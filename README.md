```
ventas_flask/
├── app/
│   ├── __init__.py           # Inicialización de la aplicación Flask
│   ├── controllers.py        # Controladores de la aplicación
│   ├── models.py             # Modelos de datos
│   ├── templates/            # Plantillas HTML (vistas)
│   │   └── layout.html       # Plantilla base
│   ├── static/
│   │   ├── css/
│   │   │   └── estilos.css   # Archivos CSS
│   │   ├── js/
│   │   │   └── scripts.js    # Archivos JavaScript
│   │   └── img/              # Imágenes
├── config.py                 # Configuración de la aplicación
├── run.py                    # Punto de entrada principal
├── requirements.txt          # Dependencias del proyecto
├── .env                      # Variables de entorno
└── README.md                 # Documentación del proyecto
```
-----------------
```
ventas_flask/
├── app/
│   ├── __init__.py          # Archivo de inicialización de la aplicación Flask
│   ├── routes.py            # Rutas principales de la aplicación
│   ├── models.py            # Definición de los modelos (Base de Datos)
│   ├── forms.py             # Formularios (con WTForms)
│   ├── templates/           # Archivos HTML (vistas)
│   │   ├── layout.html      # Plantilla base
│   │   ├── index.html       # Página de inicio
│   │   └── ...              # Otras vistas (CRUD, login, etc.)
│   ├── static/              # Archivos estáticos (CSS, JS, imágenes)
│   │   ├── css/
│   │   │   └── styles.css   # Estilo personalizado
│   │   ├── js/
│   │   │   └── scripts.js   # Scripts personalizados
│   │   └── img/             # Imágenes del sistema
│   └── utils.py             # Funciones auxiliares/reutilizables
├── migrations/              # Migraciones de la base de datos (creado por Flask-Migrate)
├── tests/                   # Pruebas unitarias
│   ├── test_routes.py       # Pruebas de rutas
│   ├── test_models.py       # Pruebas de modelos
│   └── ...                  # Otros tests
├── config.py                # Configuración de la aplicación (entorno, base de datos, etc.)
├── requirements.txt         # Dependencias del proyecto (Flask, SQLAlchemy, etc.)
├── .env                     # Variables de entorno (configuración sensible)
└── run.py                   # Punto de entrada para ejecutar la aplicación
```
