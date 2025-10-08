# Facebook Clone

Un clon completo de Facebook construido con Next.js, React, Firebase y Tailwind CSS.

## Características

- Autenticación con correo/contraseña y Google
- Feed de publicaciones en tiempo real
- Sistema de amigos con solicitudes
- Historias
- Mensajería en tiempo real
- Notificaciones
- Grupos y páginas
- Marketplace
- Empleos
- Eventos
- Y mucho más

## Tecnologías

- **Next.js 15** - Framework de React
- **React 19** - Biblioteca de UI
- **Firebase** - Backend (Auth, Firestore, Storage)
- **Tailwind CSS v4** - Estilos
- **Font Awesome v6** - Iconos
- **TypeScript** - Tipado estático

## Instalación

1. Clona el repositorio:
\`\`\`bash
git clone <tu-repositorio>
cd facebook-clone
\`\`\`

2. Instala las dependencias:
\`\`\`bash
npm install
\`\`\`

3. Configura Firebase siguiendo las instrucciones en [FIREBASE_SETUP.md](./FIREBASE_SETUP.md)

4. Inicia el servidor de desarrollo:
\`\`\`bash
npm run dev
\`\`\`

5. Abre [http://localhost:3000](http://localhost:3000) en tu navegador

## Estructura del Proyecto

\`\`\`
├── app/                    # Páginas de Next.js
│   ├── feed/              # Feed principal
│   ├── friends/           # Gestión de amigos
│   ├── messages/          # Mensajería
│   ├── groups/            # Grupos
│   ├── pages/             # Páginas de Facebook
│   ├── watch/             # Videos
│   ├── marketplace/       # Marketplace
│   ├── gaming/            # Gaming
│   ├── jobs/              # Empleos
│   ├── events/            # Eventos
│   ├── memories/          # Recuerdos
│   ├── saved/             # Guardados
│   └── fundraisers/       # Recaudación de fondos
├── components/            # Componentes reutilizables
│   ├── auth/             # Componentes de autenticación
│   ├── feed/             # Componentes del feed
│   └── layout/           # Componentes de layout
├── contexts/             # Contextos de React
├── lib/                  # Utilidades y configuración
└── public/              # Archivos estáticos
\`\`\`

## Variables de Entorno Requeridas



\`\`\`env
NEXT_PUBLIC_FIREBASE_API_KEYAIzaSyDEEMpj6JU6g4MNxXnoGRLu0z_7IHzmVlsNEXT_PUBLIC_FIREBASE_AUTH_DOMAINcreativestudio-bb60c.firebaseapp.comNEXT_PUBLIC_FIREBASE_PROJECT_IDcreativestudio-bb60cNEXT_PUBLIC_FIREBASE_STORAGE_BUCKETcreativestudio-bb60c.appspot.comNEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID404444097357NEXT_PUBLIC_FIREBASE_APP_ID1:404444097357:web:1d0015a8a6c05184382504NEXT_PUBLIC_FIREBASE_MEASUREMENT_IDG-3NNB0TZRC9
\`\`\`

## Características Implementadas

### Autenticación
- Registro con correo y contraseña
- Inicio de sesión con correo y contraseña
- Inicio de sesión con Google
- Cierre de sesión
- Persistencia de sesión

### Feed
- Crear publicaciones con texto e imágenes
- Ver publicaciones en tiempo real
- Dar like a publicaciones
- Comentar publicaciones
- Compartir publicaciones
- Eliminar publicaciones propias

### Amigos
- Enviar solicitudes de amistad
- Aceptar/rechazar solicitudes
- Ver lista de amigos
- Sugerencias de amigos

### Historias
- Ver historias de amigos
- Crear historias propias

### Mensajería
- Chat en tiempo real
- Lista de conversaciones
- Enviar mensajes de texto

### Notificaciones
- Notificaciones de solicitudes de amistad
- Notificaciones de likes y comentarios
- Notificaciones de mensajes

## Despliegue

Para desplegar en Vercel:

1. Haz push de tu código a GitHub
2. Importa el proyecto en Vercel
3. Configura las variables de entorno en Vercel
4. Despliega

## Licencia

MIT
