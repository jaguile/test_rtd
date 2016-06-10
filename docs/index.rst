.. test documentation master file, created by
   sphinx-quickstart on Sat Feb 27 08:48:18 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. toctree::
   :maxdepth: 2

   jaguile-demo

Apunts d'Apache
===============

.. subtitulo: lleva un sbrayado diferente

Instal·lació del paquet apache
------------------------------

.. TODO PARAGRAFO: como en latex, van separados por una linea en 
    blanco

Hola esto es un paragrafo. Para instalar apache desde los repositorios simplemente hay que ejecutar este comando desde terminal:


$ sudo apt-get install apache2

::

    if x == "abc":
        echo "xyz"
    $ sudo apt-get install apache2

Ahora estoy en otro parrafo.

Y ahora es otro parrafo el que estoy escribiendo aqui.

Esto es otro paragrafo. El último, vale, ya he acabado.

Configuració d'apache2
----------------------

Fitxer de configuració principal
................................

Bueno aqui pongo todo sobre el fichero *apache2.conf*.

Fitxer de configuració de ports
...............................

Y aquí, es evidente, pongo lo principal a explicar sobre el fichero *ports.conf*. Ahora veremos cómo poner texto con enfasis. Principales ficheros de configuración:

.. emphasis con *aqui va el texto*
    strong emphasis va con **aqui va el texto**

Aqui la direcitva principal es **Listen**

Principals directives
---------------------

Tota la documentacio sobre qualsevol directiva es pot trobar en la `pàgina de referència de directives d’apache <https://httpd.apache.org/docs/2.4/>`. Per entendre les directives a apache  ́es important saber en quins contex-tos es poden utilitzar. Hi han els següents:

Context
.......

**Server config** esto quiere decir que es un parámetro directo de un fiechero como apache2.conf, listen.conf.

Taules de directives
....................

=========           =======         ==========
Directiva           context         descripció
=========           =======         ==========
*AllowOverride*     directory       Quines directives podem posar en 
                                    el fitxer *.htaccess*. Per defecte
                                    el seu valor és **none**
DirectoryIndex      server config,  Diu què mostrar quan l'usuari 
                    virtualhost     demana una url.

Apache com a proxy
------------------

Ahora voy a probar una lista.

* *mod_proxy* item 1
* *mod_proxy_balancer* item 2
* *mod_proxy_cache* item 3

Listaas enumeradas

1. item 1
2. item 2
   wekjfklej
3. item 3
