---
title: "System::Drawing::Drawing2D::CombineMode enum"
linktitle: "CombineMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Drawing2D::CombineMode enum. Especifica cómo se combinan las regiones de recorte en C++."
type: docs
weight: 1400
url: /es/cpp/system.drawing.drawing2d/combinemode/
---
## CombineMode enum


Especifica cómo se combinan las regiones de recorte.

```cpp
enum class CombineMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Reemplazar | 0 | Una región de recorte se reemplaza por otra. |
| Intersect | 1 | Las dos regiones de recorte se combinan tomando su intersección. |
| Unión | 2 | Las dos regiones de recorte se combinan tomando la unión de ambas. |
| Xor | 3 | Las dos regiones de recorte se combinan tomando solo el área encerrada por una u otra región, pero no ambas. |
| Excluir | 4 | Dos regiones de recorte se combinan tomando el área de la primera región que no intersecta con la segunda. |
| Complemento | 5 | Dos regiones de recorte se combinan tomando el área de la segunda región que no intersecta con la primera. |

## Ver también

* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
