<h1 align="center"> API REST - PRÁCTICA II </h1>
<h4 align="center"> Persistencia de datos con Sequelize y PostgreSQL </h4>

Para este pequeño desafío les propongo que desarrollen una API REST que conste de sólamente tres endpoints:

-   **GET |** _'/products'_ para obtener todos los registros de la tabla **Products**.
-   **POST |** _'/products'_ para crear un nuevo registro en la tabla **Products**.
-   **PATCH |** _'/products/:id'_ para actualizar un registro de la tabla **Products**.

Armen esta API REST muy simple y básica, respetando el patrón MVC, y SIN AYUDARSE de ningún ejercicio anterior.
La idea es que se pongan más cancheras en el armado básico de toda la app. Cualquier cosa que no sepan o no estén seguras, consulten la documentación, sea de Express, TypeScript, Sequelize, o lo que haga falta.

#### PEQUEÑA GUÍA

- Analizar qué dependencias son necesarias para el proyecto e instalarlas.
- Configurar el package.json y el tsconfig.json.
- Configurar la conexión a la DB. Probar que todas las dependencias funcionen, en su aspecto más básico. Probar la conexión a la DB.
- Armar el modelo necesario y probarlo localmente, con sus respectivos métodos de acceso a la DB.
- Armar el ruteo básico con Express, sin conectarlo a la DB, y probar que funcione. Retornar al usuario JSONs mock.
- Conectar la API con la DB y terminar la APP.
- Cuando todo funcione bien, validar los datos con ZOD.

La entidad **Product** tiene **id**, **name**, **cost**, **password** y **creation_date**.

**YAPA -->** Validar los datos entrantes con Zod.
