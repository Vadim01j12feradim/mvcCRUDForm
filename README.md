# <Nombre del Proyecto>

<div align="center">
  <img src="images/logo.png" alt="Logo del Proyecto" width="200">
</div>

[![Licencia](https://img.shields.io/badge/Licencia-MIT-blue.svg)](LICENSE)

Este es un proyecto simple de un CRUD completo de entre clientes y pedidos los cuales se encuentran relacionados, fue desarrollado en windows FORM con un estilo de programacion MVC,
una base de datos MySQL con unicamente dos tablas, una para los clientes y otra para los pedidos,
se encuentra validado en las entradas segun el tipo de datos requeridos, tambien se evito utilizar
open connections ya que peuden llegar a ocacionar problemas en un entorno de desarrollo cuando se reciben muchas peticiones.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Licencia](#licencia)
## Instalación

Para este proyecto se poseen unicamente dos archivos, el mprimero (mvc.rar) consta del proyecto en C#, para poder utilizarlo es necesario clonar el repositorio para disponer de los archivos mecnionados, para esto haremos uso del siguiete comando.

```bash
git clone https://github.com/Vadim01j12feradim/mvcCRUDForm.git
```

El siguiente paso es precisamente improtar la base de datos MySQL por lo que se inclye precisamente el archivo mvc.sql.
Una vez se ha restablecida la base de datos abrir el proyecto con visual studio .NET para poder ejecutarlo.
Es posible que se requiren los siguientes paquetes de nuggets.
- Newtonsoft.Json
- MySql.Data.MySqlClient - 8.0.32.1

Es importante instalar la version mencionada de MySql.Data.MySqlClient ya que versiones superiores
para el desarrollo de este proyecto ocacionaron algunos percances.

- ** Ejecurar **

## Licencia

La Licencia MIT es una licencia de software de código abierto que permite a los destinatarios utilizar, modificar y distribuir el software de manera libre y gratuita.

- **Libertad para Usar:** Puedes hacer lo que quieras con este software.
- **Libertad para Modificar:** Puedes modificar el código fuente según tus necesidades.
- **Libertad para Distribuir:** Puedes distribuir el software original o modificado de forma gratuita o comercial.
- **Sin Garantía:** El software se proporciona "tal cual", sin garantía de ningún tipo. El uso es bajo tu propio riesgo.

### Nota de Licencia

Este proyecto utiliza la Licencia MIT para fomentar la colaboración y el intercambio en la comunidad de desarrollo de software. Al contribuir a este proyecto, aceptas y reconoces esta licencia.


