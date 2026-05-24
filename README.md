<div align="center">

# 🔥 GymApp
### Plataforma de gestión para entrenadores personales

[![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://netlify.com)

> Aplicación web fullstack diseñada para entrenadores personales que quieren gestionar clientes, rutinas y seguimiento de progreso desde un único lugar.

**[🚀 Ver Demo en vivo](https://gym-app-public-demo.netlify.app/)**

```markdown
## 🔑 Credenciales de Demo

> Puedes explorar la app con cualquiera de estas cuentas. Por favor, no borres los datos de prueba 🙏

| Rol | Email | Contraseña |
|:---:|:---:|:---:|
| 👑 **Administrador** | `admin@admin.com` | `admin1234` |
| 👤 **Cliente 1** | `clientedemo1@demo.com` | `clientedemo1` |
| 👤 **Cliente 2** | `clientedemo2@demo.com` | `clientedemo2` |
```



</div>

---

## 📸 Capturas

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

## 🛠️ Stack tecnológico

| Tecnología | Uso |
|---|---|
| **[React 19](https://react.dev)** | Frontend SPA con hooks y estado local |
| **[Tailwind CSS v4](https://tailwindcss.com)** | Estilos utility-first, diseño responsive mobile-first |
| **[Vite](https://vitejs.dev)** | Bundler y servidor de desarrollo |
| **[Supabase](https://supabase.com)** | Backend as a Service — base de datos, autenticación y storage |
| **[PostgreSQL](https://www.postgresql.org)** | Base de datos relacional gestionada por Supabase |
| **[Supabase Auth](https://supabase.com/docs/guides/auth)** | Autenticación con JWT y gestión de sesiones |
| **[Supabase Storage](https://supabase.com/docs/guides/storage)** | Almacenamiento de vídeos y fotos de progreso |
| **[Lucide React](https://lucide.dev)** | Iconografía |
| **[Netlify](https://netlify.com)** | Hosting y deploy |

---

## ✨ Funcionalidades

### 🛡️ Panel de administrador (entrenador)

- **Dashboard** con métricas en tiempo real — clientes activos, rutinas, vídeos pendientes y tasa de retención
- **Gestión de clientes** — crear, editar, activar/desactivar y eliminar clientes con limpieza automática de archivos en storage
- **Rutinas tipo bloc de notas** — creación libre por días sin estructuras rígidas de series/repeticiones
- **Asignación de rutinas** — asignar y cambiar la rutina activa de cada cliente
- **Galería de progreso** — visualización de vídeos y fotos subidos por los clientes con sistema de revisión
- **Notas por cliente** — añadir y gestionar notas privadas sobre cada cliente
- **Reproductor integrado** — visualización de media con descarga de archivos
- **Sistema de revisión** — marcar archivos como vistos o pendientes

### 👤 Panel de cliente

- **Dashboard personalizado** — saludo, rutina asignada y últimas subidas con estado de revisión
- **Visualización de rutina** — acceso a la rutina asignada organizada por días con scroll interactivo
- **Subida de progreso** — vídeos (hasta 100 MB) y fotos (hasta 10 MB) con nota adjunta
- **Compresión automática de imágenes** — redimensionado a 1920×1080 y compresión JPEG antes de subir
- **Historial de subidas** — thumbnails reales y estado de revisión del entrenador

### ⚙️ General

- **Autenticación real** con Supabase Auth — login, sesión persistente y cierre de sesión
- **Roles diferenciados** — admin y cliente con paneles completamente separados
- **Perfil editable** — cambio de nombre y contraseña con verificación de contraseña actual
- **Row Level Security (RLS)** — políticas de seguridad a nivel de base de datos
- **URLs firmadas** para acceso seguro a archivos privados con caducidad de 1 hora
- **Diseño responsive** — optimizado para móvil, funcional en desktop
- **Animaciones de transición** entre pantallas con slide suave
- **Persistencia de navegación** — recuerda la última sección visitada al recargar

---

## 🗄️ Modelo de datos

```
profiles          → usuarios (admin / client)
routines          → rutinas creadas por el entrenador
routine_days      → días de cada rutina con contenido libre
client_routines   → asignación de rutina activa a cada cliente
progress_uploads  → vídeos y fotos subidos por los clientes
client_notes      → notas del entrenador sobre cada cliente
```

---

## 🔐 Seguridad

- Row Level Security activado en todas las tablas
- Clientes solo pueden acceder a sus propios datos
- Archivos en storage privado con URLs firmadas temporales
- Variables de entorno para claves de API
- Verificación de contraseña actual antes de permitir cambios
- Protección de rol — los clientes no pueden elevar sus permisos

---

<div align="center">

Desarrollado por **David Rus** como proyecto freelance para un entrenador personal.

</div>
