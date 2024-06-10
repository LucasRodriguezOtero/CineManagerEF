# CineManagerEF
Este repositorio contiene el código de una aplicación de gestión de cine desarrollada como parte de un trabajo academico.
## Gestión de Cine con Entity Framework Core 
La aplicación de gestión de cine ha sido desarrollada utilizando C# como el lenguaje de programación principal. Se empleó Entity Framework Core como el ORM, mientras que se utilizó LINQ para consultas y manipulación de datos. Para el almacenamiento de los datos de la aplicación, se optó por SQL Server como el sistema de gestión de base de datos relacional. La aplicación de escritorio fue desarrollada utilizando .NET Framework.
## Configuración y Uso

### Configuración

1. **Clonar el Repositorio:** 
Clona este repositorio en tu máquina local utilizando el siguiente comando en tu terminal: `git clone https://github.com/LucasRodriguezOtero/CineManagerEF.git`
2. **Abrir el Proyecto en Visual Studio:**
Abre Visual Studio y selecciona la opción "Abrir Proyecto/Solución". Navega hasta el directorio donde clonaste el repositorio y selecciona el archivo de solución (.sln).
3. **Configurar la Cadena de Conexión a la Base de Datos:**
Abre el archivo `appsettings.json` en tu proyecto y modifica la cadena de conexión bajo la sección `"ConnectionStrings"` para que coincida con tu instancia de SQL Server.

### Uso

1. **Agregar una Migración:**
Para agregar una migración, ejecuta el siguiente comando desde la Consola del Administrador de Paquetes NuGet en Visual Studio (PM Console): `Add-Migration NOMBRE_DE_LA_MIGRACION`
2. **Aplicar Migraciones Pendientes:**
Para aplicar todas las migraciones pendientes y actualizar la base de datos, ejecuta el siguiente comando desde la Consola del Administrador de Paquetes NuGet: `Update-Database`
3. **Ejecutar la Aplicación:**
Ejecuta la aplicación desde Visual Studio haciendo clic en el botón de "Iniciar" o presionando `F5`. Esto compilará el proyecto y ejecutará la aplicación de gestión de cine.
4. **Explorar la Funcionalidad:**
Listo ya podes explorar todas las funcionalidades de esta aplicacion.

### Gracias!
