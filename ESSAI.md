# Site d'essai CALENDRIERS — NE PAS UTILISER POUR LE TRAVAIL RÉEL

https://antcb.github.io/lartbo-matrice-essai/ — copie de la branche `dev/v1.62-calendriers` de la Matrice (dépôt `Antcb/lartbo-matrice`,
commit `0c809b0`, version 1.61.0), **forcée sur le projet Supabase de test « Lartbo-matrice-test » (`dthfocplfzzmkgaxhmwk`)**.
La production n'est accessible d'aucune façon (ni `?prod`, ni lien). Remplace la copie C1 précédente (toujours dans l'historique git).

Seules différences avec le commit `0c809b0` :
1. `js/config.js` : environnement fixé à « test » ; le choix gardé par le navigateur n'est ni lu ni modifié ; le bloc « production »
   est retiré (ni adresse, ni clé, ni comptes de la vraie Matrice).
2. Bandeau (`js/ui/testbanner.js`, `js/app.js`, `js/views/auth.js`) : version et base de test affichées ; plus de lien « Revenir à la vraie Matrice ».
3. Seuls les fichiers du site sont publiés (pages, `js/`, `css/`, `assets/`, `apps-script/` lu par Réglages).
4. Vérification automatique après chaque publication : `.github/workflows/verif-site-essai.yml`, `tools/essai/verifier-lien.mjs`.

À archiver ou supprimer après l'essai réel des calendriers.
