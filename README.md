# Proyecto de Diagramas de Base de Datos - Empresa de Transporte de Encomiendas

## Descripción del Proyecto

Este proyecto tiene como objetivo crear una serie de diagramas de base de datos (físicos, lógicos y relacionales) para una empresa de transporte de encomiendas. Los diagramas están diseñados para facilitar la comprensión y gestión de las relaciones entre las distintas entidades de la empresa, tales como clientes, encomiendas, rutas, vehículos y empleados.

La base de datos está estructurada para manejar las operaciones y datos esenciales que necesita la empresa para realizar un seguimiento efectivo de sus encomiendas y actividades logísticas.

## Tipos de Diagramas

### 1. Diagrama Lógico
El diagrama lógico muestra las relaciones abstractas entre las distintas entidades de la base de datos. Este diagrama no incluye detalles técnicos como claves primarias, pero se enfoca en los procesos comerciales y cómo interactúan entre sí.
![Texto alternativo](../img/DIAGRAMALOG.drawio.png)


### 2. Diagrama Relacional
El diagrama relacional establece las relaciones entre las tablas físicas, mostrando cómo las entidades están conectadas a través de claves foráneas. En este diagrama se incluyen las claves primarias y las relaciones entre las tablas.
![Texto alternativo](../img/DIAGRAMARELACI.drawio.png)


### 3. Diagrama Físico
El diagrama físico muestra la estructura de la base de datos a nivel de implementación, con detalles sobre las tablas, columnas y tipos de datos. Este diagrama está diseñado para ser implementado en un sistema de gestión de bases de datos (DBMS).
![Texto alternativo](../img/DIAGRAMAFIS.drawio.png)

## Objetivos del Proyecto

- **Optimización de Logística**: Facilitar el seguimiento de las encomiendas y optimizar las rutas de transporte.
- **Mejor Gestión de Recursos**: Gestionar la disponibilidad de vehículos y empleados para asignarlos eficientemente a las rutas.
- **Transparencia en el Proceso**: Garantizar un registro claro de todas las encomiendas enviadas y entregadas, con un seguimiento continuo de su estado.

## Implementación de la Base de Datos

### Requisitos Previos
- **Sistema de Gestión de Bases de Datos (DBMS)**: SQL Server, MySQL, PostgreSQL o similar.
- **Software de Diagramas**: Herramientas como Lucidchart, draw.io o Microsoft Visio para crear los diagramas.
- **Conocimiento de SQL**: Para la implementación y gestión de las tablas en el DBMS.

### Pasos para Implementar
1. Clona o descarga este repositorio.
2. Crea las tablas basadas en el diagrama físico en tu DBMS.
3. Implementa las relaciones entre las tablas como se describe en el diagrama relacional.
4. Utiliza el diagrama lógico para revisar las relaciones de negocio y asegurarte de que las entidades están correctamente representadas.
5. Verifica la base de datos para asegurar que los datos se almacenan correctamente y las relaciones funcionan según lo esperado.

## Licencia

Este proyecto está licenciado bajo la MIT License.
