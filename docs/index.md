
# Creación de cuenta y primera publicación de vacante.

**Repositorio:** <https://github.com/occmundial/recruiter-selfService>

**Requisitos previos:**

* [Node 10.x en adelante](<https://nodejs.org/docs/latest-v10.x/api/>)

**Ambientes:**

* Local: <http://localhost:3051/empresas/publica-tu-vacante/a-quien-buscas> con dependencia de backend-login: <https://github.com/occmundial/backend-login>
* Desarrollo: <https://master.occdev.com.mx/empresas/publica-tu-vacante/a-quien-buscas>
* Producción: <https://www.occ.com.mx/empresas/publica-tu-vacante/a-quien-buscas>

**Principales Tecnologías:**

* [NextJS 12.1.4](<https://github.com/vercel/next.js/releases/tag/v12.1.4>)
* [Apollo 2.33.4](<https://github.com/apollographql/apollo-tooling/releases/tag/apollo%402.33.4>)
* [Graphql 15.5.1](<https://github.com/graphql/graphql-js/releases/tag/v15.5.1>)
* [React 17.0.2](<https://github.com/facebook/react/releases/tag/v17.0.2>)
* [Typescript 4.3.5](<https://github.com/microsoft/TypeScript/releases/tag/v4.3.5>)
* [Jest 26.6.1](<https://github.com/facebook/jest/releases/tag/v27.0.6>)

**Reglas de negocio:**
* Son usuarios nuevos que quieren publicar solo UNA vacante, por lo tanto deben crear una 
cuenta de usuario de OCC la cual tendrá privilegios de administrador hacía la organización.
* El usuario tendrá que terminar el flujo para poder acceder a la plataforma.
* Las vacantes clásicas creadas y publicadas en este flujo se publican por default con razón social
a excepción que el usuario elija no mostrar nombre de la empresa.
* Las vacantes creadas y publicadas en este flujo de tipo destacada y premium se publican por 
default con nombre comercial a excepción que el usuario elija no mostrar nombre de la empresa.
* En la pantalla donde el usuario abandone el flujo, al volver deberá ser direccionado a la misma 
pantalla donde se quedó.
* En el checkout de FJA solo existe la posibilidad de pagar con tarjeta de crédito o débito y/o 
paypal.
* El correo utilizado en creación de cuenta puede ser igual o diferente en la pantalla datos de 
contacto.
* Precios variables solo está disponible en el flujo de FJA.