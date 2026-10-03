# Veille Benj.

Deux flux de test extraits uniquement des pages web, sans utiliser les flux RSS des éditeurs ni ouvrir les articles.

- IA | BDM : https://benjamin-ripert.github.io/veille-benj/veille-benj.xml
- IA | Le Monde : https://benjamin-ripert.github.io/veille-benj/ia-lemonde.xml

Chaque flux contient les 12 premières actualités dans l’ordre de sa page source : titre, extrait, image, lien et date. Les images restent hébergées par les éditeurs. L’icône rss.png est commune.

Sources : https://www.blogdumoderateur.com/ia/ et https://www.lemonde.fr/intelligence-artificielle/.

Ces fichiers sont des instantanés. BDM fournit 11 extraits tronqués sur 12. Le Monde nécessite actuellement une lecture dans un navigateur ; une requête HTTP directe renvoie une page de vérification. Sa date de publication est obtenue depuis l’URL et l’heure affichée sur la carte, avec le fuseau Europe/Paris. La collecte automatique n8n n’est pas encore installée.
