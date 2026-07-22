---
title: "Aspose::Pdf::Vector::GraphicElementCollection class"
linktitle: "GraphicElementCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Vector::GraphicElementCollection class. Representerar GraphicElement-samling i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.vector/graphicelementcollection/
---
## GraphicElementCollection class


Representerar [GraphicElement](../graphicelement/) samling.

```cpp
class GraphicElementCollection : public System::Collections::Generic::ICollection<System::SharedPtr<GraphicElement>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<GraphicElement\>\&) override | Lägger till ett nytt [GraphicElement](../graphicelement/) i samlingen. Alla objekt i samlingen måste ha samma [GraphicElement::Parent](../). |
| [Clear](./clear/)() override | Rensar samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<GraphicElement\>\&) const override | Bestämmer om ett element finns i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<GraphicElement\>\>, int32_t) override | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [get_Count](./get_count/)() const override | Hämtar antalet [GraphicElement](../graphicelement/) objekt som faktiskt finns i samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för hela samlingen. |
| [GraphicElementCollection](./graphicelementcollection/)() | Initierar den nya samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar [GraphicElement](../graphicelement/) elementet på det angivna indexet. |
| [Remove](./remove/)(const System::SharedPtr\<GraphicElement\>\&) override | Tar bort [GraphicElement](../graphicelement/) elementet. |
| [ToString](./tostring/)() const override | Hämtar en strängrepresentation av denna samling. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
