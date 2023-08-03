# Classic Installation WordPress via Composer
Example of using Composer for installing WordPress core in your project.  

The classic installation of WordPress core files via Composer in the root of the project, along with the project files.
This option has its advantages and disadvantages.

**Advantages:**
- All plugins are compatible with this project structure.

**Disadvantages:**
- The core files can get in the way when working with the project, as they are combined with your project files.


## Installation
- Install Composer locally or you can use docker container and run commands inside a container   
  `docker run --rm -it -v "$PWD":/usr/src/myapp -w /usr/src/myapp pimlab/composer:2.0.0-alpha3-php7.4 sh`

- Then you can run composer commands inside a container.   
Run `composer install`

---

### For more infrormation you can read articles:
[Install WordPress via Composer - EN](https://wp-yoda.com/wordpress/install-wordpress-via-composer/)  
[Install WordPress via Composer - RU](https://wp-yoda.com/wordpress/ustanovka-wordpress-cherez-composer-2/)
