# À vérifier avant chaque checkpoint

Vérifiez ces points avant chaque checkpoint :

- [ ] **Dépôt à jour** : le firmware, l'interface et la documentation sont poussés sur GitHub, pas seulement sur le Raspberry Pi. Une démo réussie ne remplace pas la remise.
- [ ] **Topic d'alarme conforme** : `hydro-limoilou/{site-id}/alarm/{type}`, au singulier, avec les champs exigés par le contrat.
- [ ] **QoS justifiés** : QoS 0 pour la télémétrie, QoS 1 ou plus pour les alarmes et les boutons, avec la justification dans la documentation.
- [ ] **Redondance démontrée** : la coupure de la voie principale et la reprise sont testées, pas seulement décrites.
- [ ] **PCB complet** : routage 2 couches, DRC sans erreur, Gerbers et BOM dans le dépôt. Le schéma KiCad se valide dès le CP2.
