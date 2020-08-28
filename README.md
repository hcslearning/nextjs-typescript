# NextJS con Typescript 

```bash
$ npx create-next-app <nombre-de-mi-proyecto> --use-npm
```

Hasta aquí se ha configurado un proyecto normal de NextJS, para agregar el soporte para Typescript debe agregar un archivo de configuración de Typescript en blanco, a continuación el ejemplo.


```bash
$ cd <nombre-de-mi-proyecto>
$ touch tsconfig.json
```

Para que la configuración de Typescript sea autocompletada quedan los últimos pasos. Con lo que llevamos hasta el momento, intentamos ejecutar el servidor y nos solicitará instalar algunos paquetes:

```bash
$ npm run dev
# al intentar ejecutar el servidor ocurrirá un error y nos
# hará la sugerencia para instalar los sgtes paquetes
$ npm install --save-dev typescript @types/react @types/node
$ npm run dev
```

Con lo anterior, automáticamente se crearán y llenarán los siguientes archivos:

1. tsconfig.json
1. next-env.d.ts

  




