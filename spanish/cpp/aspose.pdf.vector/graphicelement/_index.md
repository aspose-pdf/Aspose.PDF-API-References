---
title: "Aspose::Pdf::Vector::GraphicElement clase"
linktitle: "GraphicElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Vector::GraphicElement clase. Representa la clase base para objetos gráficos en la página en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.vector/graphicelement/
---
## GraphicElement class


Representa la clase base para el objeto gráfico en la página.

```cpp
class GraphicElement : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AddOnPage](./addonpage/)(System::SharedPtr\<Page\>) | Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por la clase [GraphicElement](./). |
| [get_Matrix](./get_matrix/)() const | Obtiene la matriz del elemento gráfico. La matriz se establece cuando se crea el elemento. Cambia cuando se llama a **SetPosition()**. |
| [get_Operators](./get_operators/)() const | Obtiene una colección de operadores que representan el elemento. |
| [get_Parent](./get_parent/)() const | Obtiene el [XFormPlacement](../xformplacement/) actual en el que se encuentra el elemento. |
| virtual [get_Position](./get_position/)() | Obtiene la posición en el espacio de coordenadas actual. Si [Parent](../) no es [null](../) entonces el elemento tiene espacio de coordenadas xForm. |
| virtual [get_Rectangle](./get_rectangle/)() | Obtiene el rectángulo delimitador del [GraphicElement](./). |
| [get_SourcePage](./get_sourcepage/)() const | Obtiene la página de la cual se extrae el elemento gráfico. |
| [Remove](./remove/)() | Elimina el elemento actual de la página. Si hay muchos elementos para eliminar, es mejor usar [Page::DeleteGraphics(GraphicElementCollection)](../). |
| [SaveToSvg](./savetosvg/)() | Convierte el elemento en una única imagen SVG. |
| [SaveToSvg](./savetosvg/)(const System::String\&) | Convierte el elemento en un único archivo de imagen SVG. |
| virtual [set_Position](./set_position/)(System::SharedPtr\<Point\>) | Establece la posición en el espacio de coordenadas actual. Si [Parent](../) no es [null](../), entonces el elemento tiene espacio de coordenadas xForm. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
