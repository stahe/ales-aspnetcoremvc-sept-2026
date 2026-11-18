# Introducción paso a paso al framework web ASP.NET Core MVC

**El curso está disponible en línea aquí: [https://stahe.github.io/ales-aspnetcoremvc-sept-2026/](https://stahe.github.io/ales-aspnetcoremvc-sept-2026/)**

## Descripción general

Este curso ofrece una guía paso a paso para construir una aplicación web MVC con **ASP.NET Core MVC** (.NET 10, C#). Las páginas HTML las genera el servidor mediante vistas **Razor**, sin un framework JavaScript del lado del navegador.

Es la continuación del curso *Introducción paso a paso al framework web NestJS* (2026) y sigue exactamente la misma estructura:

1. **28 ejemplos breves**, cada uno centrado en un concepto específico:
   - controladores, acciones y enrutamiento;
   - modelo de acción: enlace de parámetros, conversión y validación;
   - vistas Razor: plantillas, vistas parciales, helpers y Tag Helpers;
   - formularios, validación y el patrón Post/Redirect/Get (TempData);
   - internacionalización (francés/inglés);
   - ámbitos de datos: Singleton, Scoped y Transient; cookies;
   - ciclo de vida de la solicitud: middleware, filtros, páginas de error;
   - autenticación mediante un token JWT en una cookie, roles, CAPTCHA y limitación de tasa;
   - arquitectura en capas (Web / Negocio / DAO) con **Entity Framework Core** y **MySQL**.
2. **Un caso de estudio completo**, *RdvMedecins*: una aplicación de gestión de citas para un consultorio médico, con tres roles (administrador, médicos, pacientes). El curso ofrece explicaciones detalladas de cada uno de sus archivos.

Los lectores no necesitan conocimientos previos de ASP.NET Core: cada ejemplo está comentado línea por línea, y el curso indica la URL exacta que se debe probar para cada uno.

## Entorno

- SDK de .NET 10
- Visual Studio Code + extensión C# Dev Kit
- MySQL (por ejemplo, con Laragon)
- curl

## Autor

Este curso fue escrito por **Claude** (Anthropic) a petición de Serge Tahé — septiembre de 2026.
