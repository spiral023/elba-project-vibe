# ELBA Vibe - Modernes Banking Dashboard (Simulation)

![ELBA Vibe Logo](https://sp23.online/images/logo.png)

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3 - Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)](https://fontawesome.com/)

## 🌟 Beschreibung

<div align="center">
<h6><a href="https://elba-vibe.sp23.online">ELBA VIBE</a></h6>
</div>

**ELBA Vibe** ist eine moderne, interaktive Simulation eines Online-Banking-Dashboards. Es demonstriert ein benutzerfreundliches Interface mit aktuellen Web-Technologien und integriert innovative Features wie KI-gestützte Interaktionen, Gamification und personalisierte Übersichten. Dieses Projekt dient als Showcase für ein zukunftsweisendes digitales Bankerlebnis.

## ✨ Features

* **Interaktiver Splash Screen:** Begrüßt den Benutzer und stellt die neuesten Features vor, bevor das Dashboard per Klick geladen wird.
* **Responsive Benutzeroberfläche:** Passt sich verschiedenen Bildschirmgrößen an (Desktop, Tablet, Mobile).
* **Dark Mode / Light Mode:** Automatischer Dark Mode mit manueller Umschaltmöglichkeit (Speicherung im Local Storage).
* **Finanzübersicht:**
    * Interaktives Balkendiagramm (Chart.js) mit Einnahmen/Ausgaben.
    * 📊 **Peergroup Vergleich:** Visueller Vergleich der eigenen Finanzen mit einer anonymisierten Vergleichsgruppe.
    * Kontoübersicht (Giro, Sparen).
* **💬 Chatte mit deinen Finanzen:**
    * Integriertes Chat-Fenster zur Interaktion mit einem (simulierten) Finanz-Assistenten (Vorbereitet für OpenAI API-Anbindung).
    * Dynamische Chatbot-Antworten basierend auf der Eingabe.
* **✨ Hyperpersonalisierte Notifications:** (Konzept, im Dashboard angedeutet)
* **🏆 Achievements & Leaderboard:**
    * Gamification-Ansatz mit sammelbaren Abzeichen für positives Finanzverhalten (z.B. Umweltfreundlichkeit, Sparen).
    * Vergleich der gesammelten Punkte mit Freunden in einer Rangliste.
* **🛍️ Regionale Raiffeisen Boni durch Punkte:** (Konzept, angedeutet durch Achievements)
* **📞 Dein persönlicher AI Bankberater (24/7 Voice Clone):**
    * Schwebender Button zum Starten eines (simulierten) Anrufs mit dem AI Voice Clone des Bankberaters.
    * Hintergrund-Audio-Wiedergabe bei Klick.
* **🧠 Financial Health AI Engine:** (Konzept, angedeutet durch Chat & Peergroup)
* **🌐 Raiffeisen Universal MCP Server:** (Konzept, erwähnt im Splash Screen)
* **Dynamische Elemente:** Letzte Umsätze, Wichtige Funktionen, Schnellzugriff, Kontaktmöglichkeiten.
* **Benutzerdefinierte Elemente:** Profilbild, Benutzername.

## 🛠️ Technologie-Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Styling:** Tailwind CSS v3
* **Diagramme:** Chart.js v3.9.1
* **Icons:** Font Awesome v6

## 🚀 Setup & Verwendung

1.  **Keine Installation notwendig:** Da es sich um reines Frontend-Projekt handelt, ist keine Server-Installation erforderlich.
2.  **Öffnen:** Laden Sie die `index.html` (oder den entsprechenden Dateinamen, unter dem Sie den Code gespeichert haben) einfach in einem modernen Webbrowser (Chrome, Firefox, Edge, Safari).
3.  **Interagieren:**
    * Klicken Sie auf dem Splash Screen auf "Zeig mir das neue ELBA!".
    * Nutzen Sie den Dark/Light Mode Toggle in der Kopfzeile.
    * Interagieren Sie mit dem Chat-Fenster.
    * Klicken Sie auf den schwebenden AI Berater Button, um die Audio-Wiedergabe zu testen.
    * Erkunden Sie die verschiedenen Dashboard-Module.

**Hinweis:** Die Chat-Funktion ist derzeit eine Simulation. Für eine echte Interaktion mit OpenAI muss ein gültiger API-Schlüssel in der JavaScript-Variable `OPENAI_API_KEY` hinterlegt und der entsprechende Code-Abschnitt (`callOpenAI` Funktion) aktiviert werden.

## 🏗️ Struktur der Komponenten

* **Splash Screen:** Initialer Ladebildschirm mit Feature-Übersicht und Start-Button.
* **Header:** Navigation, Benutzerprofil (mit Bild), Suche, Benachrichtigungen, Theme-Toggle, Logout.
* **Main Content Area (Linke Spalte):**
    * Begrüßung
    * Finanzübersicht (Chart, Kontostände)
    * Chat-Modul
    * Wichtige Funktionen (Icon-Buttons)
    * Letzte Umsätze (Tabelle)
* **Sidebar (Rechte Spalte):**
    * Achievements (Abzeichen, Leaderboard)
    * Schnellzugriff
    * Sicherheitshinweis
    * Kontakt & Hilfe
* **Floating Button:** AI Voice Clone Berater.
* **Footer:** Impressum, Datenschutz etc., Disclaimer.

## 📝 Disclaimer

Dies ist eine vereinfachte Nachbildung und Simulation eines modernen Online-Banking-Dashboards zu Demonstrations- und Entwicklungszwecken. Es stellt keine echte Banking-Anwendung dar und verarbeitet keine echten Finanzdaten.

Powered by RAITEC!
0 lines code written! © Philipp Asanger
