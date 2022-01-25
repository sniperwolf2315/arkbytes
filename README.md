abc
===

ABC es una aplicación ERP para gestionar Clientes, Proveedores, Pedidos, Facturas e Inventario, dirigido a PYMEs

Más información en [http://www.acb-erp.com](http://www.abc-erp.com)

Última release disponible [v0.6.4](https://github.com/arkabytes/abc/releases/download/v0.6.4/abc_v_0_6_4.zip)

Descripción
-----------

ABC ERP
- Aplicación Web ERP para PYMEs
- Gestión de Clientes y Proveedores
- Gestión de Pedidos y Facturación
- Gestión del Inventario y Stock
- Gestión de Tareas y Eventos

Estructura
----------

- admin

    Contiene código de la parte administrativa de la aplicación web

- config

    Contiene ficheros de configuración de la aplicación

- css

    Contiene las hojas de estilo

- iconos

    Contiene el set de iconos utilizado en toda la aplicación

- img

    Contiene las imágenes utilizadas en toda la aplicación

- include

    Contiene librerias propias y externas utilizadas en el proyecto (Ver más abajo LIBRERIAS EXTERNAS UTILIZADAS)

- run

    Contiene los scripts que procesan los formularios web

- sql

    Contiene el backup de la estructura de la Base de Datos (MySQL) utilizada

Requisitos
----------

- Servidor Web Apache
- PHP > 5.2
- MySQL > 5.1
- Driver php-mysqlnd

Instalación
-----------

[Guía de instalación](https://github.com/arkabytes/abc/wiki/Instalaci%C3%B3n-de-ABC-ERP)

Librerías de terceros utilizadas
--------------------------------

- _jQuery v1.7.1_
    
    The jQuery Project
    http://jquery.com

- _jQuery UI v.18.7_

    The jQuery Project
    http://jqueryui.com

- _FancyZoom_

    Script para visualizar imágenes
    http://www.cabel.name/2008/02/fancyzoom-10.html
    
- _FullCalendar_

    http://arshaw.com/fullcalendar/

- _FPDF_

    Librería para la generación de documentos pdf
    http://www.fpdf.org

- _Script para la generación de facturas (se ha utilizado una modificación sobre el original)_

    Autor Xavier Nicolay
    http://www.fpdf.org/en/script/script20.php

- _JQuery Calculator_

    Calculadora inline
    http://keith-wood.name/calculator.html

Autores
-------

    Santiago Faci <santi@arkabytes.com>
