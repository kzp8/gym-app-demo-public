<div align="center">

# 🔥 GymApp
### Plataforma de gestión para entrenadores personales

[![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)

> Aplicación web fullstack diseñada para entrenadores personales que quieren gestionar clientes, rutinas y seguimiento de progreso desde un único lugar.

**[🚀 Ver Demo en vivo](https://gymappdemo.davidrus.dev/)**

```markdown
## 🔑 Credenciales de Demo

> Puedes explorar la app con cualquiera de estas cuentas. Por favor, no borres los datos de prueba 🙏

| Rol | Email | Contraseña |
|:---:|:---:|:---:|
| 👑 **Administrador** | `admin@admin.com` | `admin1234` |
| 👤 **Cliente 1** | `clientedemo1@demo.com` | `clientedemo1` |
| 👤 **Cliente 2** | `clientedemo2@demo.com` | `clientedemo2` |

|👤 **Cliente 2** actualmente esta desactivado|

```



</div>

---

## 📸 Capturas

<div align="center">

| Login | Dashboard Admin | Clientes |
|:---:|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/11cb6857-71f2-4f27-b547-50d7ee906f07" /> | <img width="220" src="https://github.com/user-attachments/assets/c66046bf-dbc6-4a65-94ce-a9cf3a7247ad" /> | <img width="220" src="https://github.com/user-attachments/assets/13609c28-a2a1-4e42-a8bd-207e19c75f5a" /> |

| Detalle de Cliente | Notas | Galería de Archivos |
|:---:|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/0fa9f644-feb4-4631-8d81-77074959d013" /> | <img width="220" src="https://github.com/user-attachments/assets/71c02b11-6b23-4cde-9f89-4cb66cdfa33d" /> | <img width="220" src="https://github.com/user-attachments/assets/1a56a9b7-6b24-48c3-95c3-e9526ac56e6f" /> |

| Visualizador de Media | Rutinas | Crear Rutina |
|:---:|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/e0012b43-9736-4691-a3e6-85953aa00015" /> | <img width="220" src="https://github.com/user-attachments/assets/84e1e980-ba84-4638-bacd-dc1d66182c92" /> | <img width="220" src="https://github.com/user-attachments/assets/b6d9992a-40d8-466a-bfe6-1d2665432fa0" /> |

| Fotos y Videos | Visualizador Galería | Dashboard Cliente |
|:---:|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/87b74336-8c54-47ef-af32-9347101005ca" /> | <img width="220" src="https://github.com/user-attachments/assets/ec3558d8-5a86-400b-a851-a6f9475b51c6" /> | <img width="220" src="https://github.com/user-attachments/assets/a3d51858-56c2-4898-b910-12deeaf17b1f" /> |

| Rutina Asignada | Subir Progreso |
|:---:|:---:|
| <img width="220" src="https://github.com/user-attachments/assets/63308a80-57d1-4bc4-90a9-3b7c9a1a5c5e" /> | <img width="220" src="https://github.com/user-attachments/assets/9cf41210-7f61-40cd-a528-e84e729f89e8" /> |

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
