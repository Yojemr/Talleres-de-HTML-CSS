# Maleja's Pink Store - Taller Final: Ecosistema Web

Proyecto web multipágina para una tienda de belleza ficticia llamada **Maleja's Pink Store**. La interfaz usa una estética rosada, negra y blanca, con recursos visuales locales para logo, carrusel, servicios y perfil de usuario.

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
│   ├── dashboard-admin.html
│   └── dashboard-cliente.html
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

- `index.html`: página principal con navbar sticky, logo, carrusel, servicios, presentación, botones de llamada a la acción y footer.
- `app/login.html`: formulario de ingreso con validaciones HTML5.
- `app/registro.html`: formulario de creación de cuenta para cliente o expositor.
- `app/recuperar.html`: recuperación de contraseña con alerta informativa.
- `app/dashboard-admin.html`: panel administrativo con sidebar, métricas, tabla y modal de edición.
- `app/dashboard-cliente.html`: perfil de cliente con pestañas, inscripciones, servicios y favoritos.

## Ejecutar localmente

Abre `index.html` directamente en el navegador. Todas las rutas son relativas para funcionar desde la carpeta del proyecto.

## Nota técnica

El diseño usa Bootstrap 5 y Bootstrap Icons mediante CDN. No se creó ningún archivo `.css`, no se usaron etiquetas `<style>` y no se agregaron atributos `style=""`.
