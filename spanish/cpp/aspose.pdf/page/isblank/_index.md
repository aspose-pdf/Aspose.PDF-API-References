---
title: "Aspose::Pdf::Page::IsBlank método"
linktitle: "IsBlank"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Page::IsBlank método. Obtiene la bandera que indica si la página está en blanco o no en C++."
type: docs
weight: 4800
url: /es/cpp/aspose.pdf/page/isblank/
---
## Page::IsBlank method


Obtiene la bandera que indica si la página está en blanco o no.

```cpp
bool Aspose::Pdf::Page::IsBlank(double fillThresholdFactor)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillThresholdFactor | double | El valor del umbral de relleno que gestiona la sensibilidad de la detección. Debe estar en el rango [0..1). |

### ReturnValue

True - si la página está en blanco; de lo contrario, false.
## Observaciones



Para determinar si una página está vacía o no, se calcula la proporción del espacio rellenado respecto al espacio total de la página. Esta proporción se compara con el parámetro fillThresholdFactor y, si es menor, la página se considera vacía.
## Ver también

* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
