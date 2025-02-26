# RFID Access Control System  

Ce projet utilise un lecteur **RFID MFRC522** avec un microcontrôleur (ex. Arduino) pour contrôler l'accès en fonction des cartes RFID autorisées.  

## 🚀 Fonctionnalités  
- Lecture des cartes RFID.  
- Comparaison de l'UID avec une liste de cartes autorisées.  
- Affichage de l'UID et du statut d'accès sur le moniteur série.  

## 🛠 Matériel Requis  
- 🟢 Arduino (Uno, Mega, Nano, etc.)  
- 🟢 Module RFID **MFRC522**  
- 🟢 Carte RFID ou porte-clé RFID  
- 🟢 Câbles de connexion  

## 📜 Installation et Utilisation  
| Étape | Description |
|-------|------------|
| 📥 1 | **Cloner le repo** : `git clone https://github.com/ton_nom_utilisateur/RFID_Access_Control.git` |
| 🎛️ 2 | **Brancher le module RFID MFRC522** selon le tableau ci-dessus |
| 📝 3 | **Ouvrir le fichier `RFID_Access_Control.ino` dans l'IDE Arduino** |
| 🔧 4 | **Modifier l’UID dans le code** (`content.substring(1) == "BD 31 15 2B"`) pour ajouter ta carte autorisée |
| 🔼 5 | **Téléverser le code sur l’Arduino** |
| 🎯 6 | **Ouvrir le moniteur série et tester avec une carte RFID** |


## 🛠 Matériel Requis  

| 🎛️ Composant  | 🔌 Connexion avec Arduino |
|--------------|--------------------------|
| **SDA (SS)**  | 10 |
| **SCK**       | 13 |
| **MOSI**      | 11 |
| **MISO**      | 12 |
| **GND**       | GND |
| **RST**       | 9 |
| **3.3V**      | 3.3V |

## 📷 Aperçu  

| 🖼️ Composant | 📌 Image |
|--------------|---------|
| **Module RFID MFRC522** | ![RFID](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/MFRC522_-_Front.jpg/250px-MFRC522_-_Front.jpg) |
| **Carte RFID** | ![Carte RFID](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/RFID_Card_Transponder.jpg/250px-RFID_Card_Transponder.jpg) |

