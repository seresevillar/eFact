# eFact

e.FACT es el servicio de factura electrónica de las administraciones públicas catalanas para la recepción de las facturas electrónicas (e-facturas) por parte de sus proveedores. En este sentido, el servicio e.FACT ni genera ni hace la gestión contable de las facturas pues de eso se encargan el programa de creación de facturas electrónicas que utilice el proveedor y el programa de gestión contable que utilice la administración destinataria, respectivamente .
Este repositorio pretende ir recopilando poco a poco la nueva documentación relacionada con eFACT conforme ésta es vaya actualizando.

## Formato factura-e 

Conforme a la Ley 25/2013, de 27 de diciembre, de impulso de la factura electrónica y creación del registro  contable de facturas en el Sector Público, las facturas que se remitan a las Administraciones Públicas serán electrónicas y se ajustarán al formato estructurado de factura electrónica Facturae versión 3.2.x con firma electrónica XAdES. 
Por tanto, el formato admitido por la plataforma es Facturae, concretamente las versiones : 3.2,  3.2.1 y 3.2.2.  
Tiene más información sobre dicho formato en: 
https://www.facturae.gob.es/formato/Paginas/version-3-2.aspx

## Flujo de vida de una factura

Los estados que recogen el ciclo de vida de las facturas remitidas debe ser tramitado en base a lo solicitado para el PGE en : BOE A - 2014 -10660 
El siguiente cuadro muestra el flujo de vida natural de una factura enviada por el proveedor al servicio eFACT:
![imagen](https://user-images.githubusercontent.com/92558339/137429130-f198ce69-b91e-4855-8a78-fbaaae2c0259.png)

Durante el proceso de registro y aprobación de la factura se puede producir el rechazo de la factura , bien por problemas de forma o contenido en la factura. En ese momento la factura pasara a estado Rechazada

![imagen](https://user-images.githubusercontent.com/92558339/137429165-21a3ba3e-eb99-4f62-9e60-160fe7f2d4c1.png)

El flujo de anulación   (*) permite al proveedor solicitar la Anulación de la factura . Requiere la aprobación o rechazo por parte del receptor de esta anulación para que sea efectiva. Se recoge en los siguientes estados: 

![imagen](https://user-images.githubusercontent.com/92558339/137429196-2bcd5ef5-1202-4345-98fd-1b645446590b.png)

# Documentación para integradores

En este apartado podéis encontrar la guía de integración via WS para los diferentes servicios web proporcionados por eFact:

[Integración WS para proveedores de facturas](/ws-proveedores/README.md)

# Enlaces de interés

A continuación podéis encontrar una serie de enlaces a sitios de interés:

[Portal de soporte de eFact](https://www.aoc.cat/portal-suport/efact-empreses-base-coneixement/)

[Relación de cambios en la documentación](/CHANGELOG.md)
