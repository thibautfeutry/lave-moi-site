# Lave-Moi ! : site vitrine

Landing page du centre de lavage de contenants réemployables Lave-Moi ! (Côte d'Opale), en partenariat avec l'ESAT du Boulonnais.

- `index.html` : la page, HTML/CSS sans framework, fidèle à la charte graphique (Moon Get Heavy, Folks, palette bleu/orange/vert).
- `merci.html` : page affichée après l'envoi du formulaire.
- `assets/` : logo, polices, photos du centre.

## Déploiement

Hébergé sur Netlify : chaque push sur `main` republie le site. Le formulaire de contact passe par Netlify Forms (formulaire `contact`). Les notifications se configurent dans Netlify > Forms > Notifications.

### Attention à la publication manuelle

Publier à la main un ancien déploiement dans Netlify (« Publish deploy ») verrouille la publication automatique : les nouveaux pushs sont construits mais pas mis en ligne. Pour revenir au fonctionnement normal : Deploys → « Start auto publishing ».
