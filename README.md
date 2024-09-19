Este es un [Next.js](https://nextjs.org) Proyecto iniciado con [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Descripción del Proyecyo

El sitio web es una aplicación de documentación en línea, tiene un diseño minimalista y moderno, con un esquema de colores predominante azul y blanco. La tipografía es clara y fácil de leer, y la navegación es intuitiva y fácil de usar. La experiencia del usuario es generalmente positiva, con una carga rápida de las páginas y una respuesta rápida a las interacciones del usuario.

## Caracteristicas

- El sitio web ofrece una función de autenticación para acceder a las funciones de edición y colaboración.
- La función de autorización permite controlar quién puede acceder y editar los documentos.
- La sección "Collaborators" permite agregar colaboradores a un documento, lo que permite la edición simultánea y la colaboración en tiempo real.
- La función de comentarios permite dejar comentarios y discusiones en los documentos.
- La sección "Edit" permite editar documentos en línea, con soporte para formato Markdown y syntax highlighting.
- La función de edición ofrece una vista previa en tiempo real del documento, lo que permite ver los cambios antes de guardarlos.

## Tecnologías utilizadas

- [`Vercel`](https://vercel.com) para la implementación y el despliegue del sitio web.
- [`Next.js`](https://nextjs.org/) para la construcción del sitio web.
- [`Tailwind`](https://tailwindcss.com) para el diseño del sitio web.
- [`Shadcn/ui`](https://ui.shadcn.com) para la estructura del sitio web.
- [`Liveblocks`](liveblocks.io) para la creación de Documentos.
- [`Clerk`](clerk.com) para la gestion del sign-in/sign-up.

## Primeros pasos

Primero, ejecute el servidor de desarrollo:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Abra [http://localhost:3000](http://localhost:3000) con su navegador para ver el resultado.

Puedes comenzar a editar la página modificando `app/page.tsx`. La página se actualiza automáticamente a medida que editas el archivo.

Este proyecto utiliza [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) para optimizar y cargar automáticamente [Geist](https://vercel.com/font), una nueva familia de fuentes para Vercel.

## Más información

Para obtener más información sobre Next.js, consulte los siguientes recursos:

- [Documentación de Next.js](https://nextjs.org/docs): conozca las características y la API de Next.js.
- [Aprenda Next.js](https://nextjs.org/learn): un tutorial interactivo de Next.js.

Puedes consultar [el repositorio de GitHub de Next.js](https://github.com/vercel/next.js). ¡Tus comentarios y contribuciones son bienvenidos!

## Implementar en Vercel

La forma más sencilla de implementar su aplicación Next.js es usar la [Plataforma Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) de los creadores de Next.js.

Consulte nuestra [Documentación de implementación de Next.js](https://nextjs.org/docs/app/building-your-application/deploying) para obtener más detalles.
