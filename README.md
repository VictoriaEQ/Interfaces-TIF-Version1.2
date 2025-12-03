# Interfaces-TIF-Version1.2

# CFP 8 - ESPECIALIZACIÓN EN PROGRAMACIÓN WEB
# MÓDULO: INTERFACES GRÁFICAS

## PROYECTO - INTERFAZ PARA ADMINISTRACIÓN DE PRODUCTOS/CLIENTES/FACTURAS DE UNA ARTÍSTICA

- BACKEND - JPA SPRING BOOT - CAPAS MODELO/REPOSITORY/SERVICE/CONTROLLER 

- FRONTEND - VISTAS REALIZADAS MEDIANTE THYMELEAF Y FRONTEND BÁSICO (MEDIANTE JS FETCH)

### INICIO DE LA APLICACIÓN
> INDEX.THML ESTÁ DESARROLLADO CON THYMELEAF POR LO QUE DEBE 'DESPLEGARSE' MEDIANTE localhost:8080 EN EL NAVEGADOR.
> PREVIAMENTE, DEBE CREARSE LA BASE DE DATOS (ADICIONADA AL TREE DEL PROYECTO) Y EJECUTAR RUN SOBRE EL ARCHIVO APPLICATION

### LAS INTERFACES EN SÍ, EN ÉSTE PUNTO DEL DESARROLLO DE LA APLICACIÓN, ESTÁN PENSADAS PARA EL ADMINISTRADOR DE LA ARTÍSICA.
> LOGIN - admin - 1234

## -- ELEMENTOS QUE FALTAN DESARROLLAR PARA LA VERSIÓN 1.3 --
- Pulir FrontEnd (estilos y visualización general de la aplicación)
- Adicionar JS Axios en el FrontEnd para facturas.html
- Manejo de la entidad Detalle_Facturas en facturas.html
- Manejo del login del Administrador mediante Spring Security - NIVEL MEDIO - (dado que en este momento los datos se encuentran harcodeados y se maneja el login mediante JS)

- En éste punto, la arista de Security se manejará de la siguiente forma:
> Login vía formulario (/login)
> Usuario “admin” con contraseña hardcodeada en memoria
> Rutas /admin/** protegidas
> Logout y redirección a login


## -- ELEMENTOS QUE FALTAN DESARROLLAR PARA LA VERSIÓN 2.1 --
- En el sector de 'Tienda Virtual', realizar consumo de API externa de Mercado Pago
- Adicionar capa DTO para mejor manejo de los objetos y la correcta implementación de la API externa
- Pulir la capa Security, para utilizar BCrypt + Manejo de Usuarios/Roles/Permisos mediante BDs - NIVEL AVANZADO -
