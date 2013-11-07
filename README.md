# WordPress Skeleton in Italiano

Semplice scheletro per siti Wordpress. Usalo per cominciare da zero un repository Wordpress, oppure fai un fork per applicare le tue modifiche.
Basato sul lavoro di markjaquith

## Assunzioni

* Wordpress installato come submodule nella sottocartella '/wp'
* Contenuto custom nella cartella '/content' più chiaro e meno possibilità di errore.
* `wp-config.php` nella root (non può essere in wp)
* Tutte le cartelle con permessi di scrittura sono symlinked alle corrispettive cartelle in '/shared/content'

## Plugin

Durante la mia esperienza di sviluppo ho scoperto alcuni plugin che mi porto dietro ad ogni progetto e per questo ho deciso di inserire come must-use. Questi plugin sono ssh-sftp-updater-support (plugin per il supporto upload via ssh) e super-cpt (Super Custom Post Type, plugin per facilitare la creazione di custom post). 

Accetto consigli per l'aggiunta di plugin must-use, l'unico vincolo è che siano utili in fase di sviluppo e non vadano a modificare in nessun modo la resa finale del tema (ad esempio: non verrà presa in considerazione la proposta di un plugin per inserire un widget nella sidebar, per quanto ustile possa essere).

## Tema HTML5 Boilerplate + Foundation

Tra i temi presenti di default nella cartella cotent/themes è presente un tema scheletro basato su HTML5 boilerplate e Foundation CSS, con supporto scss.

## Modifiche

* Cercherò di mantenere il più possibile aggironato WP all'ultimo commit stabile, se per caso dovessi dimenticarmene vi prego di contattarmi e farmelo notare

