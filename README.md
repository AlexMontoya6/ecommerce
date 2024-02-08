# ecommerce

## Instalación

clonar el proyecto

```bash
git clone https://github.com/AlexMontoya6/ecommerce.git

```

levantar los contenedores

alias dcr="docker-compose up -d nginx mysql workspace phpmyadmin"

```bash
docker-compose up -d nginx mysql workspace phpmyadmin
```

entrar en el contenedor workspace

alias dcw="docker-compose exec --user=laradock workspace bash"

```bash
docker-compose exec --user=laradock workspace bash
```

copiar el .env.example a .env

```bash
cp .env.example .env
```

ejecutar composer update/install

```bash
composer update
```

crear enlace simbolico

```bash
art storage:link
```

ejecutar las migraciones y los seeders

```bash
art migrate --seed
```
