PLANNING FAMILIAL V5.5 — IMPORT CALENDRIER

Fichiers :
- index.html : Planning familial existant, conservé avec les 3 profils Edan / Otilia / Kayla.
- import-calendar.html : écran de vérification des événements du calendrier papier + SD35.

Fonctionnement :
1. Ouvrir le Planning familial.
2. Cliquer sur « Importer / vérifier le calendrier familial ».
3. Attribuer les séries (Gym, Maths) et les événements particuliers.
4. Décocher/corriger ce qui ne doit pas être importé.
5. Cliquer « Valider et envoyer au Planning familial ».
6. Les événements sont ajoutés à Firebase dans familyEvents sans remplacer dispatches, activités existantes, horaires, profils ou autres données.

Sécurité :
- Connexion Firebase obligatoire.
- Les événements sont dédupliqués par date/personne/titre/heure.
- Un nouvel envoi met à jour les mêmes événements au lieu de les multiplier.


V5.6 — CALENDRIER EDAN + RAPPELS J-1
- Edan possède maintenant le même bouton Calendar que les autres profils, même lorsqu'il n'y a aucun dispatch.
- Les événements importés qui lui sont attribués apparaissent dans son calendrier.
- La page d'accueil affiche automatiquement les événements prévus pour demain pour Edan, Otilia et Kayla.
- Chaque profil affiche aussi un encadré « Rappel pour demain ».
- Bouton « Activer les alertes » : si le navigateur autorise les notifications, une notification est envoyée lorsque l'application est ouverte/revient au premier plan et qu'un événement existe pour demain.
- Pour recevoir une vraie notification lorsque l'application est complètement fermée, il faudra ajouter ensuite Web Push/FCM + service worker.
