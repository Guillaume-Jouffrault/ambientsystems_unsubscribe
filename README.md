# Projet Ambient Systems de phising

## Housna CHANA, Guillaume JOUFFRAULT, Abdoul-Aziz HASSANE, Luc NICAUD

### L'objectif de ce projet est d'envoyer un mail de phising s'apparentant à celui d'une entreprise connue (ici linkedin).

### Ce mail est anodin et relatif à l'entreprise, par exemple nous avons choisi un mail nous indiquant qu'un de nos contacts linkedin nous invite à aimer sa page.

### Le phising se situe dans le bouton se désabonner, qui redirige vers un site internet que nous avons crée.

### Pour chaque personne cliquant sur le bouton "se désabonner" depuis son mail, nous récupérons son ip, sa localisation et son mail sur la base de données firebase.

### Si la personne rentre ses logs, ceux-ci sont aussi stockées sur la bdd.

### Les mails sont envoyés automatiquement via python.

### Une IA a été conçue pour détecter si un mail s'apparente ou non à du phising.
