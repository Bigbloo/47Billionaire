# Instructions pour héberger sur GitHub Pages

Suivez ces étapes pour héberger votre landing page sur GitHub Pages :

## 1. Créer un nouveau dépôt sur GitHub

1. Connectez-vous à votre compte GitHub (ou créez-en un si vous n'en avez pas encore)
2. Cliquez sur le bouton "+" en haut à droite, puis sélectionnez "New repository"
3. Nommez votre dépôt `casino-bleu` (ou un autre nom de votre choix)
4. Laissez le dépôt en "Public" pour que GitHub Pages fonctionne gratuitement
5. Ne cochez pas "Initialize this repository with a README" car nous avons déjà créé un README
6. Cliquez sur "Create repository"

## 2. Connecter votre dépôt local à GitHub

Une fois le dépôt créé, GitHub affichera des instructions. Exécutez les commandes suivantes dans le terminal :

```bash
# Assurez-vous d'être dans le répertoire du projet
cd /Users/athomeproject/Desktop/casino-bleu-landing

# Ajoutez l'URL du dépôt distant (remplacez USERNAME par votre nom d'utilisateur GitHub)
git remote add origin https://github.com/USERNAME/casino-bleu.git

# Poussez votre code vers GitHub
git push -u origin main
```

## 3. Configurer GitHub Pages

1. Sur GitHub, accédez à votre dépôt
2. Cliquez sur "Settings" (onglet avec l'icône d'engrenage)
3. Faites défiler jusqu'à la section "GitHub Pages"
4. Dans "Source", sélectionnez "main" comme branche et "/" (root) comme dossier
5. Cliquez sur "Save"

GitHub va maintenant construire et déployer votre site. Après quelques minutes, votre landing page sera accessible à l'URL :
`https://USERNAME.github.io/casino-bleu/`

## 4. Vérifier le déploiement

1. Retournez à la section "GitHub Pages" dans les paramètres
2. Vous verrez un message indiquant "Your site is published at https://USERNAME.github.io/casino-bleu/"
3. Cliquez sur ce lien pour voir votre landing page en ligne

Félicitations ! Votre landing page Casino Bleu est maintenant hébergée gratuitement sur GitHub Pages.
