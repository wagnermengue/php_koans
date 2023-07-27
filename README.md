# PHP Koans

Projeto baseado no original https://github.com/akoebbe/php_koans

O que foi adaptado?

Removido arquivo php contempate_koans pois era muito grande e de difícil manutenção.
Logo foi necessário adicionar algumas dependências pois, sem ele precisamos do composer.

Assim adicionei um `docker-compose.yaml`, adaptei o `Dockerfile` e adicionei um `entrypoint`.

Agora para rodar os desafios você deve:

`docker-compose up -d`

`docker-composer exec php-koans bash`

`./vendor/bin/phpunit -c phpunit.xml`


# PHP Koans

Project based on the original https://github.com/akoebbe/php_koans

What has been adapted?

Removed the php contempate_koans file because it was too large and difficult to maintain. Consequently, some dependencies were added, since without it, we need Composer.

Therefore, a `docker-compose.yaml` file was added, the `Dockerfile` was adapted, and an `entrypoint` was added.

Now, to run the challenges, you should:

`docker-compose up -d`

`docker-composer exec php-koans bash`

`./vendor/bin/phpunit -c phpunit.xml`
