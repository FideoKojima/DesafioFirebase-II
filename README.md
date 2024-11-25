# 🔐 Vue Firebase Authentication Demo

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📝 Descripción

Una aplicación de demostración robusta que implementa autenticación de usuarios utilizando Vue.js y Firebase. Este proyecto incluye registro de usuarios, inicio de sesión y una página de inicio protegida.

### ✨ Características Principales

- 🔒 Autenticación completa con Firebase
- 📝 Registro de nuevos usuarios
- 🚪 Inicio de sesión seguro
- 🛡️ Rutas protegidas
- 🎯 Redirección automática
- 🎨 Diseño responsive

## 🚀 Demo en vivo

[Ver Demo](https://tu-proyecto.firebaseapp.com)

## 🛠️ Tecnologías Utilizadas

- Vue.js 3
- Vue Router 4
- Firebase Authentication
- Firebase Hosting
- JavaScript ES6+
- CSS3

## 📋 Prerrequisitos

- Node.js (v14 o superior)
- npm o yarn
- Cuenta en Firebase

## ⚙️ Instalación

1. **Clonar el repositorio**

```bash
git clone https://github.com/FideoKojima/DesafioFirebase-II.git
cd vue-DesafioFirebase-II
```

2. **Instalar dependencias**

```bash
npm install
```

3. **Configurar variables de entorno**
   - Crea un archivo `.env` en la raíz del proyecto
   - Añade tus credenciales de Firebase:

```env
VITE_FIREBASE_API_KEY=tu-api-key
VITE_FIREBASE_AUTH_DOMAIN=tu-proyecto.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=tu-proyecto
VITE_FIREBASE_STORAGE_BUCKET=tu-proyecto.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=tu-messaging-sender-id
VITE_FIREBASE_APP_ID=tu-app-id
```

4. **Iniciar el servidor de desarrollo**

```bash
npm run dev
```

## 🏗️ Estructura del Proyecto

```
src/
├── components/
├── views/
│   ├── Home.vue
│   ├── Login.vue
│   └── SignUp.vue
├── firebase/
│   └── config.js
├── router/
│   └── index.js
├── App.vue
└── main.js
```

## 📱 Vistas

### 🔑 Login

- Inicio de sesión con email y contraseña
- Validación de formularios
- Manejo de errores
- Redirección a Home después del login exitoso

### ✍️ Sign Up

- Registro de nuevos usuarios
- Validación de datos
- Feedback de errores
- Redirección automática post-registro

### 🏠 Home

- Vista protegida
- Información del usuario
- Opción de cerrar sesión
- Diseño responsivo

## 🚀 Despliegue

1. **Construir el proyecto**

```bash
npm run build
```

2. **Inicializar Firebase Hosting**

```bash
firebase init hosting
```

3. **Desplegar**

```bash
firebase deploy
```

## 🔒 Seguridad

- Autenticación segura con Firebase
- Protección de rutas con Vue Router Guards
- Manejo seguro de sesiones de usuario
- Validación de formularios

## 🤝 Contribuir

1. Fork el proyecto
2. Crea tu Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push al Branch (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 👥 Autor

Luis Suarez

## 🙏 Agradecimientos

- [Vue.js](https://vuejs.org/)
- [Firebase](https://firebase.google.com/)
- [Vue Router](https://router.vuejs.org/)

---

⭐️ ¡Si te gustó este proyecto, no olvides darle una estrella! ⭐️
