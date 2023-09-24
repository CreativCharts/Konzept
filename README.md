# Konzept

---

### Eine kurze Beschreibung vom Projekt

Dieses Projekt zielt darauf ab, eine hochgradig konfigurierbare und benutzerfreundliche Webanwendung für die Erstellung und Anpassung von Statistikdiagrammen zu entwickeln. Die Anwendung ist modular aufgebaut und folgt der Microservices-Architektur, um Skalierbarkeit und Wartbarkeit zu gewährleisten.

---

### Wer ist meine Zielgruppe?

- Datenanalysten
- Wissenschaftler
- Studierende in technischen und wissenschaftlichen Fachrichtungen
- Unternehmen, die interne Berichterstattung benötigen
- Freiberufler, die Daten visualisieren müssen

---

### Welches Problem löst mein Projekt?

Das Projekt löst das Problem der komplizierten und zeitaufwändigen Erstellung von benutzerdefinierten, interaktiven und hochwertigen Statistikdiagrammen. Es bietet eine One-Stop-Lösung für die Integration von Daten aus verschiedenen Quellen, die Auswahl aus einer Vielzahl von Diagrammtypen und die Anpassung von Diagrammen nach Benutzeranforderungen.

---

### Was ist einzigartig, welche Besonderheit(en) gibt es? (USP - Unique Selling Points)

1. Vielseitigkeit der Datenquellen: Die Möglichkeit, Daten aus einer Vielzahl von Quellen einschließlich CSV-Dateien, APIs und Datenbanken zu importieren.
2. Interaktive Diagramme: Die Diagramme sind nicht nur optisch ansprechend, sondern auch interaktiv. Benutzer können auf Elemente klicken, um weitere Informationen zu erhalten oder die Darstellung zu ändern.
3. Multi-Sprachunterstützung im Backend: Die Verwendung von Node.js, Java und C# ermöglicht leistungsstarke, spezialisierte Microservices.
4. Benutzerrollen und Berechtigungen: Verschiedene Benutzerrollen und Berechtigungen bieten ein hohes Maß an Flexibilität und Sicherheit.
5. Echtzeit-Aktualisierung und Analytics: Benutzer können in Echtzeit sehen, wie ihre Daten genutzt werden und erhalten wertvolle Einblicke durch den Analytics-Service.

---

### Technologien

- **Frontend**: Vite-React
- **Backend**: Node.js, Java, und C#
- **Datenbank**: MongoDB oder MariaDB
- **Message Queue**: RabbitMQ oder Kafka
- **API Gateway**: Zentraler Punkt für API-Anfragen
- **Containerisierung**: Docker (optional)
- **Orchestrierung**: Kubernetes (optional)

---

### Microservices-Architektur

1. **Auth-Service**: Verantwortlich für Benutzeranmeldung und -registrierung. (Node.js oder Java)
2. **Chart-Service**: Verantwortlich für das Erstellen, Bearbeiten und Löschen von Diagrammen. (Node.js oder Java)
3. **Data-Service**: Verantwortlich für den Import und Export von Daten. (C#)
4. **User-Management-Service**: Verantwortlich für die Verwaltung von Benutzerprofilen und Einstellungen. (Node.js oder Java)
5. **Export-Service**: Verantwortlich für das Exportieren von Diagrammen. (C#)
6. **Analytics-Service**: Verantwortlich für die Auswertung und Verarbeitung von Benutzerstatistiken und Diagrammdaten. (C#)
7. **Frontend-Service**: Das Frontend, entwickelt in Vite-React.

---

### Hauptfunktionen

- Benutzeranmeldung und -registrierung: Über den Auth-Service
- Verschiedene Diagrammtypen: Unterstützt durch den Chart-Service
- Datenquellen: Import durch den Data-Service
- Benutzerdefinierte Diagramme: Anpassungen durch den Chart-Service
- Interaktive Diagramme: Implementiert im Frontend-Service
- Datenexport: Export-Funktionalität durch den Export-Service
- Responsive Design: Implementiert im Frontend-Service
- Benutzerrollen und Berechtigungen: Verwaltet durch den User-Management-Service
- Echtzeit-Aktualisierung: Möglich durch den Analytics-Service und eventuell SignalR in C#

---

### Entwicklungsphasen

1. **Planung und Design**: Erstellung von Wireframes und Mockups, sowie Definition der Schnittstellen für Microservices.
2. **Entwicklung der Microservices**: Beginn mit dem Auth-Service und sukzessive Erweiterung.
3. **Frontend-Entwicklung**: Parallele Entwicklung der Frontend-Anwendung.
4. **Datenbankintegration**: Einrichtung und Integration der Datenbanken für die jeweiligen Services.
5. **Tests und Fehlerbehebung**: Durchführung von Unit-Tests und Integrationstests für jeden Microservice.
6. **Deployment**: Optionaler Einsatz von Docker und Kubernetes für Containerisierung und Orchestrierung.
7. **Dokumentation und Wartung**: Erstellung von Entwickler- und Benutzerdokumentationen.

---
