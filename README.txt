

V5.7 — CORRECTION DATE DU JOUR + RAPPELS J-1
Correction importante:
- Deux fonctions portaient le même nom `localDateKey` dans V5.6.
- La deuxième écrasait la première et cassait la détection de "aujourd'hui" et "demain".
- Cela expliquait la case Date vide et l'absence de rappel J-1.

Ajouts:
- Date du jour affichée sur l'accueil.
- Date du jour clairement entourée/surlignée dans chaque calendrier.
- Calendrier indique aussi la date de demain.
- Rappel J-1 utilise maintenant la vraie date locale de l'iPhone.
- Si aucun événement n'est prévu demain, l'accueil l'indique explicitement.
