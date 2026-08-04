# Agentes y flujo de trabajo del proyecto

Este proyecto está pensado para desarrollarse usando Visual Studio Code, con control de versiones en Git y ejecución de aplicaciones en Node.js.

## Herramientas principales

- Visual Studio Code: editor principal para escribir el código, revisar archivos y editar el repositorio.
- Git: control de versiones para llevar el historial de cambios, crear ramas, y hacer commits y push.
- Node.js: plataforma para ejecutar aplicaciones JavaScript y realizar pruebas locales.

## Flujo recomendado

1. Abre este repositorio en Visual Studio Code.
2. Crea o edita archivos dentro del proyecto usando el editor.
3. Usa el terminal integrado de VS Code para ejecutar comandos de Git y Node.js.
4. Guarda cambios frecuentes y haz commits con mensajes claros.

## Uso de Git

- Inicializa el repositorio si aún no lo está (solo la primera vez):
  - `git init`
- Revisa el estado actual antes de cada commit:
  - `git status`
- Agrega archivos y haz commits regulares:
  - `git add .`
  - `git commit -m "Describe el cambio"`
- Si hay un remoto configurado, empuja tus cambios:
  - `git push`

## Ejecución con Node.js

- Instala dependencias si hay un `package.json`:
  - `npm install`
- Ejecuta scripts definidos en `package.json` o archivos Node.js directamente:
  - `npm run <script>`
  - `node <archivo>.js`

## Buenas prácticas

- Trabaja en ramas para cambios importantes.
- Escribe mensajes de commit descriptivos.
- Usa el terminal integrado de VS Code para mantener todo centralizado.
- Prueba tus cambios con Node.js antes de confirmar el código.
