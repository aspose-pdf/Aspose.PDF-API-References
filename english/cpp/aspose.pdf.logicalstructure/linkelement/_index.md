---
title: Aspose::Pdf::LogicalStructure::LinkElement class
linktitle: LinkElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::LinkElement class. Represents Link structure element in logical structure in C++.'
type: docs
weight: 2900
url: /cpp/aspose.pdf.logicalstructure/linkelement/
---
## LinkElement class


Represents Link structure element in logical structure.

```cpp
class LinkElement : public Aspose::Pdf::LogicalStructure::AnnotationElement,
                    public Aspose::Pdf::LogicalStructure::ITextElement,
                    public Aspose::Pdf::Tagged::IAdjustPosition
```

## Methods

| Method | Description |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_Hyperlink](./get_hyperlink/)() const | Gets or Sets [Hyperlink](../../aspose.pdf/hyperlink/) for Link [Element](../element/). |
| [get_StructureTextState](./get_structuretextstate/)() override | Gets [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) object for current element. |
| [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Gets or Sets [Hyperlink](../../aspose.pdf/hyperlink/) for Link [Element](../element/). |
| [SetText](./settext/)(System::String) override | Appends text content to current text element. |
## See Also

* Class [AnnotationElement](../annotationelement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
