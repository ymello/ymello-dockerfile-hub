# Intercase Dockerfiles

[Docker](http://docker.com) containers to use Intercase's products.


## Usage

### Install

Build `intercase/php7-fpm` from source:

    git clone https://git.intercase.net.br/docker/dockerfiles.git
    cd php7-fpm/
    docker build -t intercase/php7-fpm .

### Run

Run the image, binding associated ports, and mounting the present working
directory:

    docker run -p :9000 intercase/php7-fpm bash

Append the PHP-FPM command to the end of your `docker run` command. The above
example uses `bash`.


## Services

Service     | Port  
------------|------
PHP7-FPM    | 9000