Esto es solo una prueba

## Modulo 0

## Práctica 1.8 - Navegación en terminal

- `pwd`: saber en qué directorio estoy.
- `ls`: ver los archivos y carpetas del directorio actual.
- `cd nombre`: entrar a una carpeta.
- `cd ..`: volver a la carpeta anterior.
- `mkdir nombre`: crear una carpeta.
- `npm start`: iniciar la aplicación para poder verla en el navegador.

## Práctica 1.9 - Instalar y verificar la línea base

Instalé Node.js 24.15.0 y luego verifiqué la versión de npm. Yo tenía una versión anterior de Angular CLI, así que la actualicé a la versión 22.1.4. Después volví a comprobar todas las versiones para asegurarme de que quedaron correctas.

También aprendí que Node.js trae npm incluido, que Angular CLI se instala usando npm y que el orden importa: primero se instala Node y después Angular CLI.

## Unidad 3 Del modulo 0 

## Leccion 1.11 - Crear el workspace

Ejecute este comando ' ng new panel-actividades --routing --style=css --skip-git --package-manager=npm --ssr=false --defaults '  me creo carpetas y paquetes necesarios en el proyecto . en la leccion los mas relevantes fueron:

panel-actividades/
├── package.json        ← qué necesita el proyecto y qué comandos tiene
├── package-lock.json   ← las versiones exactas que se instalaron
├── angular.json        ← cómo se compila y se sirve
└── src/
    └── app/
        ├── app.html    ← lo que se ve
        ├── app.css     ← cómo se ve
        └── app.ts      ← qué hace