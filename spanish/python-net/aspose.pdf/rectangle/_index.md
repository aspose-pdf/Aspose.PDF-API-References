---
title: "Rectángulo"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa un rectángulo."
type: docs
weight: 1320
url: /es/python-net/aspose.pdf/rectangle/
---

## Rectangle class

Clase que representa un rectángulo.

El tipo Rectángulo expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Inicializa una nueva instancia de la clase Rectángulo |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| ancho | Ancho del rectángulo. |
| alto | Altura del rectángulo. |
| llx | Coordenada X de la esquina inferior izquierda. |
| lly | Coordenada Y de la esquina inferior izquierda. |
| urx | Coordenada X de la esquina superior derecha. |
| ury | Coordenada Y de la esquina superior derecha. |
| trivial | Inicializa un rectángulo trivial, es decir, un rectángulo con posición y tamaño cero. |
| is_trivial | Comprueba si el rectángulo es trivial, es decir, tiene tamaño y posición cero. |
| is_empty | Comprueba si el rectángulo está vacío. |
| is_point | Comprueba si el rectángulo es un punto, es decir, LLX es igual a URX y LLY es igual a URY. |
| empty | Rectángulo vacío |
## Métodos
| Nombre | Descripción |
| :- | :- |
| rotate(angle) | Rota el rectángulo por el ángulo especificado. |
| rotate(angle) | Rota el rectángulo por el ángulo especificado. |
| to_rect() | Convierte el rectángulo a una instancia de System.Drawing.Rectangle. Las posiciones y tamaños de punto flotante se truncan. |
| from_rect(src) | Inicializa un nuevo rectángulo a partir de la instancia dada de System.Drawing.Rectangle. |
| parse(value) | Intenta analizar la cadena y extraer de ella los componentes del rectángulo llx, lly, urx, ury. |
| equals(other) | Comprueba si los rectángulos son iguales, es decir, tienen la misma posición y tamaños. |
| near_equals(other, delta) | Comprueba si los rectángulos son casi iguales, es decir, tienen posición y tamaños casi idénticos (hasta delta). |
| intersect(other_rect) | Intersección de rectángulos. |
| join(other_rect) | Une rectángulos. |
| is_intersect(other_rect) | Determina si este rectángulo intersecta con otro rectángulo. |
| contains(point) | Determina si el punto dado está dentro del rectángulo. |
| center() | Devuelve las coordenadas del centro del rectángulo. |
| clone() | Clona el objeto Rectangle. |
| to_points() | Convierte el rectángulo en una matriz de puntos ("QuadPoints"). |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

