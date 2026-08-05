---
title: "XYZExplicitDestination"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un destino explícito que muestra la página con las coordenadas (izquierda, superior) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, superior o zoom indica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo."
type: docs
weight: 880
url: /es/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Representa un destino explícito que muestra la página con las coordenadas (izquierda, superior) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, superior o zoom indica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo.

El tipo XYZExplicitDestination expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | Inicializa una nueva instancia de la clase XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | Inicializa una nueva instancia de la clase XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | Inicializa una nueva instancia de la clase XYZExplicitDestination |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| página | Obtiene el objeto de página de destino |
| page_number | Obtiene el número de página de destino |
| left | Obtiene la coordenada horizontal izquierda de la esquina superior izquierda de la ventana. |
| top | Obtiene la coordenada vertical superior de la esquina superior izquierda de la ventana. |
| zoom | Obtiene el factor de zoom. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Crear destino a la ubicación especificada de la página considerando la rotación de la página si es necesario. |
| create_destination(page, type, values) | Crea instancias de clases descendientes de ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Crea instancias de clases descendientes de ExplicitDestination. |
| create_destination(page_number, type, values) | Crea instancias de clases descendientes de ExplicitDestination. |
| create_destination_to_upper_left_corner(page, zoom) | Crear destino a la esquina superior izquierda de la página especificada. |
| create_destination_to_upper_left_corner(page) | Crear destino a la esquina superior izquierda de la página especificada. |
| to_string() | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 XYZ 100 200 3". |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

