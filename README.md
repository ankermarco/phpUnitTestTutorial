# phpUnitTestTutorial

## Run composer directly from docker <br/>
https://hub.docker.com/r/composer/composer/

docker run --rm -v $(pwd):/app composer/composer update

Run php directly from docker
docker run -it --rm --name my-running-script -v "$PWD":/usr/src/myapp -w /usr/src/myapp php:5.6-cli vendor/bin/phpunit
