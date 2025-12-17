# gmail-sheets-telegram-automation
Workflow Make qui enregistre les emails Gmail dans Google Sheets et envoie une notification Telegram.
Pour la création de ma première automatisation, j’ai choisi de commencer simplement afin de me familiariser avec l’outil. J’ai donc conçu un scénario qui enregistre automatiquement les emails Gmail dans Google Sheets et envoie une notification via un chatbot Telegram.
J’ai connecté mon compte Gmail à un trigger qui surveille l’arrivée de nouveaux emails.
J’ai créé une feuille Google Sheets avec trois colonnes : Expéditeur, Sujet, et Date.
J’ai ensuite développé et configuré mon premier chatbot, nommé Alexia.
Logique du scénario : Lorsqu’un nouvel email est reçu, le workflow extrait le nom de l’expéditeur, le sujet et la date. Ces informations sont ajoutées automatiquement dans les colonnes correspondantes de Google Sheets. En parallèle, Telegram est configuré pour récupérer l’expéditeur et le sujet afin de les transmettre directement dans mon chatbot Alexia, qui me notifie en temps réel.
le scénario : Trigger → Gmail → Sheets → Telegram.
https://eu1.make.com/public/shared-scenario/piVD6ybL3iQ/integration-gmail-google-sheets-telegr
Ce projet m’a permis de :
- Découvrir la logique des automatisations.  
- Manipuler Gmail, Google Sheets et Telegram via Make.  
- Créer mon premier chatbot "Alexia" pour des notifications en temps réel.  
C’est une première étape vers des automatisations plus complexes et utiles dans un contexte académique et professionnel.
