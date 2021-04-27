# PHP FPM over Apache2

This is a docker-compose setup giving a setup to run PHP websites over
FastCGI Process Manager. The project is served using the httpd docker
image.

## Usage

If needed, PHP and Apache versions may be changed in the corresponding
Dockerfile. Apache and PHP configuration should work out of the box.
Both can be modified in the files inside the subfolders.

The website served should be placed inside the _html_ folder. And is
exposed to localhost on port _8080_

## License

This project is distributed under the MIT license (see LICENSE.md)
