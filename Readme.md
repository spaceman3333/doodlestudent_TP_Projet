# TP WEB Projet (Vladislav BURAGA)

Voici le TP WEB Projet réalisé par Vladislav BURAGA. Voici ce que j'ai changé/implementé comme fonctionnalité dans le front :
- La vue initiale du calendrier affiche maintenant le mois en cours au lieu de la semaine.
- Possibilité de basculer entre les vues mois, semaine et jour dans le calendrier.
- Ajout de l'heure de fin des événements dans la vue mois du calendrier, avant il affichait uniquement l'heure de début quand on ouvrait le calendrier du mois.
- En cliquant sur un jour dans la vue du mois, vous serez redirigé vers ce jour spécifique, permettant la sélection d'une heure précise au lieu de la journée entière. La sélection de plusieurs jours couvre toute la durée de jours.
- Ajout d'un indicateur de l'heure actuelle, visible lorsque l'heure actuelle se situe entre 08:00 et 20:00.

Ci-dessous les informations récupérées du fork de projet initial.

# Remote meetings planning

This project is used in a course on the *ops* part at the [University of Rennes](https://www.univ-rennes1.fr/), France. It is a kind of doodle clone developed in so-called "native cloud" technologies in order to allow students to work on a continuous deployment chain in a containerized environment. Among the feature, the application automatically initializes a pad for the meeting and a chat room for the meeting participants.

- The [back](https://github.com/barais/doodlestudent/tree/main/api) is developed using the [quarkus.io](https://quarkus.io/) framework. 
- The [front](https://github.com/barais/doodlestudent/tree/main/front) is developed in [angular](https://angular.io/) using the [primeng](https://www.primefaces.org/primeng/)  angular UI component library and the [fullcalendar](https://fullcalendar.io/) graphical component.

A demo of the application is available [here](https://doodle.diverse-team.fr/).

Three videos (in french) are available. They present:
- the [main application feature](https://drive.google.com/file/d/1GQbdgq2CHcddTlcoHqM5Zc8Dw5o_eeLg/preview), 
- its [architecture](https://drive.google.com/file/d/1l5UAsU5_q-oshwEW6edZ4UvQjN3-tzwi/preview) 
- and a [short code review](https://drive.google.com/file/d/1jxYNfJdtd4r_pDbOthra360ei8Z17tX_/preview) .

For french native speaker that wants to follow the course. The course web page is available [here](https://hackmd.diverse-team.fr/s/SJqu5DjSD).
