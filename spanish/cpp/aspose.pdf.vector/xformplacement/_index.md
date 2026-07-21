---
title: "Clase Aspose::Pdf::Vector::XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Vector::XFormPlacement. Representa la ubicación de XForm. Si el XForm se muestra en la página más de una vez, todos los XformPlacements asociados a este XForm tendrán elementos gráficos comunes, pero diferentes estados gráficos en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class


Representa la ubicación de [XForm](../../aspose.pdf/xform/). Si el [XForm](../../aspose.pdf/xform/) se muestra en la página más de una vez, todos los XformPlacements asociados a este [XForm](../../aspose.pdf/xform/) tendrán elementos gráficos comunes, pero diferentes estados gráficos.

```cpp
class XFormPlacement : public Aspose::Pdf::Vector::GraphicElement
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddOnPage](./addonpage/)(System::SharedPtr\<Page\>) override | Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [get_Elements](./get_elements/)() const | Obtiene los elementos gráficos dentro de este [XForm](../../aspose.pdf/xform/). |
| [get_Name](./get_name/)() | Obtiene el nombre del [XForm](../../aspose.pdf/xform/). |
| [get_Rectangle](./get_rectangle/)() override | Obtiene el rectángulo delimitador del [GraphicElement](../graphicelement/). |
| [get_XForm](./get_xform/)() const | Obtiene el [XForm](../../aspose.pdf/xform/) asociado a este [XFormPlacement](./). |
| [set_Position](./set_position/)(System::SharedPtr\<Point\>) override | Establece la posición en el espacio de coordenadas actual. Si [Parent](../) no es [null](../), entonces el elemento tiene espacio de coordenadas xForm. |
## Ver también

* Class [GraphicElement](../graphicelement/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
