# S'inscrire sur GitHub

- Connectez-vous à l'adresse `https://github.com/login` et choisissez `Create an account` : 

![](screenshots/45.png)

- Suivez la procédure d'inscription étape par étape, elle est assez fun ! Étape 1, entrez votre email :

![](screenshots/46.png)

- Étape 2, créez un mot de passe (**utilisez Keepass ou Keeweb pour générer un mot de passe fort et abstrait, et enregistrez-le dans votre base de données `.kdbx`**) :

![](screenshots/47.png)

- Étape 3, choisissez-vous un nom d'utilisateur : 

> ⚠️ Soyez rigoureux, c'est un identifiant définitif, vous ne pourrez pas le changer, par contre votre GitHub sera regardé par les recruteurs, votre ancienneté et votre niveau d'activités seront évalués, il faut donc faire les choses très bien du premier coup !

![](screenshots/48.png)

- Étape 4, choisissez ce que vous voulez, moi je n'aime pas me faire spamer mais chacun son truc : 

![](screenshots/49.png)

- Étape 5, prouvez que vous n'êtes pas un robot :

> Si vous êtes un robot, je ne peux rien faire de plus pour vous... 🤖

![](screenshots/50.png)

Étape 6, créez votre compte : 

![](screenshots/51.png)

- Étape 7, GitHub vous demande de vérifier votre email : 

> ⚠️ Si votre navigateur vous propose de sauvegarder vos mots de passe, répondez `JAMAIS`. Ne faites **jamais** confiance à votre navigateur pour les mots de passe : vous avez un fichier `.kdbx`, ça c'est une solution robuste, préconisée par les spécialistes ! 

![](screenshots/52.png)

- Consultez vos mails dans votre boîte de réception Codeur Online, si vous ne recevez rien, vérifiez dans vos *spams* :

![](screenshots/53.png)

- Dites que vous avez une dizaine de collaborateurs, et que vous êtes étudiant :

![](screenshots/54.png)

- Choisissez `Collaborative Coding` :

![](screenshots/55.png)

- Restez sur la version gratuite : 

![](screenshots/56.png)

- Vous arrivez sur une page GitHub avec des tutos pour apprendre à prendre l'outil en main. Libre à vous de les suivre plus tard, en attendant, cliquez en haut à droite sur l'image, et cliquer sur `Your Profile` :

![](screenshots/57.png)

- C'est votre page personnelle, c'est là qu'apparaîtront vos *repositories* et votre activité. Re-cliquez sur l'image en haut à droite, puis sur `Settings` :

![](screenshots/58.png)

- Descendez tout en bas, et cochez la case `Include private contribution on my profile`, puis `Update preferences` :

![](screenshots/59.png)

- Dans votre boîte mail Codeur Online, vous devez avoir reçu une confirmation de la création de votre compte : 

![](screenshots/60.png)


# Téléchargez & installez Git

- Rendez-vous sur la page de téléchargement de [Git](https://git-scm.com/downloads) et cliquez sur le bouton `Downloads for Windows` :

![](screenshots/61.png)

- Soyez patient. La patience est une vertu : 

![](screenshots/62.png)

- Dans Windows, dans votre dossier `Téléchargement`, exécutez le fichier `Git-2.36.1-64-bit.exe`.

![](screenshots/63.png)

- Autorisez Git à faire des modifications sur votre machine : 

![](screenshots/64.png)

- Gardez à peu près toutes les valeurs par défaut, sauf dans de rares exceptions. Par exemple, décochez l'option `Git GUI here`, vous n'en n'aurez jamais besoin, par contre cochez l'option `Check daily for Git Windows update` (c'est quand même mieux d'être à jour) : 

![](screenshots/65.png)

- Et choisissez Visual Studio Code comme éditeur par défaut : 

![](screenshots/66.png)

- Forcez l'utilisation de la branche `main` : 

![](screenshots/67.png)

- Pour le reste, vous pouvez tout laisser par défaut : 

![](screenshots/68.png)

- ⚠️ J'ai menti quand j'ai dit que Git GUI ne sert à rien, on va l'utiliser une fois ! Tapez Git GUI dans la barre de recherche de Windows 11 : 

![](screenshots/69.png)

- Cliquez sur `Help` puis sur `Show SSH Key` : 

![](screenshots/70.png)

- Cliquez sur `Generate Key` : 

![](screenshots/71.png) : 

- Laissez le champs `Passphrase` vide (il vous demande de retaper la `Passphrase`, laissez-le encore vide) : 

![](screenshots/72.png)


- Puis cliquez sur `Copy To Clipboard` : 

![](screenshots/73.png)

- Ok ! Maintenant, on va dans GitHub, dans les `Settings`:

![GitHub Settings access](screenshots/19.png)

- Dans `SSH and GPG Keys`, cliquez sur le bouton `New SSH Key` :

![Paste SSH Key](screenshots/22.png)

- Donnez un titre (par exemple l'identifiant de votre machine : c'est la fin de la clé générée) et collez votre clé : 

![Paste SSH Key](screenshots/20.png)

- Le résultat : 

![GitHub SSH Key result](screenshots/21.png)

- Pour pouvoir faire des *commits*, vous devez lancer `Git Bash` et configurer votre identité : 

![GitHub SSH Key result](screenshots/25.png)

- Tapez ces 2 lignes de commande (que vous personnalisez avec vos informations bien entendu) :  

```
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```

![GitHub SSH Key result](screenshots/74.png)

- Quand vous ferez votre premier commit, vous devrez autoriser la communication entre VSCode et GitHub :

![Allow connexion between VSCode & GitHub](screenshots/23.png)

- 🎉 C'est terminé !