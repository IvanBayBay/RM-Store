# RM Store

Segundo avance del proyecto de Desarrollo de Portales Web I de la Universidad Católica de Honduras (UNICAH), III período académico de 2026. El sitio presenta a RM Store, un comercio de Tegucigalpa, Honduras, y permite consultar productos y encargos personales por WhatsApp.

## Objetivos

- Presentar las líneas de productos, los canales de contacto y la identidad visual de RM Store.
- Aplicar HTML semántico y los estilos responsivos estudiados en clase.
- Mantener el proyecto en un repositorio que permita revisar e integrar las aportaciones del equipo.

## Tecnologías

HTML5 y CSS3 externo con Flexbox, variables CSS, pseudoclases, posicionamiento, transiciones y diseño mobile first. La cuadrícula de 12 columnas usa las clases `grid`, `row`, `col-*`, `col-m-*`, `col-l-*` y `col-xl-*`, con los puntos de quiebre de clase a 768, 1025 y 1328 px. Montserrat se carga desde Google Fonts.

## Estructura

```text
RM-Store/
├── index.html
├── catalogo.html
├── encargos.html
├── nosotros.html
├── contacto.html
├── css/
│   ├── grid.css
│   └── styles.css
├── imgs/
│   ├── banners/
│   ├── branding/
│   └── productos/
├── .gitignore
└── README.md
```

## Ejecución local

Abre la carpeta del proyecto en Visual Studio Code y ejecuta `index.html` con Live Server. También puedes iniciar el servidor desde una terminal en la carpeta del proyecto.

```sh
python -m http.server 8765 --bind 127.0.0.1
```

Abre [RM Store en el servidor local](http://127.0.0.1:8765/). El sitio funciona sin un paso de compilación. Montserrat requiere conexión a Google Fonts y el sitio cuenta con una fuente alternativa.

## Estado del segundo avance

Las cinco páginas están implementadas y comparten el encabezado, la navegación y el pie. El catálogo contiene ejemplos con enlaces de consulta al WhatsApp comercial. El formulario de contacto es una demostración de interfaz con el envío deshabilitado.

Las cinco páginas se probaron en Google Chrome a 320, 390, 768, 1024, 1366 y 1920 px.

Los logotipos y las aplicaciones se extrajeron de los archivos de marca proporcionados por RM Store. Los bodegones y las fotografías de producto se generaron para ilustrar el alcance del sitio y están identificados como ejemplos.

## Pendiente de validar con RM Store

- Fotografías autorizadas de los productos reales, nombres, variantes, precios y disponibilidad.
- Enlaces oficiales de Instagram y Facebook.
- Flujo de encargos, disponibilidad de viajes y condiciones de cotización y entrega.
- Canal o servicio de recepción si se decide habilitar el formulario en una fase posterior.

## Colaboración

El propietario puede invitar a los integrantes desde la configuración de acceso del repositorio. Cada integrante trabaja en su propia rama y propone sus cambios mediante un pull request a `main`.
