# BoaClone
Proyecto Socioformativo: Réplica de la Página Web de BOA

**1. Introducción**

El presente informe documenta el desarrollo de un sistema de solicitud y recepción de vuelos replicando la funcionalidad de la página web de BOA (Boliviana de Aviación). Este proyecto busca capacitar a los estudiantes en el diseño e implementación de interfaces dinámicas utilizando Blazor para la interfaz web y Supabase como base de datos en tiempo real.

**2. Objetivos**

**2.1 Objetivo General**

Capacitar a los estudiantes en la implementación de un sistema de solicitud y recepción de vuelos con el uso de Blazor y Supabase.

**2.2 Objetivos Específicos**

Desarrollar una interfaz web funcional para la selección y reserva de vuelos.

Implementar una base de datos en Supabase para gestionar vuelos, pasajeros y reservas.

Automatizar la generación de comprobantes de reserva.

Sincronizar el sistema con Supabase para operaciones en tiempo real.

**3. Marco Teórico**

**3.1 Blazor**

Blazor es un framework de desarrollo web basado en .NET que permite crear aplicaciones interactivas del lado del cliente utilizando C# en lugar de JavaScript.

**3.2 Supabase**

Supabase es una plataforma backend que proporciona una base de datos en tiempo real basada en PostgreSQL, junto con autenticación y almacenamiento de archivos.

**4. Metodología**

Para el desarrollo del sistema, se sigue la metodología de desarrollo incremental, dividiendo el proceso en etapas:

Diseño de la Base de Datos: Creación de tablas en Supabase.

Implementación de la Interfaz: Desarrollo de componentes reutilizables en Blazor.

Integración con Supabase: CRUD de vuelos, pasajeros y reservas.

Generación de Comprobantes: Creación y descarga de recibos.

Pruebas y Optimización: Validación de funcionalidad y rendimiento.

**5. Modelado**

**5.1 Estructura de Base de Datos**

Vuelos: id, origen, destino, fecha, hora, precio.

Pasajeros: id, nombre, apellido, documento, email.

Reservas: id, id_pasajero, id_vuelo, monto_total, fecha_reserva.

**5.2 Arquitectura del Sistema**

Frontend: Blazor WebAssembly.

Backend: Supabase para almacenamiento y gestión de datos.

Autenticación: Opcionalmente, sistema de login con Supabase Auth.

**6. Conclusiones**

El proyecto permite a los estudiantes adquirir conocimientos sobre el desarrollo de aplicaciones web modernas con Blazor y bases de datos en tiempo real con Supabase. La implementación de operaciones CRUD y la generación de comprobantes refuerzan habilidades clave en el desarrollo full-stack.

**7. Bibliografía**

Documentación oficial de Blazor: https://learn.microsoft.com/en-us/aspnet/core/blazor

Documentación oficial de Supabase: https://supabase.com/docs

**8. Anexos**

Capturas de pantalla del sistema.

Fragmentos de código relevantes.
