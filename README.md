# 📚 Comic-Verse

**Comic-Verse** es una plataforma digital gratuita orientada a los amantes de los cómics. Permite a los usuarios registrarse, iniciar sesión, subir y leer archivos en formato CBR, así como interactuar con otros miembros de la comunidad a través de comentarios y chat. Esta aplicación busca democratizar el acceso al contenido de cómics y fortalecer la interacción entre fanáticos mediante una experiencia de lectura inmersiva, segura y social.

---

## 🚀 Características principales

- ✅ Registro e inicio de sesión seguro con autenticación basada en JWT (RFC7519)
- 📥 Carga y lectura de archivos `.CBR` directamente desde el navegador
- 🔍 Búsqueda avanzada por título, autor, género y año de publicación
- 📚 Biblioteca personal y general para organizar cómics
- 💬 Sistema de comentarios y valoraciones
- 🔐 Seguridad robusta: cifrado de contraseñas, protección contra ataques (XSS, CSRF, SQLi)
- ⚡ Alta eficiencia: búsqueda y carga rápida de archivos
- 🧠 Cumple con estándares de calidad de software ISO/IEC 25010 (SQuaRE)

---

## 🛠️ Tecnologías utilizadas

| Componente       | Tecnología       |
|------------------|------------------|
| Frontend         | React.js         |
| Backend          | Node.js + Express|
| Base de Datos    | MongoDB (ODM: Mongoose) |
| Seguridad        | JSON Web Tokens (JWT), bcrypt, CORS |
| Comunicación     | Socket.IO (chat) |
| Visualización    | Lector de archivos `.CBR` en el navegador |
| Estándares       | IEEE 830-1993, ISO/IEC 25010           |

---

## 🧩 Estructura de Módulos

- **Autenticación de usuarios**
- **Gestión de perfil**
- **Carga y visualización de cómics CBR**
- **Buscador de cómics**
- **Sistema de comentarios y valoraciones**
- **Notificaciones**
- **Chat en tiempo real (Socket.IO)**

---

## 📦 Requisitos de instalación

### Requisitos previos

- Node.js ≥ 18
- MongoDB ≥ 6
- Git

### Instalación

```bash
# Clona el repositorio
git clone https://github.com/tuusuario/comic-verse.git
cd comic-verse

# Instala dependencias para el backend
cd server
npm install

# Instala dependencias para el frontend
cd ../client
npm install

# Configura las variables de entorno (.env en /server)
🧪 Pruebas
Se realizaron pruebas de rendimiento con Morgan y herramientas de navegador (DevTools).

La interfaz fue validada en navegadores modernos: Edge, Firefox y Opera.

Seguridad verificada contra vulnerabilidades en dependencias (Express, cookie-parser).

🔒 Restricciones del sistema
Máximo 1000 usuarios simultáneos sin degradación

Archivos .CBR ≤ 100 MB

No se permiten archivos .CBZ, .PDF o imágenes sueltas

Optimización principal para uso en escritorio

⚠️ Descargo de responsabilidad
Comic-Verse no aloja ni distribuye cómics comerciales. Todos los archivos subidos son responsabilidad de los usuarios. El uso de la plataforma es estrictamente personal y no comercial. Se prohíbe copiar, compartir, modificar o distribuir el contenido cargado.

🤝 Contribuciones
¡Se aceptan contribuciones! Abre un Pull Request o un Issue para mejoras, correcciones o sugerencias.

👨‍💻 Autor
David Felipe Villamarin Limas
Proyecto académico — Fundación Universitaria Para El Desarrollo Humano - Uninpahu

📄 Licencia
MIT License — libre uso académico y educativo.

### Documentaciob

Para este proyecto segui el ciclo de vida con un producto mínimo viable (MVP) por el tiempo establecido, donde, antes de iniciar a codificar, se realiza la documentación, se levantan requerimientos funcionales, no funcionales, casos de uso, historias de usuario y restricciones del software, se documentó este proceso, se logró finalizar el primer ciclo de vida del sistema desarrollado.
Editar
