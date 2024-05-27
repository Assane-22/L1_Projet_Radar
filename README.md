# L1_Projet_Radar

# Description du Projet
Ce projet a pour objectif de développer un système de radar capable de détecter les embouteillages sur les autoroutes et d'envoyer des alertes en temps réel via WhatsApp. Le système utilisera des capteurs radar pour surveiller la circulation et un algorithme de traitement des données pour identifier les embouteillages. Les alertes seront transmises aux utilisateurs via une API WhatsApp.

# Notre but :
- Fournir des informations en temps réel.
- Avertir et éviter le désagréments des usagers.
- Impact environnemental " pollution atmosphérique"
  
# Matériaux utilisés
Notre projet est basé sur une carte Arduino, des radars, et des capteurs de luminosité.

# Partie informatique :
Nous avons utilisé Node Red avec une base de données contenant les contacts des utilisateurs pour automatiser les alertes.
On s'assurera de la récupération des données des radars avec le protocoles: MQTT.

# Traitement des Données :
- Collecte de données : Les radars collectent des données en temps réel sur la vitesse des véhicules et la densité du trafic.
- Analyse des données : Un algorithme de traitement des données analyse les informations pour détecter les ralentissements et les embouteillages.
- Détection des embouteillages : Utilisation de seuils prédéfinis pour identifier un embouteillage " vitesse moyenne inférieure à 20 km/h sur une distance de 500 mètres".

# Système d’Alerte :
- API WhatsApp : Intégration avec l'API WhatsApp Business pour envoyer des notifications.
- Configuration des alertes : Personnalisation des alertes en fonction des préférences des utilisateurs "localisation, heure de la journée".

 # Risques et Contraintes :

- Risques techniques : Problèmes liés à la précision des radars ou à l’algorithme de traitement.
- Contraintes réglementaires : Respect des normes et régulations en matière de surveillance du trafic et de protection des données.

# Conclusion
Le projet de radar de détection des embouteillages avec alerte WhatsApp représente une innovation significative pour la gestion du trafic autoroutier. En utilisant des technologies de pointe pour surveiller le trafic en temps réel et en fournissant des alertes instantanées via WhatsApp, ce système peut améliorer la fluidité de la circulation et réduire les désagréments pour les conducteurs. Une planification rigoureuse et une exécution méthodique sont essentielles pour le succès de ce projet.








  
