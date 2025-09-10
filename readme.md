# Générateur de signature pour e-mail

Ce projet a pour utilité, comme son nom l'indique, de générer votre propre signature à insérer dans vos e-mails.

## Comment faire ?

- Recupérer le projet et l'ouvrir avec VSCode.

- Utiliser l'extension Live Server et activer "Go Live!".

- Une fois le projet ouvert sur le navigateur grâce à l'extension, renseigner ses coordonnées.

- Générer le code HTML, ou la signature en riche.

- Sur votre boîte mail ( GMAIL, OUTLOOK, etc.), insérer la signature dans le paramètre correspondant, afin qu'elle s'ajoute automatiquement à la fin de chaque mail expédié.


## Signature - site statique
Local:
docker build -t maracorp-signature:dev
docker run --rm -p 8081:80 maracorp-signature:dev
## http://localhost:8081
.