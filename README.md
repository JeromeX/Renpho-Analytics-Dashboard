# 📈 Renpho Analytics Dashboard

**Frontend**
### Sprachen: HTML5 (Struktur) und CSS3 (Design).
### Styling-Framework: Bootstrap 5
### Icons: FontAwesome 6

Ein leistungsstarkes, Flask-basiertes Dashboard zur detaillierten Analyse von Körperzusammensetzungs-Daten der Renpho-Waagen. Visualisiere deinen Fortschritt über das Gewicht hinaus – inklusive Körperfett, Muskelmasse, BMI und mehr.

<img width="1920" height="1080" alt="2025-12-22 00_32_21-Renpho Importer Tool und 1 weitere Seite - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/fb262268-c9ea-4b30-a229-3f2bcd695b6d" />
<img width="1920" height="1080" alt="2025-12-22 00_32_12-Renpho Importer Tool und 1 weitere Seite - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/18b16fd0-0d8e-4d08-9e91-c5dfc34d50bc" />
<img width="1920" height="1080" alt="2025-12-22 00_32_26-Renpho Importer Tool und 1 weitere Seite - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/180bf1ab-34d7-4152-9089-c9d2373ddd70" />
<img width="1920" height="1080" alt="2025-12-22 00_32_31-Renpho Importer Tool und 1 weitere Seite - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/3c4f2296-13f0-43af-aa3e-96c064a3810f" />
<img width="1920" height="1080" alt="2025-12-22 00_32_34-Renpho Importer Tool und 1 weitere Seite - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/b5dd32b6-76ac-40f7-b7a6-1876291e65ae" />
<img width="1920" height="1080" alt="2025-12-22 00_32_45-Renpho Importer Tool und 1 weitere Seite - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/e3894462-102f-46fb-82a3-2a9e630852d9" />

### ✨ Features :
- **Interaktives Dashboard:** Visualisierung von Gewicht, Fettanteil, Muskelmasse, Wasser, BMI, Viszeralfett, Knochenmasse und BMR mittels Chart.js.
- **Bunte Navigation:** Intuitive Benutzeroberfläche mit thematisch farblich getrennten Sektionen (Dashboard, Details, Analyse, Gesundheit, Bericht).
- **Ziel- & Planer:** Berechne dein Zieldatum basierend auf deiner Kalorienzufuhr und verfolge deinen Fortschritt grafisch.
- **Automatischer Import:** Überwacht einen definierten Ordner und importiert neue Renpho-CSV-Exporte automatisch jeden Sonntag um 09:00 Uhr.
- **Gesundheitsberichte:** Erstelle professionelle PDF-Berichte mit Trend-Indikatoren (▲/▼) und anpassbaren Spaltenfiltern.
- **Sicherheit:** Verschlüsselte Speicherung sensibler Gesundheitsdaten in einer MySQL-Datenbank.
- **Multi-User & Admin:** Benutzerverwaltung mit Rollensystem (Admin/User).

## 🚀 Installation

### Voraussetzungen
- Python 3.8+
- MySQL Server

### 🛠 Technologien
Backend: Python / Flask
Datenbank: MySQL (SQLAlchemy)
Frontend: HTML5, Bootstrap 5, FontAwesome 6
Charts: Chart.js
PDF-Export: jsPDF / jsPDF-AutoTable
Automatisierung: APScheduler

### 🔒 Datenschutz
Alle biometrischen Daten werden vor der Speicherung in der Datenbank mittels AES-Verschlüsselung (Fernet) gesichert. Nur der eingeloggte Benutzer kann seine eigenen Daten entschlüsseln.

Erstellt mit ❤️ für eine gesündere Zukunft.
