## Explicação

O projeto **Service Delivery** tem como objetivo apresentar as **várias maneiras** de se obter resultado utilizando o **Framework Laravel**. Resultado leia-se código 100% funcional independente de estrutura ou padrão aplicado.

Portanto será desenvolvido uma api responsável pelo gerenciamento de várias outras empresas de delivery, contando com um cadastro de usuários, empresas envolvidas, serviços e ordens de serviço.

## Instalação

O projeto **Service Delivery** tem como requerimento [Laravel](https://laravel.com/docs/9.x) v9+ para rodar normalmente.

Instale as dependencias e inicie o server.

```sh
git clone https://github.com/inventory-handler/service-delivery.git
cd service-delivery
composer install
php artisan key:generate
php artisan migrate --seed
php artisan serve
```