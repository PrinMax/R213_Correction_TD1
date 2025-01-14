__Objectif__: Au cours des TDs, nous allons développer un site web pour un conservatoire tout en pratiquant Astro.

Commencez par l'installation : Guide d'installation Astro

Installez Tailwind avec la commande :

 npx astro add tailwind
Installez l'adaptateur Netlify pour que le site puisse être déployé sur Netlify avec la commande (https://docs.astro.build/fr/guides/integrations-guide/netlify/):

 npx astro add netlify
Supprimez tous les fichiers .astro sauf index.astro.

Créez un nouveau layout contenant un composant header et footer, ainsi qu'un contenu entre les deux.

Passez le titre de la page en tant que props au layout.

Créez un menu dans le header et un message dans le footer.