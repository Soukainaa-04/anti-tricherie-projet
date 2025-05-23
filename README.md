 🎓 Projet Anti-Tricherie Académique – Détection par Reconnaissance Faciale

 📌 Description

Dans le cadre de la lutte contre la triche en milieu académique, ce projet propose une solution semi-automatisée intégrant des tables intelligentes et des caméras pour la reconnaissance faciale. Lorsqu’une anomalie est détectée par la table , une LED rouge s’allume, déclenchant automatiquement la caméra pour analyser le visage de l’étudiant. En cas de confirmation de fraude, un e-mail est envoyé au coordinateur.

 🛠 Fonctionnalités principales

- 🔴 Détection de fraude par table intelligente (via capteurs intégrés)
- 📸 Reconnaissance faciale de l’étudiant activée par l’allumage de la LED rouge
- 🚨 Détection de tentative de triche 
- 📧 Envoi automatique d’un e-mail au coordinateur avec les détails de l’alerte

💡 Architecture du système

- Table intelligente dotée de capteurs et d’une LED rouge
- Caméra complémentaire, activée uniquement lorsqu’une alerte est détectée
- Module de reconnaissance faciale des étudiants
- Système d’alerte automatique via envoi d’e-mails

🧠 Technologies utilisées

- Python pour le développement global
- OpenCVpour la capture vidéo et la reconnaissance faciale
- MediaPipe ou Dlib pour la détection de visage
- smtplib et email (Python) pour l'envoi automatique d'e-mails
- SQLite pour le stockage local des alertes

⚙️ Installation

Prérequis
- Python 3.8 ou plus
- Pip
- Webcam connectée
- Connexion Internet pour l’envoi des e-mails"
- Capteurs de la table connectés via un module compatible ( Arduino)

 Installation des dépendances
```bash
git clone https://github.com/tonPseudo/anti-tricherie-projet.git
cd anti-tricherie-projet
pip install -r requirements.txt
