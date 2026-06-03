# ePrésence Étudiant

Site web statique de l'application ePrésence pour étudiants UDBL.

## Publication sur GitHub

1. Créez un dépôt GitHub depuis votre compte.
2. Dans ce dossier, exécutez :

```powershell
cd "c:\Users\j\Desktop\ePresence version étudiante"
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<votre-nom-utilisateur>/<nom-du-repo>.git
git push -u origin main
```

3. Activez GitHub Pages dans les paramètres du dépôt :
   - Source : branche `main`
   - Dossier : `/ (racine)`

4. L'URL publique sera :

```text
https://<votre-nom-utilisateur>.github.io/<nom-du-repo>/
```

## Accès direct

Une fois publié sur GitHub Pages, ce site sera accessible via un lien public.

Vous pouvez aussi ouvrir l'application directement avec un paramètre QR dans l'URL, par exemple :

```text
https://<votre-nom-utilisateur>.github.io/<nom-du-repo>/?code=UDBL-L3-1234-5678
```

## Notes

- Le site est entièrement contenu dans `index.html`.
- Les scripts externes nécessaires sont chargés depuis des CDN publics.
