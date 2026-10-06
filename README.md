# Redirection glyceo.app → glyami.app

L'app Glycéo s'appelle désormais **Glyami**. Ce dépôt sert `glyceo.app` (GitHub Pages, HTTPS) et
renvoie chaque adresse vers la même page de `https://glyami.app` : les pages connues par
`<meta refresh>` + `<link rel="canonical">`, toutes les autres par `404.html`.
Une redirection web OVH ne suffit pas : `.app` impose HTTPS (HSTS préchargé).

Le site lui-même est publié depuis `jalil0404/glyceo-site` (domaine `glyami.app`).
