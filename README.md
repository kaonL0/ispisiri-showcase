# Génèse
Ce petit projet est un site vitrine pour l'association FALTAZY et plus particulièrement pour le projet d'épicerie autogérée l'UISPIRI.

Pour l'usage de la page, plusieurs objectifs :
- avoir une visibilité sur internet car plusieurs personnes "ne trouve pas" l'initiative 
- avoir une visibilité des horaires => framagenda intégré sur la page
- valoriser l'initiative et donner envie d'adhérer

Intention de partage et de pragmatisme :
- simple, efficace, sécurisé, rapide à faire avec des technologies courantes : html, css, javascript
- intégration d'un calendrier de https://framagenda.org via iframe

Il est actuellement déployé sur https://ispisiri.fr

# Droits et licence
Aucune licence, toute personne est libre d'utiliser ce code comme il lui semble bon...

# Notes sur les technologies
Ce site ne possède pas d'espace d'administration il faut connaitre les langages techniques pour le mettre à jour.

Par contre vous pouvez éditer le fichier index.html pour modifier le code sur votre propre ordinateur (pas besoin de serveur web compte tenu du choix technique).

Si vous voulez vous pencher sur le code, la documentation très bien faite est là : https://www.w3schools.com/w3css/defaulT.asp

# Comment déployer un site internet ?
1) disposer d'un nom de domaine (www.ispisiri.fr 7e/an)
2) disposer d'un hénergement (OVH ou autre, de 50 à 150€/an)
3) copier l'ensemble des fichiers sur l'hébergement
4) faire pointer le domaine sur le bon dossier et générer le certificat SSL

# Comment changer l'agenda partagé ?
1) disposer d'un compte framagenda
2) créer un agenda partagé
3) créer un cercle et associer les personnes (ou un compte générique à difuser)
3) modifier l'agenda pour associer le cercle et le rendre publique
4) récupérer le code de l'iframe de l'agenda et le mettre à jour dans le code du site