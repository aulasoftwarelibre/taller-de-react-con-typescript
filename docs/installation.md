# Instalación

## Requisitos para el taller

Es necesario tener un equipo con el siguiente software:

* Node >= 8.0
* Visual Studio Code
* Yarn
* Git

## Instalación

Debido a la variedad de distribuciones disponibles, se indicará exclusivamente la URL de la documentación de cada software y las instrucciones para instalación con **snap**. Las siguientes distribuciones son compatibles con **snap**: Ubuntu >= 16.04, todas las variantes de Ubuntu excepto Lubuntu, Solus >= 3, Zorin OS.

Puedes instalar **snap** en otras distribuciones [siguiendo las instrucciones](https://snapcraft.io/docs/installing-snapd) de la web oficial.

### Node 

Se recomienda usar _node_ versión 8 o superior. Puedes [descargarlo de la web oficial](https://nodejs.org/es/download/). Sin embargo, si usas _snap_ puedes instalarlo directamente ejecutando la siguiente orden en tu terminal:

    sudo snap install node --classic --channel=8

El paquete de _snap_ ya incluye _yarn_, por lo que si lo usas, puedes saltarte el siguiente paso.

### Yarn

_Yarn_ es opcional, ya que _node_ trae su propio gestor de dependencias: _npm_. Sin embargo se recomienda usar _yarn_, que es bastante más rápido que el anterior.

Si no vas a usar _snap_ puedes instalar yarn [siguiendo las instrucciones](https://yarnpkg.com/en/docs/install) de la web oficial.

### Visual Studio Code

De nuevo, si usas _snap_, instalar la aplicación es tan fácil como ejecutar lo siguiente en tu terminal:

    sudo snap install code --classic

De lo contrario, [descargarlo de la web oficial](https://code.visualstudio.com/Download/).

### Git

Git se puede instalar fácilmente usando el gestor de paquetes de tu distribución. Puedes encontrar instrucciones de instalación en nuestro [tutorial de Git](https://aulasoftwarelibre.github.io/taller-de-git/git/).