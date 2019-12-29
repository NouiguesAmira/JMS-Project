# JMS-Project
jms
  symfony new jmsProject --full
  cd jmsProject
  composer require friendsofsymfony/rest-bundle
  composer require sensio/framework-extra-bundle
  composer require symfony/validator
  composer require symfony/form
  composer require symfony/orm-pack
  code .
  bin/console doctrine:database:create --if-not-existe 
  bin/console server:start
  bin/console make:entity 
  bin/console make:entity 
  bin/console m:m
  bin/console doctrine:migrations:migrate
  bin/console debug:config 
  bin/console make:Form
  bin/console make:Form
  bin/console doctrine:migrations:diff 
  bin/console doctrine:migrations:migrate
  bin/console doctrine:schema:update --dump-sql --force
  mysql -u root -p
  composer require friendsofsymfony/rest-bundle "^2.1"
  php bin/console debug:router
 
