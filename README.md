# ChatGPT_Bot_Discord

-Créer une nouvelle application avec Discord Developer Portal :

        appuyez sur "New Application" et suivre les instructions


-Ajoutez un Bot dans l'onglet "Bot" :

        cliquer sur "Add Bot"


-Dans "Privileged Gateway Intents" activer la liste suivante :

        Presence Intent
        Server Members Intent
        Message Content Intent


- Dans "Bot Permissions" :
        cocher "Administrator"


-Pour ajouter le bot à votre serveur :

        dans l'onglet "OAuth2" -> "URL Generator"
        dans "Scopes" cocher "bot"
        dans "Bot Permissions" cocher les permissions voulus
        puis copiez le lien (qui se trouve tout en bas de votre page) et collez le dans votre navigateur
        pour finir, ajouter le bot dans le serveur de votre choix


-Récuperer le Token Discord :

        cliquer sur le bouton "Reset Token"


-Faire un git clone du repo :

        git clone git@github.com:Civlov50cl/ChatGPT_Bot_Discord.git
    ou
        git clone https://github.com/Civlov50cl/ChatGPT_Bot_Discord.git


-Créer un .env et ajouter vos access token pour le bot Discord et pour l'API d'OpenAI :

        export OPENAI_API_KEY="sk-..."
        export BOT_TOKEN="Le token du bot Discord"


-Installez les librairies :

        pip install -r requirements.txt

