<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# ACP GROUP - TESTE PRÁTICO. 
## Por Melquisedeque Bispo de Jesus.

## Documentação.pdf
### O que há no arquivo?
    - Mapa dos End Points
    - Instrução do JWT 
    - Diagrama do banco de dados.    
    - Codificação do Projeto (UTF-8)
    - Localizada na raiz do projeto no arquivo ('Documentação.pdf')

## Instruções para instalação do projeto.

## 1. Clonar o projeto.
    - 1.1 git clone
## 2. Instalar Dependências Laravel.
    - 2.1 Renomear .env.example para .env (Raiz do projeto)
    - Comando(s)
    - 2.2 composer install
    - 2.3 php artisan key:generate
    - 2.4 php artisan jwt:secret
## 3. Instalar Dependências Banco de dados (PostgresSQL).   
    - 3.1 Configurar .env com banco de dados (PostgresSQL)
    - Comando(s)
    - 3.2 php artisan migrate   
    - Popular Banco (opcional)
    - 3.3  php artisan db:seed
    - 3.31 php artisan migrate:fresh --seed
## 4. Instalar Dependências Docker.
    - 4.1 Arquivos já configurados
    - Na Pasta /dockerfiles & docker-compose.yml (Raiz do projeto)
    - Comando(s)
    - 4.2 docker compose up -d
    - Obs.: A porta 5432 para o banco PostgreSql, precisa estar livre.

### 5. Sua API esta pronta!

## 6. Bônus Adicional: Login Web (Acessando a raiz do proejto) 
![image](https://github.com/user-attachments/assets/b4c8adb5-74e2-4f2c-83b0-bc636156fe7f)


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
