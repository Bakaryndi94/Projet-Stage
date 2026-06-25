# HELP 94 — Site vitrine (version finale)

Site professionnel prêt à être mis en ligne. HTML5 + CSS + Bootstrap 5, entièrement responsive.

## Comment l'utiliser

1. Décompresse le ZIP.
2. Ouvre `index.html` pour visualiser en local (la navigation fonctionne).
3. Pour la mise en ligne : déploie le dossier sur Netlify (drag-and-drop).

> ⚠️ Le formulaire de contact ne fonctionne qu'une fois le site déployé en ligne (Web3Forms), pas en local.

## Arborescence

help94/
├── index.html                 Accueil
├── coaching.html              Coaching scolaire & orientation
├── accompagnement.html        Accompagnement & vie sociale
├── tarifs.html                Tarifs
├── contact.html               Formulaire (le SEUL du site) + coordonnées
├── merci.html                 Page de confirmation après envoi
├── mentions-legales.html      Mentions légales
├── confidentialite.html       Politique de confidentialité (RGPD)
└── assets/
    ├── css/styles.css         Charte « Confiance & Sérénité »
    └── img/                   Images (logo + photos + illustrations)

## État de finalisation

VALIDÉ :
- HTML 100% valide W3C sur les 8 pages (validateur strict).
- Aucun lien mort : tous les liens internes pointent vers des pages existantes.
- Aucune faute d'orthographe / grammaire (relecture complète).
- Aucune mention fausse : plus de CESU / crédit d'impôt / gratuité.
- Toutes les images ont un attribut alt (accessibilité).
- Un seul formulaire dans tout le site (page Contact), branché sur Web3Forms.
  Toutes les pages renvoient vers cette page.
- Coordonnées harmonisées partout : 06 40 40 35 29 / catherine-szewezuk@orange.fr
- Réseaux : seul Facebook (groupe HELP 94). Instagram et LinkedIn retirés.
- Mentions légales : SIREN 512 786 229, SIRET 512 786 229 00017, hébergeur Netlify.

À COMPLÉTER PAR TOI :
- Les tarifs (page Tarifs affiche « — € · à compléter »).
- La clé Web3Forms : actuellement le formulaire envoie vers ta boîte Gmail de test.
  Pour la prod, génère une clé avec catherine-szewezuk@orange.fr et remplace
  uniquement la clé dans contact.html (ligne ~119).
