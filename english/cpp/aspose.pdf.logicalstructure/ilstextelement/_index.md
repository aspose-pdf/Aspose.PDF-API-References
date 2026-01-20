---
title: Aspose::Pdf::LogicalStructure::ILSTextElement class
linktitle: ILSTextElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::ILSTextElement class. Represents a base class for inline-level text structure elements in logical structure in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf.logicalstructure/ilstextelement/
---
## ILSTextElement class


Represents a base class for inline-level text structure elements in logical structure.

```cpp
class ILSTextElement : public Aspose::Pdf::LogicalStructure::ILSElement,
                       public Aspose::Pdf::LogicalStructure::ITextElement,
                       public Aspose::Pdf::Tagged::IAdjustPosition
```

## Methods

| Method | Description |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_StructureTextState](./get_structuretextstate/)() override | Gets [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) object for current element. |
| [SetText](./settext/)(System::String) override | Appends text content to current text element. |
## See Also

* Class [ILSElement](../ilselement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
