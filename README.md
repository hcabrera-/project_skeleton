#project_skeleton
Template para nuevos proyectos de Python. Provee una jerarquia de archivos con lo minimo necesario para inciar un nuevo proyecto de python, reduciendo la friccion al iniciar un nuevo proyecto. Solo clonar, renombrar y empezar a escribir codigo. 

.
├── docs
│   ├── conf.py
│   └── index.md
├── LICENSE
├── NAME
│   ├── __init__.py
│   └── NAME.py
├── README.md
├── requirements.txt
├── setup.py
└── tests
    ├── __init__.py
    └── test_basic.py

##Contenido de Repo

###docs
Documentacion del proyecto. Un documento con instrucciones de como ejecutar/importar el codigo es un buen punto de inicio para cualquier documentacion.

###LICENSE
Como deseas liberar tu codigo? permitir que otras personas lo utilicen libremente? los usuarios pueden modificar tu codigo y redistribuirlo?. Si no estas seguro cual es la licencia apropiada para tu proyecto puedes consultar choosealicense.com.

###NAME
El folder donde recide los archivos fuente del proyecto. Para personalizar este template se debe de renombrar todas las instancias de 'NAME' con el nombre del proyecto, incluyendo este directorio.

###README.md
Este archivo! Una descripcion sobre el objetivo del proyeto.

###requirements.txt
Archivo de instalacion de dependencias de pip. Este archivo se utiliza junto con [pip](https://pypi.python.org/pypi/pip) para instalar todas las dependencias de manera automatica.

###setup.py
Script de [instalacion](https://docs.python.org/3/distutils/setupscript.html). Archivo para empaquetado y distribucion del codigo.

###tests
Suite de pruebas para el proyecto.

##Referencia
Basic project structure for python projects
http://docs.python-guide.org/en/latest/writing/structure/
