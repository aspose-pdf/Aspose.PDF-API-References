---
title: "Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination método"
linktitle: "CreateDestination"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination método. Crea un destino a la ubicación especificada de la página considerando la rotación de la página si es necesario en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.annotations/xyzexplicitdestination/createdestination/
---
## XYZExplicitDestination::CreateDestination method


Cree el destino a la ubicación especificada de la página considerando la rotación de la página si es necesario.

```cpp
static System::SharedPtr<XYZExplicitDestination> Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination(const System::SharedPtr<Aspose::Pdf::Page> &page, double left, double top, double zoom, bool considerRotation)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\\<Aspose::Pdf::Page\\>\\& | Página de destino. |
| left | double | [Izquierda](../../../aspose.pdf/left/) posición en la página. |
| superior | double | Posición superior en la página. |
| zoom | double | Factor de zoom (0 para predeterminado). |
| considerRotation | bool | Si es verdadero, la posición se recalculará según la rotación de la página. |

### ReturnValue

Objeto de destino.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XYZExplicitDestination](../)
* Class [Page](../../../aspose.pdf/page/)
* Class [XYZExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
