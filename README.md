# Coderr - Jobplattform Frontend

Dieses Repository enthält das Frontend der **Coderr** Jobplattform, die es Unternehmen und Kunden ermöglicht, miteinander in Kontakt zu treten und Angebote zu verwalten. Die Plattform bietet eine benutzerfreundliche Oberfläche für die Interaktion mit der API des Backends, das mit **Python**, **Django** und **Django REST Framework** entwickelt wurde.

## Features

- **Login und Registrierung**: Ermöglicht Benutzern, sich anzumelden oder zu registrieren.
- **Angebotsübersicht**: Zeigt eine Liste aller verfügbaren Angebote.
- **Angebotsdetails**: Detaillierte Ansichten zu einzelnen Angeboten.
- **Eigenes Profil**: Ermöglicht Benutzern das Verwalten ihrer Profilinformationen (Kunden- oder Unternehmensprofil).
- **Fremdansicht von Profilen**: Ermöglicht das Betrachten von Profilen anderer Nutzer (Kunden oder Unternehmen).

## Technologie-Stack

- **Programmiersprache**: JavaScript
- **Framework**: Vanilla JavaScript 
- **Styling**: CSS 
- **API**: Kommunikation mit dem Backend über die REST-API (Django REST Framework)

## Verzeichnisstruktur

```plaintext
/coderr-frontend
Coderr_frontend_v1.1.0

├─ business_profile.html
├─ customer_profile.html
├─ imprint.html
├─ index.html
├─ login.html
├─ offer.html
├─ offer_list.html
├─ own_profile.html
├─ privacy_policy.html
├─ registration.html
├─ scripts
│  ├─ business_profile.js
│  ├─ customer_profile.js
│  ├─ index.js
│  ├─ login.js
│  ├─ offer_list.js
│  ├─ profile.js
│  ├─ registration.js
│  ├─ single_offer.js
│  └─ template
│     ├─ business_profile_template.js
│     ├─ customer_profile_template.js
│     ├─ offer_list_template.js
│     ├─ profile_business_templates.js
│     ├─ profile_customer_templates.js
│     └─ single_offer_template.js
├─ shared
│  ├─ scripts
│  │  ├─ api.js
│  │  ├─ auth.js
│  │  ├─ config.js
│  │  ├─ form_helper.js
│  │  ├─ header.js
│  │  ├─ offer_crud.js
│  │  ├─ order_crud.js
│  │  ├─ redirect.js
│  │  ├─ review_crud.js
│  │  ├─ template
│  │  │  ├─ header_template.js
│  │  │  ├─ offer_templates.js
│  │  │  ├─ order_templates.js
│  │  │  └─ review_templates.js
│  │  ├─ ui_helper.js
│  │  └─ user_crud.js
│  └─ styles
│     ├─ assets.css
│     ├─ fonts.css
│     ├─ form.css
│     ├─ header_footer.css
│     ├─ order_list.css
│     ├─ standard.css
│     └─ variables.css
└─ styles
   ├─ business_profile.css
   ├─ customer_profile.css
   ├─ index.css
   ├─ login.css
   ├─ offer.css
   ├─ offer_list.css
   ├─ own_profile.css
   └─ registration.css

