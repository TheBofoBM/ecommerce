# Documentación de código  
### Introducción a las Ventanas de Alquiler Smart

Alquiler Smart es una aplicación desarrollada en Java utilizando el entorno de construcción **Maven**. Su propósito es gestionar de manera eficiente la administración de apartamentos, permitiendo a los propietarios y administradores realizar un seguimiento de los alquileres, los inquilinos y las transacciones relacionadas con sus propiedades.

La interfaz gráfica de Alquiler Smart está compuesta por varias ventanas diseñadas para facilitar la navegación y la gestión de los apartamentos. Estas ventanas están organizadas en módulos específicos, cada uno con funcionalidades bien definidas:

1. **Ventana de Inicio de Sesión:**
   - Permite a los usuarios autenticarse en el sistema con sus credenciales.
   - Implementa validaciones para evitar accesos no autorizados.

2. **Ventana Principal:**
   - Actúa como el punto central de navegación, ofreciendo acceso a las diferentes funciones del sistema.
   - Contiene menús y botones para gestionar apartamentos, inquilinos y pagos.

3. **Ventana de Gestión de Apartamentos:**
   - Permite registrar nuevos apartamentos con detalles como ubicación, tamaño y precio de alquiler.
   - Facilita la edición y eliminación de registros existentes.

4. **Ventana de Gestión de Inquilinos:**
   - Proporciona un listado de inquilinos registrados con sus datos de contacto.
   - Permite agregar, modificar o eliminar información de los inquilinos.

5. **Ventana de Pagos y Facturación:**
   - Permite registrar los pagos de alquiler y generar facturas.
   - Ofrece un historial de pagos para cada inquilino.

6. **Ventana de Reportes:**
   - Genera informes detallados sobre los alquileres, pagos pendientes y ocupación de los apartamentos.
   - Exporta información en diferentes formatos para facilitar su análisis.

Cada una de estas ventanas ha sido desarrollada utilizando el framework **Swing** o **JavaFX**, según las necesidades del proyecto, asegurando una experiencia de usuario fluida e intuitiva. Además, la arquitectura basada en Maven permite una gestión modular del código, facilitando la escalabilidad y el mantenimiento del sistema.

En las siguientes secciones, se detallará el funcionamiento específico de cada ventana y sus interacciones dentro de la aplicación Alquiler Smart.

