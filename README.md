# Angular

Comandos Angular

1.- Para obtener la versión npm
npm -v

Para obtener la versión de Node
node -v

Para obtener la versión de Angular
ng v

Para instalar Angular CLI
npm install @angular/cli -g

Para instalar la próxima versión de Angular CLI
npm install @angular/cli@next

Para crear un nuevo proyecto en Angular
ng new nuevoproyecto

Para omitir dependencias externas al crear un nuevo proyecto
ng new nuevoproyecto --skip-install

Para ejecutar el proyecto Angular
ng serve
ng s

Para crear un nuevo componente en el Proyecto Angular
ng generate component nuevoComponente
ng g c nuevoComponente

Para evitar crear una nueva carpeta mientras crea un nuevo componente
ng generate component nuevoComponente --flat
Este comando sirve para generar un nuevo componente en angular y evitar que se cree un nuevo directorio

Para crear una construcción
ng build

Para crear una compilación para un entorno específico
ng build --dev

Para ejecutar casos de prueba
Este comando sirve para ejecutar los test de angular

Para ejecutar la prueba de un extremo a otro
ng e2e

Para cambiar el archivo de configuración angular-cli.json
ng set

Para crear una directiva en Angular
ng generate directive miDirectiva
ng g d miDirectiva

Para crear un servicio en Angular
ng generate service miServicio
ng g s miServicio

Para crear una clase
ng generate class miClase
ng g cl miClase

Para crear una interfaz
ng generate interface miInterface
ng g i miInterface

Para crear una tubería
ng generate pipe miPipe
ng g p miPipe
Este comando sirve para generar un filtro (pipe)

Para crear enum
ng generate enum enumDato
ng g e enumDato

Para crear un módulo
ng generate module miModulo
ng g m miModulo

Para crear un módulo con enrutamiento
ng generate module miModulo
ng g m miModulo

Para crear un Guard en la ruta
ng generate guard miVigilante

Para eliminar node_modules
rm -rf node_modules
Este comando sirve para eliminar la carpeta de node_modules

Para desinstalar Angular CLI
npm uninstall --save-dev @angular/cli
npm uninstall -g angular/cli @angular/cli

Para instalar la última versión de Angular CLI
npm install --save-dev @angular/cli@latest

Para actualizar Angular CLI
ng update @angular/cli
ng update @angular/core

Para limpiar la caché
npm cache clean

Para instalar la última versión de TypeScript
npm install -g typescript@latest

Para instalar la última versión de Jasmine / Karma
npm install -g jasmine@VERSION_NUMBER

Para instalar la versión específica de Karma
npm install -g karma@VERSION_NUMBER

Que es SPA?
Una Single-Page Application (SPA) es un tipo de aplicación web que ejecuta todo su contenido en una sola página.
Funciona cargando el contenido HTML, CSS y JavaScript por completo al abrir la web. Al ir pasando de una sección a otra, solo necesita cargar el contenido nuevo de forma dinámica si este lo requiere, pero no hace falta cargar la página por completo. Esto mejora los tiempos de respuesta y agiliza mucho la navegación, favoreciendo así a la experiencia de usuario.
