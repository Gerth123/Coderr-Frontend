# Coderr - Jobplattform Frontend

Dieses Repository enthält das Frontend der **Coderr** Jobplattform. Coderr ermöglicht eine einfache Verbindung zwischen Unternehmen und Kunden, um Angebote zu verwalten und miteinander zu interagieren. Das Frontend kommuniziert über eine REST-API mit dem Backend, das mit **Python**, **Django** und **Django REST Framework** entwickelt wurde.

## Funktionen

- **Login und Registrierung**: Benutzer können sich registrieren und anmelden.
- **Angebotsübersicht**: Eine Liste aller verfügbaren Jobangebote wird angezeigt.
- **Angebotsdetails**: Detaillierte Ansichten zu einzelnen Angeboten.
- **Profilverwaltung**: Benutzer können ihre eigenen Profile (Kunden- oder Unternehmensprofile) verwalten.
- **Fremdansicht von Profilen**: Ermöglicht das Betrachten von Profilen anderer Nutzer (Kunden oder Unternehmen).

## Technologie-Stack

- **Programmiersprache**: JavaScript
- **Framework**: Vanilla JavaScript
- **Styling**: CSS
- **API-Kommunikation**: Interaktion mit dem Backend über die REST-API (Django REST Framework)

## Verzeichnisstruktur

```plaintext
/coderr-frontend
├─ business_profile.html          # Seite für das Unternehmensprofil
├─ customer_profile.html          # Seite für das Kundenprofil
├─ imprint.html                   # Impressum-Seite
├─ index.html                     # Startseite
├─ login.html                     # Login-Seite
├─ offer.html                     # Detailansicht eines einzelnen Angebots
├─ offer_list.html                # Übersicht der verfügbaren Angebote
├─ own_profile.html               # Eigene Profilübersicht
├─ privacy_policy.html            # Datenschutzrichtlinien
├─ registration.html              # Registrierungsseite
├─ scripts
│  ├─ business_profile.js         # JavaScript für Unternehmensprofil
│  ├─ customer_profile.js         # JavaScript für Kundenprofil
│  ├─ index.js                    # JavaScript für die Startseite
│  ├─ login.js                    # JavaScript für Login
│  ├─ offer_list.js               # JavaScript für die Angebotsübersicht
│  ├─ profile.js                  # JavaScript für Profilfunktionen
│  ├─ registration.js             # JavaScript für die Registrierung
│  ├─ single_offer.js             # JavaScript für Angebotsdetails
│  └─ template
│     ├─ business_profile_template.js  # Vorlagen für Unternehmensprofil
│     ├─ customer_profile_template.js  # Vorlagen für Kundenprofil
│     ├─ offer_list_template.js       # Vorlagen für die Angebotsübersicht
│     ├─ profile_business_templates.js # Vorlagen für Unternehmensprofile
│     ├─ profile_customer_templates.js # Vorlagen für Kundenprofile
│     └─ single_offer_template.js    # Vorlagen für Angebotsdetails
├─ shared
│  ├─ scripts
│  │  ├─ api.js                    # API-Integrationshilfe
│  │  ├─ auth.js                   # Authentifizierungsfunktionen
│  │  ├─ config.js                 # Konfigurationseinstellungen
│  │  ├─ form_helper.js            # Hilfsfunktionen für Formulare
│  │  ├─ header.js                 # Header-Funktionen
│  │  ├─ offer_crud.js             # CRUD-Operationen für Angebote
│  │  ├─ order_crud.js             # CRUD-Operationen für Bestellungen
│  │  ├─ redirect.js               # Umleitungsfunktionen
│  │  ├─ review_crud.js            # CRUD-Operationen für Bewertungen
│  │  ├─ template
│  │  │  ├─ header_template.js     # Vorlagen für Header
│  │  │  ├─ offer_templates.js     # Vorlagen für Angebote
│  │  │  ├─ order_templates.js     # Vorlagen für Bestellungen
│  │  │  └─ review_templates.js    # Vorlagen für Bewertungen
│  │  ├─ ui_helper.js             # Benutzeroberflächenhilfen
│  │  └─ user_crud.js             # CRUD-Operationen für Benutzer
│  └─ styles
│     ├─ assets.css                # Allgemeine Stile für Assets
│     ├─ fonts.css                 # Schriftarten-Stile
│     ├─ form.css                  # Stile für Formulare
│     ├─ header_footer.css         # Stile für Header und Footer
│     ├─ order_list.css            # Stile für die Bestellübersicht
│     ├─ standard.css              # Standardstile
│     └─ variables.css             # Variablen für CSS
└─ styles
   ├─ business_profile.css        # Stile für Unternehmensprofile
   ├─ customer_profile.css        # Stile für Kundenprofile
   ├─ index.css                   # Stile für die Startseite
   ├─ login.css                   # Stile für die Login-Seite
   ├─ offer.css                   # Stile für Angebotsdetails
   ├─ offer_list.css              # Stile für die Angebotsübersicht
   ├─ own_profile.css             # Stile für das eigene Profil
   └─ registration.css            # Stile für die Registrierungsseite
```

## Kontakt

Bei Fragen oder Anregungen wende dich gerne an kontakt@robin-gerth.de.
