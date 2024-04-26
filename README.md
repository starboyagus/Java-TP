# Sistema de Club de Fúbtol

## Integrantes
50412 - Gil, Agustín
<br>
51367 - Gallegos, Nicolás Gabriel

## Enunciado general
<div align="justify">
Un club de fútbol necesita un sistema que le permita:
- Gestionar la venta de entradas a los distintos partidos jugados en sus canchas
- Gestionar la venta de los palcos disponibles en sus canchas.
- Visualizar información relevante para el club mediante listados.

Dentro del sistema, existirán usuarios con diferentes permisos, cada uno con distintos beneficios.
Un usuario puede ser "Invitado", "Administrador" o "Registrado"
- Invitado: puede acceder al sitio web para verlo.
- Registrados: estos se dividen en tres categorías:
    - Regulares: pueden comprar entradas y visitar las secciones de noticias y entrevistas.
    - Socios: tienen los beneficios de los Registrados Regulares + acceso a pre-compra de entradas.
    - VIPs: tienen los beneficios de los Registrados Socios + acceso a compra de palcos.
- Administrador: puede realizar los ABMC de las entidades del sistema.
</div>

## ABCMs / CRUDs
- Simple
    - Usuarios
        <p>Este puede ser  "Invitado",  "Administrador", "Registrado Regular",   "Registrado Socio" o  "Registrado VIP"</p>
    - Canchas
- Dependiente
    - Palcos
    - Tribunas-Ubicaciones
    - Partidos
## Listados
- ### Simple
    -  <b>Listado de partidos futuros</b>
- ### Complejo
    - <b>Usuarios registrados</b>
        <p>Filtros: por rango de fechas</p>
    - <b>Entradas Vendidas</b>
        <p>Filtros: por partido, rango de fechas, por una, por cancha</p>
    - <b>Palcos Vendidos</b>
        <p>Filtros: por rango de fechas, por cancha, por usuario</p>
## Caso de Uso
- ### No-ABMC
    - Crear partido
    - Comprar entrada a partido
- ### Complejo
    - Gestion VIP (Registrarse, Volverse VIP, Comprar Palco)

## Modelo de Datos

![Modelo de Datos](/Sistema_de_Club_de_Futbol/Modelo%20de%20Datos.png)

## Checklist Regularidad

|Requerimiento|2 integrantes|Detalle/Listado de casos incluidos|
|:-|-:|:-|
|ABMC simple|2|Usuario<br>Cancha|
|ABMC dependiente|1|Tribuna-Ubicaciones|
|CU NO-ABMC|1|Crear partido|
|Listado simple|1|Listado de partidos futuros|
|Listado complejo|0|

## Checklist Aprobación Directa

|Requerimiento|2 integrantes|Detalle/Listado de casos incluidos|
|:-|-:|:-|
|ABMC|6|Usuario<br>Cancha<br>Paritdo<br>Palco<br>Tribuna<br>Ubicaciones|
|CU "Complejo"(nivel resumen)|1|Gestion VIP|
|Listado complejo|1|Usuarios registrados|
|Nivel de acceso|2|Regulares<br>Socios|
|Manejo de errores|obligatorio|no requiere detalle|
|requerimiento extra obligatorio|0|
|publicar el sitio|olbigatorio|no requiere detalle|


