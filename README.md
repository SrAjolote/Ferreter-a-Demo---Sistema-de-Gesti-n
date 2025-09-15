# Ferretería Demo - Sistema de Gestión

Sistema completo de gestión para ferretería con tienda online integrada y conexión directa a WhatsApp para ventas.

## 🛠️ Características Principales

- **Gestión de Inventario**: Control de stock en tiempo real con alertas
- **Tienda Online**: Catálogo público con búsqueda y filtros
- **Ventas por WhatsApp**: Integración directa para procesar pedidos
- **Panel Administrativo**: Gestión completa de productos y categorías
- **Diseño Responsive**: Compatible con todos los dispositivos

## 🚀 Tecnologías Utilizadas

- PHP 8.0+
- MySQL
- HTML5, CSS3, JavaScript
- Bootstrap 5.3
- Tailwind CSS (para iconos)
- API de WhatsApp

## 📦 Módulos del Sistema

1. **Inventario**: Control de stock y categorías
2. **Tienda Online**: Catálogo público sin necesidad de login
3. **Panel Admin**: Gestión completa del sistema
4. **Sistema de Ventas**: Procesamiento de pedidos vía WhatsApp
5. **Reportes**: Informes básicos de stock y ventas

## 🗄️ Estructura de Base de Datos

El sistema incluye las siguientes tablas principales:
- `productos` - Inventario de productos
- `categorias` - Categorías de productos
- `usuarios` - Usuarios administrativos
- `pedidos` - Registro de pedidos realizados

## ⚙️ Instalación

1. **Requisitos del Servidor**:
   - PHP 8.0 o superior
   - MySQL 5.7 o superior
   - Apache/Nginx con mod_rewrite habilitado

2. **Configuración**:
   ```bash
   # Crear base de datos
   mysql -u root -p -e "CREATE DATABASE ferreteria_demo;"
   
   # Importar estructura inicial
   mysql -u root -p ferreteria_demo < database/init.sql
   ```

3. **Configurar Credenciales**:
   Editar el archivo `config/database.php`:
   ```php
   define('DB_HOST', 'localhost');
   define('DB_NAME', 'ferreteria_demo');
   define('DB_USER', 'tu_usuario');
   define('DB_PASS', 'tu_password');
   ```

4. **Acceso Inicial**:
   - URL Admin: `tudominio.com/admin`
   - Usuario: admin@ferreteriademo.com
   - Contraseña: Admin123

## 📱 Uso del Sistema

### Para Clientes:
1. Navegar por el catálogo de productos
2. Usar filtros y búsqueda para encontrar productos
3. Agregar productos al carrito
4. Completar formulario de contacto
5. Enviar pedido directamente por WhatsApp

### Para Administradores:
1. Gestionar productos y categorías
2. Controlar niveles de stock
3. Ver reportes de inventario
4. Administrar usuarios del sistema

## 🔧 Personalización

### Colores Corporativos:
El sistema usa la siguiente paleta de colores:
- Naranja Principal: `#FF7F00`
- Plateado: `#C0C0C0`
- Gris Oscuro: `#333333`

### Configuración WhatsApp:
Editar el número de WhatsApp en `config/whatsapp.php`:
```php
define('WHATSAPP_NUMBER', '527861624359');
define('WHATSAPP_MESSAGE', 'Hola, me interesa los siguientes productos:');
```

## 📞 Soporte y Contacto

- **Desarrollador**: David Sánchez
- **Email**: gsdavid151006@gmail.com
- **WhatsApp**: +52 7861624359
- **Portafolio**: [davidsanchez.shop](https://davidsanchez.shop)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🐛 Reportar Problemas

Si encuentras algún error o tienes sugerencias:
1. Revisa la documentación en `/docs`
2. Abre un issue en este repositorio
3. Contacta por WhatsApp para soporte inmediato


**¡Sistema 100% funcional!** 🎯
No incluye opciones "en desarrollo" - Todo está completo y listo para usar.
