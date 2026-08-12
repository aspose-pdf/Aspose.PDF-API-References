---
title: "Método Aspose::Pdf::Page::AddGraphics"
linktitle: "AddGraphics"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Page::AddGraphics. Añade gráficos a la página. Funciona más rápido que añadir elementos uno a uno con el método GraphicElement::AddOnPage(Page) en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/page/addgraphics/
---
## Page::AddGraphics method


Agrega gráficos a la página. Funciona más rápido que agregar elementos uno por uno con el método [GraphicElement::AddOnPage(Page)](../).

```cpp
void Aspose::Pdf::Page::AddGraphics(const System::SharedPtr<Aspose::Pdf::Vector::GraphicElementCollection> &elements, const System::SharedPtr<Aspose::Pdf::Rectangle> &rectangle=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elementos | const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\& | Colección de gráficos. |
|  | rectangle | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Los elementos se agregarán a la página si está |
GraphicElement::Position


está dentro del área del rectángulo. Si el rectángulo es nulo, se agregarán todos los elementos gráficos |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicElementCollection](../../../aspose.pdf.vector/graphicelementcollection/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
