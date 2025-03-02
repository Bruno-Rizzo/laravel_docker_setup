### Passo a passo

Clonar os Arquivos do Laravel
```sh
git clone https://github.com/laravel/laravel.git app-laravel
```

Clonar o Repositório dentro da pasta do projeto
```sh
git clone https://github.com/Bruno-Rizzo/laravel_docker_setup.git 
```

Copiar os arquivos docker-compose.yml, Dockerfile, diretório docker/ e .env para o seu projeto


Subir os containers do projeto
```sh
docker-compose up -d
```


Acessar o container
```sh
docker-compose exec app bash
```


Instalar as dependências do projeto
```sh
composer install
```


Gerar a key do projeto Laravel
```sh
php artisan key:generate
```