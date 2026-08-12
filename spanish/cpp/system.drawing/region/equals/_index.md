---
title: "Método System::Drawing::Region::Equals"
linktitle: "Igual"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Drawing::Region::Equals. Determina si la región especificada es idéntica a la región representada por el objeto actual en la superficie de dibujo especificada en C++."
type: docs
weight: 600
url: /es/cpp/system.drawing/region/equals/
---
## Region::Equals method


Determina si la región especificada es idéntica a la región representada por el objeto actual en la superficie de dibujo especificada.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r | const SharedPtr\<Region\>\& | La región con la que comparar esta región |
| g | const SharedPtr\<Graphics\>\& | Una superficie de dibujo |

### ReturnValue

Verdadero si el interior de la región especificada es idéntico al interior de la región representada por el objeto actual cuando se aplica la transformación asociada al parámetro **g**; de lo contrario, falso

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Class [Region](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
