# symfonyweapp
Siple symfony 6 webapp

 symfony new webappcrud –webapp
[OK] Your project is now ready in /home/josemo/Symfony/webap

Data base 
php bin/console doctrine:database:create
Entity
php bin/console make:entity Agenda
name;  adress; phoneNumber

Migration
bin/console make:migration
bin/console doctrine:migration:migrate
[OK] Successfully migrated to version : DoctrineMigrations\Version20231012133847

Controller
php bin/console make:crud

symfony server:start
