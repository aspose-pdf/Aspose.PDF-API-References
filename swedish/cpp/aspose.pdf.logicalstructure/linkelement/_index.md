---
title: "Aspose::Pdf::LogicalStructure::LinkElement klass"
linktitle: "LinkElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::LinkElement klass. Representerar länkelement i logisk struktur i C++."
type: docs
weight: 2900
url: /sv/cpp/aspose.pdf.logicalstructure/linkelement/
---
## LinkElement class


Representerar Link‑strukturelement i logisk struktur.

```cpp
class LinkElement : public Aspose::Pdf::LogicalStructure::AnnotationElement,
                    public Aspose::Pdf::LogicalStructure::ITextElement,
                    public Aspose::Pdf::Tagged::IAdjustPosition
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_Hyperlink](./get_hyperlink/)() const | Hämtar eller anger [Hyperlink](../../aspose.pdf/hyperlink/) för Link [Element](../element/). |
| [get_StructureTextState](./get_structuretextstate/)() override | Hämtar [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) objekt för aktuellt element. |
| [set_Hyperlink](./set_hyperlink/)(const System::SharedPtr\<Aspose::Pdf::Hyperlink\>\&) | Hämtar eller anger [Hyperlink](../../aspose.pdf/hyperlink/) för Link [Element](../element/). |
| [SetText](./settext/)(System::String) override | Lägger till textinnehåll till aktuellt textelement. |
## Se även

* Class [AnnotationElement](../annotationelement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
