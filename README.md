Scripting en DaVinci Resolve (probando con la beta 17)

Información dentro de Resolve en "Help > Documentation > Developer". En esa carpeta, consultar "Scripting > README.txt". Hay unos cuantos scripts con código de ejemplo.


NOTAS: He instalado Python 2.7 en C:\Python27

setup.bat - Establece las variables de entorno para poder usar el API python de DaVinci Resolve (aunque no llega con esas, por lo visto)
python_console.bat - Llama a setup.bat y abre una consola python 2.7

python_setup.py - Configura el entorno en python para acceder al API de DaVinci Resolve

resolve_test.py - Pruebas de uso del API (sandbox, prescindible)

NOTA: La versión gratuita de Resolve no permite la ejecución de scripts desde fuera del programa.
Se pueden ejecutar dentro de la consola del programa (Workspace > Console)

También se pueden copiar a %appdata%\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts\Comp (que en mi caso viene siendo C:\Users\jtaibo\AppData\Roaming\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts\Comp) y entonces los scripts estarán accesibles desde el menú en Workspace > Scripts > ...
(dejo acceso directo en "DaVinci Installed Scripts")

Realmente los scripts no van en Comp, van dentro de Scripts clasificados en "Comp", "Edit", "Color" y "Deliver". Según el menú en que estemos en Resolve nos aparecen los scripts correspondientes en un primer nivel y los demás en submenús con el nombre correspondiente.
