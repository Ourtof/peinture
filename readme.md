# Yann EYSSERIC

Début du site de Peinture.

## Environnement de développement

### pré-requis

* PHP 831
* Composer
* Symfony CLI
* Docker
* Docker-compose

Vous pouvez vérifier les pré-requis (sauf Docker-compose) avec la commande suivante (de la CLI Symfony) : 

```bash
symfony check:requirements
``` 

### Lancer l'environnement de développement

```bash
docker-compose up -d
symfony serve -d
```