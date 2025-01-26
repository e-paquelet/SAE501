# 🌐 Projet SAE 501 : Infrastructure Réseau Complexe  

## 🔎 Contexte  
Cette SAE s’est déroulée sur **1 semaine et 3 jours**, en binôme :  
- **Moi** (parcours Cybersécurité) : Sécurisation de l'infrastructure.  
- **Binôme** (parcours IoM) : Installation et configuration du Wi-Fi.  

## 🎯 Objectif  
Créer une **infrastructure réseau fonctionnelle** inspirée du concours **WorldSkills**, avec 3 sites :  
**Remote**, **HQ**, et **Internet**.  

## 🛠️ Architecture et Matériel  
- **Matériel** : 3 routeurs, 6 switches, serveurs **ESXi** et **Proxmox**, PCs, bornes Wi-Fi, tablette.  
- **Plans disponibles** :  
  - Schémas physiques (simplifié et détaillé).  
  - Schémas logiques (couches 2 & 3).
  - Schémas DNS et Routage. 

## ✅ Tâches Réalisées  
1. **Planification & Gestion** : Utilisation de **Trello** pour organiser les tâches.  
2. **Réseau** :  
   - Routage : **OSPF**, **BGP**, **VRF**, **NAT/PAT**.  
   - Switches : **EtherChannel**, **HSRP**, **VTP**, **STP**.  
3. **Déploiement de Services** :  
   - **Active Directory**, **DNS**, **GPO**, **RAID**, **serveur mail**, etc.  
4. **Automatisation** :  
   - **PowerShell** : Scripts de provisioning utilisateurs/groupes.  
   - **Cisco EEM** : Script HSRP (non fonctionnel pour cause d’incompatibilité).  
5. **Accès à Distance** : Gestion de l'ESXi via Proxmox pour le télétravail.  

## ❗ Problèmes et Solutions  
- **Simulation GNS3** : Résolu après le déploiement physique.  
- **Déploiement des certificats** : Non résolu dans les délais impartis.  
- **Connexion AD depuis DMZ** : Résolu avec une règle de filtrage.  

## 🚀 Compétences Acquises  
- Mise en place d’un réseau complexe et sécurisé sous pression.  
- Maîtrise approfondie des protocoles **OSPF**, **BGP**, et **VRF**.  
- Renforcement des compétences en **résolution de problèmes**, **travail d’équipe**, et **gestion du temps**.  

## 📂 Ressources  
- [Rapport complet 📄](./Rapport_de_synthèse_-_Groupe-11.pdf)  
- Scripts et configurations : Disponibles dans ce dépôt. 🛠️  
