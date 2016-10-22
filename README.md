# drupal-console-es
DrupalConsole Spanish Language / en Español

# Version en Español

## Uso

El proyecto Drupal console se instala por cada sitio web de Drupal 8 con el lenguaje Inglés por defecto.
Para instalar el paquete de Drupal Console en Español se deben ejecutar las siguientes instrucciones

```
$ composer require drupal/console-es
```

### Instalar Drupal Console

Para instalar la versión adecuada del proyecto Drupal console para su instalación de Drupal, ejecute el siguiente comando de composer

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Instalar Drupal Console launcher

Con el fin de evitar conflictos entre las diferentes versiones de  Drupal y tener una versión de Drupal Console entre versiones mayores y menores en Drupal, se ha creado un Drupal Console Launcher para facilitar la carga de la consola de comandos de Drupal a disposición de cada Drupal 8 página web
 
Siguiendo estas instrucciones se puede instalar globalmente el Drupal Console Launcher.
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribuir

Si quiere contribuir a esta traducción, es necesario seguir los siguientes pasos

- Hacer un fork de este repositorio.
- Clonar tu repositorio forkeado en tu ambiente local.
- Configurar un repositorio de upstream.

A fin de estar al día con otras contribuciónes se debe configurar una conexión con el repositorio principal mediante el siguiente comando git

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-fr.git
```

Para obtener las ultimas contribuciónes antes de empezar, se deben ejecutar los siguientes comandos

```
$ git fetch upstream
$ git merge upstream/master
```

Nótese bien: actualice su copia y ENVÍE sus cambios cada día a su repositorio forkeado si quiere hacer un Pull Request para evitar conflictos con otros colaboradores.

# English Version

Check instructions at [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)
