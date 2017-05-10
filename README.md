# DO!Hack Docker wrapper for UserFrosting development

### Five steps to get started:

* git clone git@github.com:iGore/UserFrosting.git
* cd UserFrosting
* git submodule update --init --recursive
* cd app
* docker-compose run composer install
* cd ../build
* docker-compose run node npm install
* docker-compose up
* click [http://localhost:8570](http://localhost:8570)