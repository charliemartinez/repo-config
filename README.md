# repo-config
Autor: Charlie Martínez ®
## Acerca de este repositorio
Gestor gráfico que permite activar y desactivar los repositorios non-free, contrib y backports en Debian Buster.
## Detalles adicionales
Este instalador modifica el archivo /etc/apt/sources.list creando /etc/apt/sources.list.d/debian.list con repositorios oficiales libres de Debian (sin backports). El programa repo-config permite elegir si activar non-free contrib y backports o sólo backports, de una manera sencilla por medio de una interfáz gráfica rudimentaria (zenity)
### Compatibilidad
Desarrollado para Quirinux GNU/Linux 2.0 este programa sólo es compatible con Debian Buster. Para utilizarse con Ubuntu o Devuan, sería necesario modificar el código fuente de los archivos .list
### Instrucciones
sudo dpkg -b repo-config-1.0-q2_amd64
sudo dpkg -i repo-config-1.0-q2_amd64-deb
repo-config
#### Autores
Charlie Martínez, haciendo uso de la libertad de distribución de la licencia GPL, ha programado este instalador gráfico pero no guarda relación con el desarrollo del software que instala (OpenToonz) ni con sus autores (Digital Video S.p.A.). Este instalador está liberado también bajo licencia GPLv3. 
#### Avisos legales
(p) y (c) 2020. Charlie Martínez y Quirinux son marcas registradas. Todo el software aquí publicado está protegido por Derechos de Autor y registrada en DNDA y se distribuye bajo licencia <a href="https://lslspanish.github.io/translation_GPLv3_to_spanish/">GPLv3</a>, mientras que todo el contenido artistico que acompaña al software (íconos, wallpapers, etc) y el literario (manuales y textos en general) es distribuido bajo licencia <a href="https://creativecommons.org/licenses/by/4.0/deed.es">Creative Commons Reconocimiento 4.0 Internacional</a>. Digital Video S.p.A., Windows, Mac, GitHub, Debian, TupiTube, OpenToonz, Linux, GNU, Ardour y otras son marcas registradas por sus respectivo dueños.
## Licencia GPLv2.0
Puedes copiar y distribuir este material en cualquier medio y formato, remezclar, transformar y contruir nuevo material a partir del mismo para cualquier propósito, incluso comercialmente. Es necesario que indiques el nombre del autor original en los créditos, de manera adecuada y brindes un enlace a la licencia, indicando si se han realizado cambios. Puedes hacerlo en cualquier forma razonable, pero no de forma en que parezca que tu o que la implementación de este software cuenta con apoyo del licenciante. No puedes aplicar términos legales ni medidas tecnológicas que restrinjan legalmente a otras a hacer cualquier uso permitido por la licencia. 
#### Renuncias
Este repositorio de GitHub no es un respaldo a GitHub por parte de Charlie Martínez ni de Quirinux. Quirinux no mantiene ni distribuye el código base del motor de GitHub porque no está disponible bajo una licencia de código abierto y libre.
El autor de Quirinux no forma parte del equipo de desarrollo de Debian y Quirinux no es una distribución oficial de Debian, sino una derivada construida en base a ella, sin relación colaborativa alguna. 
El autor de Quirinux participa como usuario de pruebas y aporta sugerencias en proyectos como el fork de Systemback de Franco Conidi, OpenToonz y TupiTube, aplicaciones incluidas por defecto en Quirinux, sin embargo no forma parte del equipo de desarrollo de tales aplicaciones ni de ninguna otra salvo las que se indiquen específicamente en los repositorios.

