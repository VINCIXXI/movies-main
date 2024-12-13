# Proyecto de Renta de Películas

Este proyecto es un sitio web de renta de películas diseñado para administradores. Permite agregar usuarios y películas, así como gestionar una lista de películas favoritas.

## Tecnologías Utilizadas

- **React**: Biblioteca de JavaScript para construir interfaces de usuario.
- **TypeScript**: Superconjunto de JavaScript que añade tipado estático opcional.
- **React Router**: Biblioteca para manejar el enrutamiento en aplicaciones React.
- **Axios**: Biblioteca para realizar solicitudes HTTP desde el navegador.
- **CSS**: Hojas de estilo en cascada para dar estilo a los componentes y la interfaz de usuario.
- **@testing-library/react**: Biblioteca para probar componentes React.
- **@types**: Paquetes de definiciones de tipos para bibliotecas de JavaScript.

## Componentes del Proyecto

### Componentes Principales

- **Navbar**: Barra de navegación que contiene enlaces a diferentes rutas de la aplicación, como "Home", "Add Movie", "Favorite Movies", "Users" y "Register Users". También incluye un logo.
- **MovieCard**: Componente que muestra la información de una película individual y permite agregarla a favoritos.
- **AddMovie**: Componente que contiene un formulario para agregar una nueva película. Utiliza `useState` para manejar el estado del formulario y `axios` para enviar una solicitud POST al servidor.
- **Favorites**: Componente que muestra una lista de películas favoritas. Permite eliminar películas de la lista de favoritos.
- **Home**: Ruta principal que muestra una lista de películas o una página de bienvenida.
- **Users**: Componente que muestra una lista de usuarios.
- **RegisterUsers**: Componente que contiene un formulario para registrar nuevos usuarios.

### Hooks Personalizados

- **useFetchMovies**: Hook personalizado que se utiliza para obtener datos de películas desde una API.

## Estructura del Proyecto

```plaintext
src/
├── assets/
│   └── logo.png
├── components/
│   ├── Navbar.tsx
│   ├── MovieCard.tsx
├── hooks/
│   └── useFetchMovies.ts
├── pages/
│   ├── AddMovie.tsx
│   ├── Favorites.tsx
│   ├── Home.tsx
│   ├── Users.tsx
│   └── RegisterUsers.tsx
├── App.tsx
├── index.tsx
└── reportWebVitals.ts



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
