---
title: Aspose::Pdf::LogicalStructure::MCRElement class
linktitle: MCRElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::MCRElement class. Represents marked-content reference object in logical structure in C++.'
type: docs
weight: 3500
url: /cpp/aspose.pdf.logicalstructure/mcrelement/
---
## MCRElement class


Represents marked-content reference object in logical structure.

```cpp
class MCRElement : public Aspose::Pdf::LogicalStructure::Element
```

## Methods

| Method | Description |
| --- | --- |
| [get_MCID](./get_mcid/)() | Gets MCID of marked-content reference object. |
| [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) override | Bind a structure element to the content stream BDC operator. |
| [Tag](./tag/)(System::SharedPtr\<XForm\>) override | Bind a structure element to the content stream [XForm](../../aspose.pdf/xform/). |
| [Tag](./tag/)(System::SharedPtr\<XImage\>) override | Bind a structure element to the [XImage](../../aspose.pdf/ximage/). |
| [Tag](./tag/)(System::SharedPtr\<Artifact\>) override | Bind a structure element to the [Artifact](../../aspose.pdf/artifact/). |
| [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) override | Bind a structure element to the Annotation. |
| [ToString](./tostring/)() const override | Returns a string that represents the current object. |
## See Also

* Class [Element](../element/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
