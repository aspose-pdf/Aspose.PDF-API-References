---
title: "FitRExplicitDestination"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que el rectángulo especificado por las coordenadas left, bottom, right y top quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible."
type: docs
weight: 230
url: /es/python-net/aspose.pdf.annotations/fitrexplicitdestination/
---

## FitRExplicitDestination class

Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que el rectángulo especificado por las coordenadas left, bottom, right y top quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible.

El tipo FitRExplicitDestination expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| FitRExplicitDestination(page, left, bottom, right, top) | Inicializa una nueva instancia de la clase FitRExplicitDestination |
| FitRExplicitDestination(document, page_number, left, bottom, right, top) | Inicializa una nueva instancia de la clase FitRExplicitDestination |
| FitRExplicitDestination(page_number, left, bottom, right, top) | Inicializa una nueva instancia de la clase FitRExplicitDestination |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| página | Obtiene el objeto de página de destino |
| page_number | Obtiene el número de página de destino |
| left | Obtiene la coordenada horizontal izquierda del rectángulo visible. |
| bottom | Obtiene la coordenada vertical inferior del rectángulo visible. |
| derecha | Obtiene la coordenada horizontal derecha del rectángulo visible. |
| top | Obtiene la coordenada vertical superior del rectángulo visible. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| create_destination(page, type, values) | Crea instancias de clases descendientes de ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Crea instancias de clases descendientes de ExplicitDestination. |
| create_destination(page_number, type, values) | Crea instancias de clases descendientes de ExplicitDestination. |
| to_string() | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitR 100 200 300 400". |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

