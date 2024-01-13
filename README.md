# Kit de inicio de Astro: conceptos básicos

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **¿Astronauta experimentado?** Elimina este archivo. ¡Divertirse!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Estructura del proyecto

Dentro de su proyecto Astro, verá las siguientes carpetas y archivos:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada página se expone como una ruta según su nombre de archivo.

No hay nada especial en `src/components/`, pero ahí es donde nos gusta colocar los componentes Astro/React/Vue/Svelte/Preact.

Cualquier activo estático, como imágenes, se puede colocar en el directorio `public/`.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                  | Acción                                          |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala dependencias                            |
| `npm run dev`             | inicia el servidor de desarrollo local en`localhost:4321`|
| `npm run build`           | Construya su sitio de producción para`./dist/`          |
| `npm run preview`         | Obtenga una vista previa de su compilación localmente, antes de implementarla|
| `npm run astro ...`       | Ejecute comandos CLI como `astro add`, `astro check` |
| `npm run astro -- --help` | Obtenga ayuda para usar Astro CLI                     |

## 👀 ¿Quieres saber más?

No dudes en consultar [nuestra documentación](https://docs.astro.build) o acceder a nuestro [servidor de Discord](https://astro.build/chat).
