<h1 align="center"> API REST - PRÁCTICA II </h1>
<h4 align="center"> Persistencia de datos con Sequelize y PostgreSQL </h4>

Para este pequeño desafío les propongo que desarrollen una API REST que conste de sólamente tres endpoints:

-   **GET |** _'/products'_ para obtener todos los registros de la tabla **Products**.
-   **POST |** _'/products'_ para crear un nuevo registro en la tabla **Products**.
-   **PATCH |** _'/products/:id'_ para actualizar un registro de la tabla **Products**.

Armen esta API REST muy simple y básica, respetando el patrón MVC, y SIN AYUDARSE de ningún ejercicio anterior.
La idea es que se pongan más cancheras en el armado básico de toda la app. Cualquier cosa que no sepan o no estén seguras, consulten la documentación, sea de Express, TypeScript, Sequelize, o lo que haga falta.

La entidad **Product** tiene **id**, **name**, **cost**, **password** y **creation_date**.

**YAPA -->** Validar los datos entrantes con Zod.
