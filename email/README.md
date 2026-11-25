# Images des e-mails voyageurs (Brevo)

Ce dossier héberge les images appelées par les modèles d'e-mails Brevo.
Adresse publique : `https://inscription.goodstory.events/email/…`

**Ne jamais renommer ni déplacer un fichier déjà utilisé** : les e-mails envoyés
continuent d'appeler l'ancienne adresse. Pour changer une image, ajouter un
nouveau fichier et mettre à jour le modèle.

## Organisation

| Dossier | Contenu | Exemple |
|---|---|---|
| `commun/` | Éléments Good Story utilisés par tous les voyages | `goodstory-logo-blanc.png` |
| `equipe/` | Photos de l'équipe (module « Une question ? ») | `pauline.png` |
| `clients/<client>/` | Logos d'un client, en versions validées par sa charte | `clients/rexel/rexel-logo-blanc.png` |
| `voyages/<AAAA-MM>-<client>-<voyage>/` | Images propres à un voyage : grands titres, photos | `voyages/2027-01-rexel-club-agir-canada/titre-montreal.png` |

## Règles

- Noms en minuscules, sans accents ni espaces, mots séparés par des tirets.
- Images en double résolution (2x) pour les écrans Retina ; la largeur d'affichage
  est fixée dans Brevo (contenu de l'e-mail : 536 px).
- Grands titres : en image (police Hanken Grotesk garantie, adaptés au mobile),
  toujours avec un texte alternatif dans Brevo.
- Logos clients : respecter la charte du client (version blanche sur fond foncé,
  pas d'effet ni de recoloration).

## Voyages

| Dossier | Voyage | Couleur |
|---|---|---|
| `voyages/2027-01-rexel-club-agir-canada/` | Rexel · Club Agir · Montréal, 27 janv. – 1er févr. 2027 | Glacier `#1E3A5C` |
