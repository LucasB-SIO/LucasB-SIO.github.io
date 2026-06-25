# Portfolio Professionnel — BTS SIO SISR

Bienvenue sur le dépôt GitHub de mon portfolio professionnel réalisé dans le cadre de ma formation en **BTS SIO** (Services Informatiques aux Organisations), option SISR (Solutions d'Infrastructure, Systèmes et Réseaux).

> **Lien du site en ligne :** [Cliquer ici pour voir mon portfolio](https://lucasb-sio.github.io)

---

##  Présentation du Projet Principal

Ce portfolio met en avant un projet majeur de mon parcours : la reconstruction, la segmentation et la sécurisation d'un réseau d'entreprise multi-VLAN (réalisé en environnement de laboratoire inspiré de mon stage chez Concentrix).

###  Architecture & Technologies Clés :
* **Segmentation Réseau :** Déploiement et isolation de **5 VLANs** spécifiques (Administration, IT/Management, Salariés/WiFi, Transit WAN, LAN Filtré).
* **Infrastructures Cisco :** Configuration de commutateurs (Cisco 2960+ / Cœur de réseau L3 9300), routage inter-VLAN (SVI), sécurisation des accès (Port-Security, Spanning-Tree Rapid-PVST+, BPDU Guard).
* **Sécurité & Pare-feu :** Implémentation d'un pare-feu **OPNsense** configuré en **Default Deny** pour un cloisonnement strict des flux.
* **Filtrage Web & Proxy :** Déploiement du **Proxy Squid** avec filtrage par catégories (listes de Toulouse) et déchiffrement des flux HTTPS à la volée (SSL Bump / MitM).
* **Supervision :** Intégration de la sonde de supervision **PRTG Network Monitor** via le protocole sécurisé **SNMP v2c**.

---

##  Compétences Techniques Validées (Portfolio GitHub)

Ce dépôt valide les compétences attendues par le référentiel du BTS SIO concernant l'utilisation des outils de versionning et de publication :
* **Compte + Dépôt :** Création et gestion d'un espace de stockage distant sur GitHub.
* **Développement Front-End :** Intégration et structuration des données en **HTML5** et création d'un design moderne/dynamique en **CSS3** (*Glassmorphism*, grilles réactives).
* **Web Hosting :** Déploiement et automatisation de la mise en ligne via **GitHub Pages**.

---

##  Structure du Dépôt

* `index.html` : Fiche descriptive et technique du projet de segmentation réseau.
* `style.css` : Feuille de style gérant l'interface graphique du portfolio.
* `README.md` : Présentation globale du projet (ce fichier).

---
 **Réalisé par :** LucasB-SIO - 2026
