---
title: "Aspose::Pdf::LogicalStructure::LinkElement clase"
linktitle: "LinkElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LogicalStructure::LinkElement clase. Representa un elemento de estructura Link en la estructura lógica en C++."
type: docs
weight: 2900
url: /es/cpp/aspose.pdf.logicalstructure/linkelement/
---
## LinkElement class


Representa el elemento de estructura Link en la estructura lógica.

```cpp
class LinkElement : public Aspose::Pdf::LogicalStructure::AnnotationElement,
                    public Aspose::Pdf::LogicalStructure::ITextElement,
                    public Aspose::Pdf::Tagged::IAdjustPosition
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_Hyperlink](./get_hyperlink/)() const | Obtiene o establece [Hyperlink](../../aspose.pdf/hyperlink/) para el elemento Link [Element](../element/). |
| [get_StructureTextState](./get_structuretextstate/)() override | Obtiene el objeto [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) para el elemento actual. |
| [set_Hyperlink](./set_hyperlink/)(const System::SharedPtr\<Aspose::Pdf::Hyperlink\>\&) | Obtiene o establece [Hyperlink](../../aspose.pdf/hyperlink/) para el elemento Link [Element](../element/). |
| [SetText](./settext/)(System::String) override | Añade contenido de texto al elemento de texto actual. |
## Ver también

* Class [AnnotationElement](../annotationelement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
