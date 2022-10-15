# Sonarqube With Docker
Port d'écoute 9000
## Configuration de la machine hôte
Toute image utilisant ElasticSearch requiert une configuration de la machine hôte.
Cela se fait depuis un shell linux avec la ligne de commande suivante:
    **sysctl -w vm.max_map_count=262144**
Si vous utilisez Docker Desktop sous windows avec l'intégration WSL, la commande suivante permet de démarrer un shell sur la machine WSL exécutant docker à partir duquel vous pourrez appliquer la configuration:
    **wsl -d docker-desktop**