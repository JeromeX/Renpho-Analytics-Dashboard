# 📈 Renpho Analytics Dashboard

Ein leistungsstarkes, Flask-basiertes Dashboard zur detaillierten Analyse von Körperzusammensetzungs-Daten der Renpho-Waagen. Visualisiere deinen Fortschritt über das Gewicht hinaus – inklusive Körperfett, Muskelmasse, BMI und mehr.

### 🛠 Technologien
Backend: Python / Flask
Datenbank: MySQL (SQLAlchemy)
Frontend: HTML5, Bootstrap 5, FontAwesome 6
Charts: Chart.js
PDF-Export: jsPDF / jsPDF-AutoTable
Automatisierung: APScheduler

### Voraussetzungen
- Python 3.8+
- MySQL Server

### 🔒 Datenschutz
Alle biometrischen Daten werden vor der Speicherung in der Datenbank mittels AES-Verschlüsselung (Fernet) gesichert. Nur der eingeloggte Benutzer kann seine eigenen Daten entschlüsseln.

<img width="1920" height="1080" alt="2025-12-25 14_17_31-Login _ RenphoAnalytics und 3 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/d0d5bd94-9842-4389-856f-3918b22b76ec" />
<img width="1920" height="1080" alt="2025-12-25 14_37_48-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/fe5373b1-b26a-46bb-bd99-6e07734748e8" />
<img width="1920" height="1080" alt="2025-12-25 14_37_55-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/a94538dd-de82-4f4f-a88b-3a9fc1ef6bd8" />
<img width="1920" height="1080" alt="2025-12-25 14_38_16-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/d5bf6799-e7c9-41b8-90d6-f4e178e5e355" />
<img width="1920" height="1080" alt="2025-12-25 14_47_52-Clipboard" src="https://github.com/user-attachments/assets/7860e098-2a06-42ce-a03f-712145945a9e" />
<img width="1920" height="1080" alt="2025-12-25 14_38_59-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/0a8ecb27-4582-486f-8e05-4a1a4257eb69" />
<img width="1920" height="1080" alt="2025-12-25 14_39_14-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/4a13e17a-c97d-4a2e-bb83-ff949b536fdc" />
<img width="1920" height="1080" alt="2025-12-25 14_39_45-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/26e71e13-45cf-46cd-8ff3-7236d1bb47a9" />
<img width="1920" height="1080" alt="2025-12-25 14_40_02-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/c42af456-4a64-468d-8091-61cab6890f69" />




### ✨ Features :
- **Interaktives Dashboard:** Visualisierung von Gewicht, Fettanteil, Muskelmasse, Wasser, BMI, Viszeralfett, Knochenmasse und BMR mittels Chart.js.
- **Bunte Navigation:** Intuitive Benutzeroberfläche mit thematisch farblich getrennten Sektionen (Dashboard, Details, Analyse, Gesundheit, Bericht).
- **Ziel- & Planer:** Berechne dein Zieldatum basierend auf deiner Kalorienzufuhr und verfolge deinen Fortschritt grafisch.
- **Automatischer Import:** Überwacht einen definierten Ordner und importiert neue Renpho-CSV-Exporte automatisch jeden Sonntag um 09:00 Uhr.
- **Gesundheitsberichte:** Erstelle professionelle PDF-Berichte mit Trend-Indikatoren (▲/▼) und anpassbaren Spaltenfiltern.
- **Sicherheit:** Verschlüsselte Speicherung sensibler Gesundheitsdaten in einer MySQL-Datenbank.
- **Multi-User & Admin:** Benutzerverwaltung mit Rollensystem (Admin/User).

**Erstellt mit ❤️ für eine gesündere Zukunft.** 
