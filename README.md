# AsianKC

Carnet privé (PWA) avec synchronisation Google Drive.

- **App** : `index.html` (mono-fichier, vanilla JS)
- **Hébergement** : Cloudflare Pages → https://asiankc.pages.dev/
- **Déploiement** : automatique à chaque `git push` sur la branche `main`

## Mettre à jour le site

```bash
git add -A
git commit -m "description du changement"
git push
```

Cloudflare reconstruit et publie automatiquement en ~1 minute.
