This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Historial de versiones

### [0.0.0] - 2024-05-26
### Añadido
- Creacion del proyecto

### [0.0.1] - 2024-05-26
### Añadido
- Se creo el esqueleto mediante tres contenedores de la pagina principal

### [0.0.2] - 2024-05-26
### Añadido
- Se implemento casi por completo la barra de categorias
- Funciona en su totalidad la busqueda por categorias 
- Aun no muestra todos los productos filtrados en pantalla
- Muestra los productos filtrados en consola

### [0.0.3] - 2024-05-26
### Añadido
- Se implemento por completo la barra de categorias
- Muestra completamente los productos filtrados en la pantalla y en su seccion 
- Muestra imagenes de los productos
- Muestra en que seccion esta actualmente

### [0.0.4] - 2024-05-27
### Añadido
- Muestra cuando el pedido esta vacio
- El boton de agregar es funcional
- Se ordenaron los componentes de cliente y servidor para evitar cargas inecesarias 
- Se muestra en forma de tarjetas los productos pedidos
- Se evitan los duplicados de productos en la seccion pedidos (tarjetas duplicadas)
- Se agregaron funcionalidades a los botones de agregar productos + - y el boton eliminar x
- Se calcula el total de una compra
- Se agrega limites en los botones + y -

### [0.0.5] - 2024-05-27
### Añadido
- Se creo el modelo de ordenes 
- Se agrego el boton para poder confirmar pedido
- Se agrego la funcion de agregar nombre al pedido
- Se establecio valores de validacion al momento de ingresar un nombre
- Se ingresa datos de ordenes en la base de datos

### [0.1.0] - 2024-05-28
### Añadido
- Creacion de las primeras funciones de administrador 
- Asignacion de un logo dinamico
- Se creo la pagina principal de administrador junto con su navegacion
- Se obtienen y muestran las ordenes pendientes
- Se puede marcar las ordenes completas

### [0.1.1] - 2024-05-29
### Añadido
- Se listo los productos 
- Se creo un paginador 
- Se puede ver el total de paginas disponibles
- Se añadio un buscador 
- Se muestran resultados al momento de utilizar el buscador

### [0.1.2] - 2024-05-30
### Añadido
- Se creo un formulario para crear productos 
- Se asigno una validacion para la creacion de productos 
- Se permite subir imagenes 
- Se guardan los nuevos productos en la base de datos

### [0.1.3] - 2024-05-30
### Añadido
- Se agrego la funcion para obtener un producto para editar
- Validacion de imagenes
- Guardado de cambios

### [0.1.3] - 2024-05-30
### Añadido
- Creacion de un Endpoint para api
- Configuracion de swr