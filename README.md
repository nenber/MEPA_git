In order to run the project with Docker,

*****
Step1 - Clone the project
*****
```
git clone https://github.com/nenber/MEPA_git.git

```
****
Step2 - navigate into the root of the project.
****

in the folder root, you should be able to see a Dockerfile and docker-compose.yml.
Run the command 
```
docker-compose up -d
```
and navigate to ``` http://0.0.0.0:81/ ``` in order to access the site page.



**** 
Install composer
****

If you dont have composer on your machine, type those commands in your terminal
````
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '795f976fe0ebd8b75f26a6dd68f78fd3453ce79f32ecb33e7fd087d39bfeb978342fb73ac986cd4f54edd0dc902601dc') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
````
wait for the instalation to be done, and then type 

```
composer install 

```




