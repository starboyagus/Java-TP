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
    - Regulares: pueden comprar entradas y visitar las secciones de noticias y entrevistas
    - Socios: tienen los beneficios de los Registrados Regulares + acceso a pre-compra de entradas
    - VIPs: tienen los beneficios de los Registrados Socios + acceso a compra de palcos
- Administrador: puede realizar los ABMC de las entidades del sistema
</div>

## ABCMs / CRUDs
- Simple
    - Usuarios
        <p>Este puede ser  "Invitado",  "Administrador", "Registrado Regular",   "Registrado Socio" o  "Registrado VIP"</p>
    - Canchas
    - Partidos
- Dependiente
    - Palcos
    - Tribunas
    - Ubicaciones
## Listados
- ### Simple
    -  <b>Disponibilidad de aciones en las canchas</b>
- ### Complejo
    - <b>Usuarios registrados</b>
        <p>Filtros: por rango de as</p>
    - <b>Partidos registrados</b>
        <p>Filtros: por rango de as, por resultado, por ha, por rival</p>
    - <b>Entradas Vendidas</b>
        <p>Filtros: por partido, rango de fechas, por una, por cancha</p>
    - <b>Palcos Vendidos</b>
        <p>Filtros: por rango de as, por cancha, por /p>
## Caso de Uso:
- ### No-ABMC
    - Comprar entrada a partido
    - Comprar palco
- ### Complejo
    - Gestion VIP (Registrarse, Volverse VIP, Comprar Palco)

## Modelo de Datos

![Modelo de Datos](/Sistema_de_Club_de_Futbol/Modelo%20de%20Datos.png)