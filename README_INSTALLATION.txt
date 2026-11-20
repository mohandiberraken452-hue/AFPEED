AFPEED DIGITAL — VERSION GITHUB PAGES (SITE STATIQUE)
====================================================

CONTENU
- index.html : page d'entrée
- app.js : navigation, français/arabe, orientation locale
- styles.css : styles adaptés de l'interface AFPEED fournie
- icon.svg / icon-192.png / icon-512.png : icônes fournies
- manifest.webmanifest : métadonnées du site
- .nojekyll : empêche Jekyll de transformer le site

IMPORTANT
Ce ZIP est une ADAPTATION STATIQUE, pas le serveur AFPEED DIGITAL COMPLETE.
GitHub Pages n'héberge pas Node.js, Next.js en mode serveur, Prisma ou PostgreSQL.
Il n'y a PAS de comptes, inscriptions, base de données, attestations, messagerie,
admin, gestion de projets ni catalogue dynamique dans cette version.
Les pages publiques et la navigation français/arabe sont disponibles.
Aucune donnée de la base PostgreSQL locale n'a été copiée.
Les données dynamiques de l'application originale ne sont pas dans le ZIP source.

PUBLICATION GRATUITE SUR GITHUB PAGES (SANS TERMINAL)
1. Ouvrir https://github.com/new et se connecter.
2. Nom du dépôt : AFPEED-DIGITAL (ou autre nom sans espaces).
3. Choisir Public (GitHub Pages gratuit pour les dépôts publics).
4. Créer le dépôt.
5. Sur le PC, EXTRAIRE ce ZIP dans un dossier.
6. Dans le dépôt GitHub, choisir "Add file" > "Upload files".
7. Envoyer les FICHIERS EXTRAITS à la RACINE du dépôt : index.html,
   app.js, styles.css, .nojekyll, manifest.webmanifest et les icônes.
   Ne PAS envoyer le ZIP seul : GitHub Pages ne l'extrait pas.
8. Cliquer "Commit changes".
9. Ouvrir "Settings" > "Pages".
10. Dans "Build and deployment", sélectionner "Deploy from a branch".
11. Branch : main ; Folder : / (root) ; puis Save.
12. Attendre quelques minutes. Le lien est indiqué dans Settings > Pages.

LIEN ATTENDU
https://VOTRE-IDENTIFIANT.github.io/AFPEED-DIGITAL/

REMARQUES
- Le dépôt étant Public, le code source du site est visible par tous.
- Ne JAMAIS publier .env, clés, mots de passe, fichiers de base de données,
  exports personnels, pièces jointes privées ni les sources serveur complètes.
- Le site fonctionne lorsque votre PC est éteint.
- GitHub Pages n'offre pas une garantie de conservation à vie.
- Conserver une copie du ZIP et de l'application originale.
- La langue choisie est enregistrée localement dans le navigateur.
- Le mini-questionnaire d'orientation ne transmet pas de données.
- Les pages sont accessibles par des liens du type #/courses et #/projects.
- Pour remplacer des textes, modifier app.js puis republier ce fichier.

TEST LOCAL
Double-cliquer sur index.html pour un aperçu. Certaines fonctions du navigateur
peuvent exiger un serveur local : dans ce cas, ouvrir PowerShell dans le dossier
et exécuter : py -m http.server 8080
Puis ouvrir http://localhost:8080

Fichiers sources de l'utilisateur utilisés :
- app/globals.css (styles d'origine)
- components/App.tsx (structure et textes d'accueil)
- public/icon.svg, icon-192.png, icon-512.png

La version originale AFPEED DIGITAL COMPLETE n'est pas modifiée.
