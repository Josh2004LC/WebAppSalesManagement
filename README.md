# WebAppSalesManagement — Sistema de Gestión de Ventas

Aplicación web desarrollada con **ASP.NET Core MVC y C#**, orientada a la administración de clientes, productos, usuarios y ventas.

El sistema utiliza una API REST independiente para consultar y almacenar información, y permite generar reportes en PDF.

## Tecnologías utilizadas

- C# y .NET 8
- ASP.NET Core MVC
- Razor Views
- Bootstrap
- HttpClient
- Rotativa.AspNetCore
- API REST

## Funcionalidades

- Pantalla de inicio de sesión.
- Gestión de clientes.
- Administración de productos.
- Gestión de usuarios.
- Registro de ventas con sus respectivos detalles.
- Consulta, modificación y eliminación de ventas.
- Visualización de reportes.
- Generación de documentos PDF.

## Estructura del proyecto

- `Controllers`: lógica de las operaciones web.
- `Models`: modelos de clientes, productos, usuarios y ventas.
- `Services`: comunicación con la API.
- `Views`: formularios, listados y reportes.
- `wwwroot`: recursos estáticos y herramientas para PDF.

## Instalación

1. Clonar el repositorio.
2. Instalar el SDK de .NET 8.
3. Configurar y ejecutar SalesManagementAPI.
4. Revisar las direcciones de la API en `Program.cs`, actualmente configuradas con una URL local.
5. Ejecutar:

```bash
dotnet restore
dotnet run
```

6. Abrir la dirección local indicada por la aplicación.

## Capturas de pantalla

*Pendiente: agregar capturas reales de los módulos de clientes, productos, ventas y reportes.*

## Mejoras futuras

- Implementar autenticación y autorización por usuario.
- Sustituir el almacenamiento estático del nombre de usuario por información asociada a la sesión.
- Centralizar la configuración de la URL de la API.
- Incorporar pruebas automatizadas.
- Mejorar el diseño adaptable a dispositivos móviles.

## Backend

[SalesManagementAPI](https://github.com/Josh2004LC/SalesManagementAPI)

## Estado del proyecto

Proyecto académico desarrollado para aplicar conocimientos de sistemas empresariales, arquitectura MVC, consumo de APIs REST y generación de reportes.
