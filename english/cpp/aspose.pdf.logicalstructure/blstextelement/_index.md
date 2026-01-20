---
title: Aspose::Pdf::LogicalStructure::BLSTextElement class
linktitle: BLSTextElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::BLSTextElement class. Represents a base class for block-level text structure elements in logical structure in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.logicalstructure/blstextelement/
---
## BLSTextElement class


Represents a base class for block-level text structure elements in logical structure.

```cpp
class BLSTextElement : public Aspose::Pdf::LogicalStructure::BLSElement,
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

* Class [BLSElement](../blselement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
