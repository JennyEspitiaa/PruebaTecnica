# π€οΈββ Gnomai App

**Gnomai app es un aplicativo que permite ver el estado del clima actual por ciudad que el usuario ingrese. AsΓ­ entonces el usuario serΓ‘ capaz de 
ver la fecha actual, el clima en Β°C, sensaciΓ³n tΓ©rmica, temperatura maxima, temperatura minima, entre otras. TambiΓ©n podra ver el pronostico por horas y de los proximos dΓ­as. 

AdemΓ‘s el usuario podrΓ‘ ingresar sesiΓ³n por medio de correo y contraseΓ±a o autenticaciΓ³n de Gmail, una vez loggeado serΓ‘ capaz de hacer comentarios para publicar en la pagina principal de Gnomai app.
**

## πβ Estructura de carpetas

``````

ββββπ public/
β   ββββπ index.html
|
ββββπ src/
β   ββββπ components/
β   β   ββββπ
β   β    ββββπ Create.jsx
    |     ββββπ Edit.jsx
    |    ββββπ Footer.jsx
    |    ββββπ FormBar.jsx
    |    ββββπ Gallery.jsx
    |    ββββπ Home.jsx
    |    ββββπ Login.jsx
        ββββπ Navbar.jsx
    |    ββββπ Register.jsx
    |    ββββπ Weather.jsx
β   ββββπ Firebase/
β   β   ββββπ rifebaseConfig.js
|
β   ββββπ redux/
         ββββπ actions
β   β     ββββπ actionRegister.js
          |βββπ actionFotos.js
         ββββπ reducers
β   β    ββββπ registerReducers.js
         ββββπ fotoReducers.js
         ββββπ store
β   β    ββββπ store.js
         ββββπ types
β   β    ββββπ types.js
β    ββββπroutes
β   β    ββββπ AppRoutes.jsx
    |     ββββπDashboard.jsx
    |    ββββπ PrivateRoutes.jsx
    |    ββββπ PublicRoutes.jsx
β   ββββπ styles/
β   β   ββββπ styles.css
β   β   ββββπ styles.js
β   ββββπ test/
β   β   ββββπ Apptest.test.js
β   ββββπ index.js
ββββπ .gitignore
ββββπ package-lock.json
ββββπ package.json
ββββπ README.md

``````

## πβ Dependencias usadas

    1. Puedes clonar el repositorio
    2. Abre tu terminal y digita "nmp i"
    3. Digita "npm start"


    "firebase": "^9.8.4",
    "react": "^18.2.0",
    "react-bootstrap": "^2.4.0",
    "react-dom": "^18.2.0",
    "react-icons": "^4.4.0",
    "react-redux": "^8.0.2",
    "react-router-dom": "^6.3.0",
    "react-scripts": "5.0.1",
    "redux": "^4.2.0",
    "redux-thunk": "^2.4.1",
    "styled-components": "^5.3.5",
    "thunk": "^0.0.1",
    "web-vitals": "^2.1.4"

## πβ Despliegue del proyecto

    Puedes ver el proyecto aquΓ­ : https://prueba-tecnica-one.vercel.app/


## π»β Recursos de interes

    React-bootstrap: https://react-bootstrap.netlify.app/
    API Weather : https://openweathermap.org/api
    Cloudinary: https://cloudinary.com

