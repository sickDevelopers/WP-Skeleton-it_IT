# WordPress Skeleton in Italiano

Semplice scheletro per siti Wordpress. Usalo per cominciare da zero un repository Wordpress, oppure fai un fork per applicare le tue modifiche.
Basato sul lavoro di markjaquith

## Assumptions

* WordPress as a Git submodule in `/wp/`
* Custom content directory in `/content/` (cleaner, and also because it can't be in `/wp/`)
* `wp-config.php` in the root (because it can't be in `/wp/`)
* All writable directories are symlinked to similarly named locations under `/shared/`.

