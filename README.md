# 📊 RenphoAnalytics v1.5.0

**RenphoAnalytics** ist eine leistungsstarke, webbasierte Dashboard-Anwendung zur Analyse von Körperzusammensetzungsdaten. Die App ermöglicht den automatisierten Import von Renpho-Gesundheitsdaten, verschlüsselt sensible Informationen und bietet interaktive Visualisierungen sowie KI-gestützte Prognosen.

---

## 🛠 Verwendete Technologien & Sprachen

Dieses Projekt basiert auf einem modernen Full-Stack-Ansatz unter Verwendung folgender Sprachen und Frameworks:

### **Backend**
* **Python 3.8+**: Die Kernlogik der Anwendung.
* **Flask**: Leichtgewichtiges Web-Framework für Routing und Server-Logik.
* **SQLAlchemy / PyMySQL**: Datenbank-Abstraktion und Anbindung an MySQL/MariaDB.
* **Pandas**: Datenverarbeitung und Analyse der CSV-Importe.
* **Cryptography (Fernet)**: AES-256 Verschlüsselung der Gesundheitsdaten.
* **APScheduler**: Planung und Ausführung der automatisierten Hintergrund-Importe.

### **Frontend**
* **HTML5 & CSS3**: Struktur und modernes "Glassmorphism" Design.
* **JavaScript (Vanilla)**: Interaktive Logik, Countdown-Timer und UI-Sperren.
* **Bootstrap 5**: Responsives Grid-System und UI-Komponenten.
* **Chart.js**: Leistungsstarke Engine für die interaktiven Multi-Achsen-Diagramme.
* **FontAwesome 6**: Medizinische und funktionale Icons.
* **Flatpickr**: Moderner Kalender- und Zeitraumpicker.

### **Datenbank**
* **MySQL / MariaDB**: Strukturierte Speicherung der verschlüsselten Benutzer- und Messdaten.

---

## 🔥 Kernfunktionen

### 1. Intelligentes Daten-Management
* **Vollautomatischer Import:** Überwacht das Verzeichnis `/var/www/html/renpho/import` und liest neue CSV-Daten alle 60 Minuten ein.
* **AES-256 Verschlüsselung:** Alle Gesundheitsdaten werden verschlüsselt gespeichert (Datenbank-Leaks bleiben unlesbar).
* **Manueller CSV-Upload:** Drag-and-Drop Funktion direkt im Browser.

### 2. Interaktives Dashboard
* **Live-Analyse (Multi-Axis Chart):** Visualisierung von Gewicht, BMI, Körperfett, Wasser und BMR in einem kombinierten Diagramm.
* **Status-Tracker:** Anzeige des aktuellsten Messstands ("Stand: Datum") und dynamischer Import-Countdown.
* **Farbcodierter Countdown:** Weiß (> 30 Min), Grün (< 30 Min), Rot (< 5 Min) mit anschließendem Auto-Reload.

### 3. Deep-Dive Analyse (13 Metriken)
Jede Messwert-Kachel öffnet per Klick ein detailliertes Analyse-Modal mit:
* **Grafischer Bewertung:** Ampelsystem zur schnellen Einordnung der Gesundheit.
* **Experten-Wissen:** Medizinische Hintergründe und WHO-Richtlinien zu jedem Wert.

### 4. KI & Prognose-Tools
* **Ziel-Simulator:** Live-Berechnung der Dauer bis zum Wunschgewicht basierend auf dem Kaloriendefizit.
* **Bio-Alter-Projektion:** Berechnung des metabolischen Alters bei Erreichen des Zielgewichts.

---

## ⚙️ Installation & Setup

1.  **Repository klonen:**
    ```bash
    git clone [https://github.com/dein-nutzername/renpho-analytics.git](https://github.com/dein-nutzername/renpho-analytics.git)
    cd renpho-analytics
    ```
2.  **Abhängigkeiten installieren:**
    ```bash
    pip install flask flask-sqlalchemy sqlalchemy pymysql pandas cryptography apscheduler werkzeug
    ```
3.  **App starten:**
    ```bash
    python3 app.py
    ```
4.  **Konfiguration:**
    Navigiere zu `http://localhost:5001/setup` zur Ersteinrichtung.

---

## 🔒 Sicherheit & Datenschutz
* **Verschlüsselung:** Ohne den individuellen Key in der `config.bin` sind die Datenbankwerte wertlos.
* **UI-Sperren:** Rechtsklick und F12-Sperre zum Schutz der App-Integrität.
* **Session-Security:** Passwort-Hashing nach modernsten Standards (PBKDF2).

---
**Entwickelt von:** 2026 Malte Speck

<img width="1920" height="1080" alt="2025-12-25 14_17_31-Login _ RenphoAnalytics und 3 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/d0d5bd94-9842-4389-856f-3918b22b76ec" />
<img width="1920" height="1080" alt="2025-12-25 14_37_48-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/fe5373b1-b26a-46bb-bd99-6e07734748e8" />
<img width="1920" height="1080" alt="2025-12-25 14_37_55-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/a94538dd-de82-4f4f-a88b-3a9fc1ef6bd8" />
<img width="1920" height="1080" alt="2025-12-25 14_38_16-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/d5bf6799-e7c9-41b8-90d6-f4e178e5e355" />
<img width="1920" height="1080" alt="2025-12-25 14_47_52-Clipboard" src="https://github.com/user-attachments/assets/7860e098-2a06-42ce-a03f-712145945a9e" />
<img width="1920" height="1080" alt="2025-12-25 14_38_59-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/0a8ecb27-4582-486f-8e05-4a1a4257eb69" />
<img width="1920" height="1080" alt="2025-12-25 14_39_14-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/4a13e17a-c97d-4a2e-bb83-ff949b536fdc" />
<img width="1920" height="1080" alt="2025-12-25 14_39_45-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/26e71e13-45cf-46cd-8ff3-7236d1bb47a9" />
<img width="1920" height="1080" alt="2025-12-25 14_40_02-RenphoAnalytics und 2 weitere Seiten - Maltex – Microsoft​ Edge" src="https://github.com/user-attachments/assets/c42af456-4a64-468d-8091-61cab6890f69" />
