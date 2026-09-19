# 🛡️ Système de Détection d'Attaques Réseau (DPI & Intelligence Artificielle)

Projet réalisé dans le cadre de mon **stage académique en Cybersécurité & Réseaux**.

---

## 📌 Présentation du Projet
Ce projet consiste en la conception, l'implémentation et l'évaluation d'un banc d'essai d'un **Système de Détection d'Intrusions (NIDS) hybride**. Il associe :
- L'inspection approfondie des paquets (**Deep Packet Inspection - DPI**) pour l'analyse des protocoles et signatures.
- Un modèle de Machine Learning non surveillé (**Isolation Forest**) pour détecter les comportements anormaux et attaques sans signature préexistante.

---

## 🛠️ Environnement & Technologies
- **Hyperviseur & OS :** VMware Workstation, Kali Linux (Attaquant), Metasploitable2 (Cible).
- **Analyse & DPI :** Wireshark, TShark, Scapy.
- **Machine Learning :** Python (Pandas, Scikit-learn, Isolation Forest).
- **Attaques Simulées :** Balayage de ports (Nmap), SYN Flood (Hping3), exploits Metasploit.

---

## 📊 Principaux Résultats
- **Détection d'Anomalies :** Capture et classification efficace du trafic anormal par rapport au trafic légitime de référence.
- **Réduction des Faux Positifs :** Corrélation entre l'analyse de paquets (DPI) et l'isolation comportementale par IA.

---

## 👤 Auteur
- **Djimen Njo’sseu Joël Miguel**
- Étudiant en Licence Réseaux & Cybersécurité
