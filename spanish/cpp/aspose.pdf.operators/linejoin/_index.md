---
title: "Aspose::Pdf::Operators::LineJoin enum"
linktitle: "LineJoin"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Operators::LineJoin enum. El estilo de unión de línea debe especificar la forma que se usará en las esquinas de las rutas que se trazan en C++."
type: docs
weight: 8400
url: /es/cpp/aspose.pdf.operators/linejoin/
---
## LineJoin enum


El estilo de unión de línea debe especificar la forma que se usará en las esquinas de las rutas que se trazan.

```cpp
enum class LineJoin
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| MiterJoin | 0 | Unión en inglete. Los bordes exteriores de los trazos de los dos segmentos se extenderán hasta encontrarse en un ángulo, como en un marco de foto. Si los segmentos se encuentran en un ángulo demasiado agudo según lo define el parámetro de límite de inglete (ver 8.4.3.5, "Miter Limit"), se usará una unión biselada en su lugar. |
| RoundJoin | 1 | Unión redondeada. Se dibujará un arco de círculo con un diámetro igual al ancho de línea alrededor del punto donde se encuentran los dos segmentos, conectando los bordes exteriores de los trazos de los dos segmentos. Esta figura en forma de sector de pastel se rellenará, produciendo una esquina redondeada. |
| BevelJoin | 2 | Unión biselada. Los dos segmentos se terminarán con tapas planas (ver 8.4.3.3, "Line Cap Style") y la muesca resultante más allá de los extremos de los segmentos se rellenará con un triángulo. |

## Ver también

* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
