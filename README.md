# Hospital

**Hospital** es un sitio web diseñado para que los pacientes puedan conocer a los profesionales de la salud, así como obtener información sobre su ubicación en caso de emergencias.

## Instrucciones para Visualizar el Proyecto

1. Clona el repositorio:

``` bash
git clone git@github.com:valeriatorrealba/Hospital.git
``` 
2. Abre el proyecto en Visual Studio Code.
3. Inicia Live server (si no lo tienes lo puedes instalar)
4. Accede al index.html en tu navegador desde la carpeta v1 para ver la primera versión

``` bash
http://127.0.0.1:5500/v1/index.html
``` 
5. Accede al index.html en tu navegador desde la carpeta v2 para ver la segunda versión

``` bash
http://127.0.0.1:5500/v2/index.html
``` 

## Estructura de carpetas y archivos
``` bash
Hospital/
│
├── assets/
│   ├── css/
│   │   ├── main.css 
│   │   └── main.css.map
│   ├── img/
│   │   ├── favicon.png  
│   │   ├── logo.png
│   │   └── paciente1.jpg
│   │
│   ├── js/
│   │   └── script.js    
│   │
│   ├── screenshot/
│   │   └──     
│   │
│   └── Sass/
│       ├── abstrats/   
│       │   └── _variables.scss
│       ├── base/   
│       │   └── _normalize.scss
│       ├── components/   
│       │   └── _buttons.scss
│       ├── layout/   
│       │   ├── _footer.scss
│       │   └── _header.scss
│       ├── pages/   
│       │   ├── _contact.scss
│       │   ├── _home.scss
│       │   └── _medicalEquipment.scss
│       ├── themes/   
│       │   └── _default.scss
│       ├── vendors/ 
│       │   └──  
│       └──  main.scss   
│
├── index.html                
├── equipo-medico.html            
├── contacto.html 
├── package-lock.json
├── package.json
├── README.md 
├── LICENSE
└── .gitignore
```
## Estructura del Proyecto

- **Home** La página principal del sitio proporciona una introducción y visión general de los servicios ofrecidos. Está diseñada para captar la atención de los usuarios y guiarlos hacia información adicional sobre el equipo médico y formas de contacto. También puede incluir secciones destacadas como testimonios, especialidades o servicios médicos.
- **Equipo médico** Esta página muestra detalles sobre el equipo médico, incluyendo perfiles de los profesionales de salud, sus especialidades. Facilita a los usuarios conocer al equipo, generando confianza y transparencia sobre quiénes brindan los servicios.
- **Contacto** La página de contacto permite a los usuarios comunicarse con el equipo mediante un formulario sencillo. Incluye campos básicos como nombre, correo electrónico, mensaje y un botón para enviar la información. El formulario es ideal para consultas generales, solicitudes de información o preguntas sobre los servicios ofrecidos.

## Tecnologías Usadas
- **HTML5**
- **CSS3**
- **SASS**

## Modularización de Estilos y Media Queries

Para facilitar el mantenimiento del proyecto, los estilos CSS se modularizaron en archivos parciales usando SASS. Esto permite mantener cada sección (como el header, el footer, y las páginas específicas) en archivos separados, haciéndolo más organizado y eficiente. Las media queries se colocaron en cada archivo parcial correspondiente, de modo que los ajustes de diseño específicos de cada componente se aplican únicamente donde se necesitan.

## Estructura de SASS

La estructura de archivos SASS fue organizada de la siguiente manera:

- main.scss: Archivo principal que importa todos los parciales.
- _variables.scss: Contiene las variables globales como colores, facilitando su modificación en un solo lugar.
- _header.scss, _footer.scss, _main.scss: Cada sección principal de la página tiene su propio archivo parcial, donde se definen sus estilos específicos.

## Creditos
- Logo [Pngwing](https://www.pngwing.com/)
- Imágenes [Unsplash](https://unsplash.com/)
- Iconos [Fontawesome](https://fontawesome.com/)

## Autor
Desarrollado por Valeria Torrealba.