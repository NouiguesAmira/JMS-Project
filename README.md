# JMS-Project
execute les commandes suivante :

  symfony new jmsProject --full
  
  cd jmsProject
  
  composer require friendsofsymfony/rest-bundle
  
  composer require sensio/framework-extra-bundle
  
  composer require symfony/validator
  
  composer require symfony/orm-pack
  
  bin/console doctrine:database:create --if-not-existe 
  
  bin/console doctrine:migrations:diff 
  
  bin/console doctrine:migrations:migrate
  
  bin/console server:start
  
 
