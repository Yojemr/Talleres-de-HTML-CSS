# Maleja's Pink Store - Taller Final: Ecosistema Web

Proyecto web multipágina para una tienda de belleza ficticia llamada **Maleja's Pink Store**. La interfaz conserva una estética rosada, negra y blanca, usa recursos visuales locales y está construida únicamente con clases de Bootstrap 5.

## Tecnologías usadas

- HTML5
- Bootstrap 5 por CDN
- Bootstrap Icons por CDN
- GitHub Pages

## Estructura de carpetas

```text
Taller_4/
├── index.html
├── app/
│   ├── login.html
│   ├── registro.html
│   ├── recuperar.html
│   ├── admin.html
│   └── cliente.html
├── assets/
│   ├── backgrounds/
│   ├── decor/
│   ├── icons/
│   ├── img/
│   ├── logo/
│   └── palette.json
└── README.md
```

## Páginas

- `index.html`: página principal con navbar `fixed-top`, logo, carrusel, servicios, presentación, botones de llamada a la acción y footer.
- `app/login.html`: ingreso demostrativo para cliente y administrativo con correo, contraseña, checkbox y etiquetas flotantes.
- `app/registro.html`: formulario de creación de cuenta para cliente o expositor.
- `app/recuperar.html`: recuperación de contraseña con validación visual Bootstrap para correo no encontrado.
- `app/admin.html`: panel administrativo con sidebar, métricas, tabla responsive, badges, botones de acción y modal de edición.
- `app/cliente.html`: dashboard cliente con sidebar, perfil, alerta dismissible, pestañas de inscripciones activas e historial.

## Ejecutar localmente

Abre `index.html` directamente en el navegador. Todas las rutas son relativas para funcionar desde la carpeta del proyecto.

## Desplegar en GitHub Pages

1. Sube el proyecto al repositorio.
2. En GitHub, entra a **Settings > Pages**.
3. Selecciona la rama principal y la carpeta donde está `Taller_4`.
4. Guarda la configuración y espera la URL pública de GitHub Pages.

## Nota técnica

El diseño usa Bootstrap 5 y Bootstrap Icons mediante CDN. No se creó ningún archivo `.css`, no se usaron etiquetas `<style>` y no se agregaron atributos `style=""`.

