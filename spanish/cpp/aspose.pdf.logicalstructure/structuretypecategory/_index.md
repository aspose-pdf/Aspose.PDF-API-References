---
title: "Aspose::Pdf::LogicalStructure::StructureTypeCategory clase"
linktitle: "StructureTypeCategory"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LogicalStructure::StructureTypeCategory clase. Representa categorías de tipos de estructura estándar en C++."
type: docs
weight: 5800
url: /es/cpp/aspose.pdf.logicalstructure/structuretypecategory/
---
## StructureTypeCategory class


Representa categorías de tipos de [Structure](../../aspose.pdf.structure/) estándar.

```cpp
class StructureTypeCategory : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [BLSEs](./blses/)() | Los elementos de estructura a nivel de bloque (BLSEs) describen el diseño general del contenido en la página, avanzando en la dirección de progresión de bloque. |
| static [GroupingElements](./groupingelements/)() | Los elementos de agrupación agrupan otros elementos en secuencias o jerarquías, pero no contienen contenido directamente y no tienen efecto directo en el diseño. |
| static [IllustrationElements](./illustrationelements/)() | Los elementos de ilustración son secuencias compactas de contenido, en el orden del contenido de la página, que se consideran objetos unitarios con respecto al diseño de la página. Una ilustración puede tratarse como un BLSE o un ILSE. |
| static [ILSEs](./ilses/)() | Los elementos de estructura a nivel en línea (ILSEs) describen el diseño del contenido dentro de un BLSE, avanzando en la dirección de progresión en línea. |
| static [to_StructureTypeCategory](./to_structuretypecategory/)(const System::String\&) | Realiza una conversión explícita de [System::String](../../system/string/) a [Aspose::Pdf::LogicalStructure::StructureTypeCategory](./). |
| [ToString](./tostring/)() const override | Devuelve una cadena que representa el objeto actual. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
