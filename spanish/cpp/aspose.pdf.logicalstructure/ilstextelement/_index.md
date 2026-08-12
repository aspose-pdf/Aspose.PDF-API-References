---
title: "Clase Aspose::Pdf::LogicalStructure::ILSTextElement"
linktitle: "ILSTextElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LogicalStructure::ILSTextElement. Representa una clase base para los elementos de estructura de texto a nivel inline en la estructura lógica en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.pdf.logicalstructure/ilstextelement/
---
## ILSTextElement class


Representa una clase base para elementos de estructura de texto a nivel en línea en la estructura lógica.

```cpp
class ILSTextElement : public Aspose::Pdf::LogicalStructure::ILSElement,
                       public Aspose::Pdf::LogicalStructure::ITextElement,
                       public Aspose::Pdf::Tagged::IAdjustPosition
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_StructureTextState](./get_structuretextstate/)() override | Obtiene el objeto [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) para el elemento actual. |
| [SetText](./settext/)(System::String) override | Añade contenido de texto al elemento de texto actual. |
## Ver también

* Class [ILSElement](../ilselement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
