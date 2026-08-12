---
title: "Clase Aspose::Pdf::Vector::GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Vector::GraphicElementCollection. Representa la colección de GraphicElement en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.vector/graphicelementcollection/
---
## GraphicElementCollection class


Representa la colección de [GraphicElement](../graphicelement/).

```cpp
class GraphicElementCollection : public System::Collections::Generic::ICollection<System::SharedPtr<GraphicElement>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<GraphicElement\>\&) override | Agrega un nuevo [GraphicElement](../graphicelement/) a la colección. Todos los elementos de la colección deben tener el mismo [GraphicElement::Parent](../). |
| [Clear](./clear/)() override | Limpia la colección. |
| [Contains](./contains/)(const System::SharedPtr\<GraphicElement\>\&) const override | Determina si un elemento está en la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<GraphicElement\>\>, int32_t) override | Copia toda la colección a una Matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos de objeto [GraphicElement](../graphicelement/) realmente contenidos en la colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador para toda la colección. |
| [GraphicElementCollection](./graphicelementcollection/)() | Inicializa la nueva colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el elemento [GraphicElement](../graphicelement/) en el índice especificado. |
| [Remove](./remove/)(const System::SharedPtr\<GraphicElement\>\&) override | Elimina el elemento [GraphicElement](../graphicelement/). |
| [ToString](./tostring/)() const override | Obtiene una representación en cadena de esta colección. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
