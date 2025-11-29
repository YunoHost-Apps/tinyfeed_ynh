tinyfeed est un outil CLI qui génère une page HTML statique à partir d'une collection de flux.
C'est très simple, pas de base de données, pas de fichier de configuration, juste une CLI et un peu de HTML.
Donnez-lui une liste d'URL de flux RSS, Atom ou JSON et il générera une seule page HTML pour celle-ci. Vous pouvez ensuite le configurer sans effort dans crond, systemd ou openrc et voilà, vous obtenez une page web qui agrège vos flux préférés.

### Caractéristiques

    Les flux RSS, Atom et JSON sont tous pris en charge grâce à l'excellente bibliothèque gofeed.
    Hautement personnalisable, notamment grâce à la possibilité d'utiliser des feuilles de style et des modèles externes.
    Thème sombre/clair en fonction des préférences du système.
    La page générée est légère et entièrement accessible.
    Prend en charge un mode démon pour régénérer périodiquement la sortie.
    