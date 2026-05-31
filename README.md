<div align="center">

# GymApp
### Plataforma de gestión para entrenadores personales

[![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![PocketBase](https://img.shields.io/badge/PocketBase-B8DBE4?style=for-the-badge&logo=pocketbase&logoColor=black)](https://pocketbase.io)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)

> Aplicación web fullstack diseñada para entrenadores personales que quieren gestionar clientes, rutinas y seguimiento de progreso desde un único lugar.

**[🚀 Ver Demo en vivo](https://gymappdemo.davidrus.dev/)**

</div>

---

## Capturas

<div align="center">

| Login | Dashboard Admin | Clientes |
|:---:|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/d693d94a-5600-4049-b9e9-ae61d1715c73" /> | <img width="220" src="https://github.com/user-attachments/assets/32d8b8e1-ed6f-44e7-a9c0-517bf0d68531" /> | <img width="220" src="https://github.com/user-attachments/assets/5ec0e191-8299-4b77-9b5c-b51fd09b4f95" /> |

| Detalle de Cliente | Notas | Galería de Archivos |
|:---:|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/d8674c4b-fed0-4b09-8756-8bfebf81a259" /> | <img width="220" src="https://github.com/user-attachments/assets/bce62a10-4038-4b44-b1c6-7983b29c1a5b" /> | <img width="220" src="https://github.com/user-attachments/assets/7881089f-15a0-4e6d-9e16-b15a43bf9d9a" /> |

| Visualizador de Media | Rutinas | Crear Rutina |
|:---:|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/40f38b56-36fb-430b-be92-f25b8fbc25c6" /> | <img width="220" src="https://github.com/user-attachments/assets/fc7b9e9d-081f-434f-9a32-679b79bc2bc1" /> | <img width="220" src="https://github.com/user-attachments/assets/3566ac30-d5af-4778-960c-e3a7b6fa34cd" /> |

| Fotos y Videos | Visualizador Galería | Dashboard Cliente |
|:---:|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/33be80b3-c018-410d-884a-ed838c872392" /> | <img width="220" src="https://github.com/user-attachments/assets/51dbc1a7-cfbe-4d19-8801-2bcf565cff19" /> | <img width="220" src="https://github.com/user-attachments/assets/b21eae98-b805-434a-930a-eac5b0cd5a45" /> |

| Rutina Asignada | Subir Progreso |
|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/fe8bad1f-c05d-429d-8380-1db1fc2eec9a" /> | <img width="220" src="https://github.com/user-attachments/assets/ae2a797d-7db6-4918-b4df-5076f46ede69" /> |

</div>

---

## Stack tecnológico

| Tecnología | Uso |
|---|---|
| **[React 19](https://react.dev)** | Frontend SPA con hooks y estado local |
| **[Tailwind CSS v4](https://tailwindcss.com)** | Estilos utility-first, diseño responsive mobile-first |
| **[Vite](https://vitejs.dev)** | Bundler y servidor de desarrollo |
| **[PocketBase](https://pocketbase.io)** | Backend — base de datos, autenticación y storage en un único binario |
| **[Docker](https://docker.com)** | Contenerización del backend en producción |
| **[Coolify](https://coolify.io)** | Self-hosted PaaS — deploy automático del frontend y backend |
| **[Lucide React](https://lucide.dev)** | Iconografía |

---

## Funcionalidades

### Panel de administrador (entrenador)

- **Dashboard** con métricas en tiempo real — clientes activos, rutinas, vídeos pendientes y tasa de retención
- **Gestión de clientes** — crear, editar, activar/desactivar y eliminar clientes
- **Rutinas tipo bloc de notas** — creación libre por días sin estructuras rígidas de series/repeticiones
- **Asignación de rutinas** — asignar y cambiar la rutina activa de cada cliente
- **Galería de progreso** — visualización de vídeos y fotos subidos por los clientes con sistema de revisión y respuesta
- **Notas por cliente** — añadir y gestionar notas privadas sobre cada cliente
- **Reproductor integrado** — visualización de media con descarga de archivos
- **Informe PDF** — generación de informes por cliente exportables

### Panel de cliente

- **Dashboard personalizado** — saludo, rutina asignada, racha de entrenamientos y últimas subidas
- **Racha de entrenamientos** — contador de días consecutivos de actividad
- **Visualización de rutina** — acceso a la rutina asignada organizada por días
- **Registro de entrenamientos** — logs de sesión con notas y historial
- **Subida de progreso** — vídeos (hasta 100 MB) y fotos con nota adjunta
- **Compresión automática de imágenes** — redimensionado a 1920×1080 antes de subir
- **Galería personal** — historial de subidas con feedback del entrenador

### General

- **Autenticación** con PocketBase — login, sesión persistente y cierre de sesión
- **Roles diferenciados** — admin y cliente con paneles completamente separados
- **Perfil editable** — cambio de nombre y contraseña
- **Reglas de acceso** por colección — los clientes solo acceden a sus propios datos
- **Diseño responsive** — optimizado para móvil, funcional en desktop
- **Animaciones de transición** entre pantallas con slide suave
- **Persistencia de navegación** — recuerda la última sección visitada al recargar
- **Configurable por variables de entorno** — nombre del gimnasio, colores de marca y logo

---

## Modelo de datos

```
users             → usuarios (admin / client) con perfil extendido
routines          → rutinas creadas por el entrenador
routine_days      → días de cada rutina con contenido libre
client_routines   → asignación de rutina activa a cada cliente
workout_completions → registro de días de entrenamiento completados
workout_logs      → notas de sesión por día de rutina
progress_uploads  → vídeos y fotos subidos por los clientes
client_notes      → notas del entrenador sobre cada cliente
```

---

## Despliegue

El frontend se despliega como imagen Docker estática servida por Nginx, gestionado por Coolify con SSL automático vía Traefik. El backend (PocketBase) corre como servicio Docker independiente en el mismo VPS.

```
Frontend → Coolify → Docker (nginx:alpine) → gymappdemo.davidrus.dev
Backend  → Coolify → Docker (pocketbase)   → pb-gymapp-1.davidrus.dev
```

---

<div align="center">

Desarrollado por **David Rus** como proyecto freelance para entrenadores personales.

</div>
