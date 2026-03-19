## 1. Création d'un nouveau projet basic

bash command:
```
symfony new <project-name>
```

### Package permettant la réindentation des fichiers

bash command:
```
composer require cs-fixer-shim
```

### Package permettant la création l'affichage de pages

bash command:
```
composer require twig
```

### Package pour le debugging

bash command:
```
composer require debug
```

### Package serializer json

bash command:
```
composer require serializer
```

### Package Asset Mapper

bash command:
```
composer require symfony/asset-mapper
composer require symfony/asset
```

### Package Tailwind-Bundle

bash command:
```
composer require symfonycasts/tailwind-bundle
php bin/console tailwind:init
```
compile automatiquement:
```
php bin/console tailwind:build --watch
```
