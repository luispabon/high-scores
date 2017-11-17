# Pavs

Quick and dirty API to create / update / list / delete high scores.

# How to run

  * Install docker in your computer. You'll need Windows 10 pro if you're on windows. If you got something else, install `vagrant` and `virtualbox` and let me know to prepare you a way to run this.
  * Install git in your computer
  * Clone https://github.com/luispabon/high-scores 
  * Open a terminal and CD to the project folder
  * `docker-compose up -d`
  * `docker-compose exec php-fpm bin/console doctrine:schema:create`
  * Open your browser and head off to http://localhost:10000/api/scores
  
