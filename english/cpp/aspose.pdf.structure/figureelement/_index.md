---
title: Aspose::Pdf::Structure::FigureElement class
linktitle: FigureElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Structure::FigureElement class. Class representing logical structure figure in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.structure/figureelement/
---
## FigureElement class


Class representing logical structure figure.

```cpp
class FigureElement : public Aspose::Pdf::Structure::Element
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_ActualText](../element/get_actualtext/)() | (Optional; PDF 1.4) [Text](../../aspose.pdf.text/) that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document's contents in support of accessibility to users with disabilities or for other purposes. |
| virtual [get_Alt](../element/get_alt/)() | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document's contents in support of accessibility to users with disabilities or for other purposes. |
| [get_Children](../element/get_children/)() | Gets child elements collection. |
| virtual [get_E](../element/get_e/)() | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| [get_Image](./get_image/)() | Gets the value of figure structure element. |
| virtual [get_Lang](../element/get_lang/)() | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
| [Remove](../element/remove/)() | Remove element. |
| virtual [set_ActualText](../element/set_actualtext/)(System::String) | (Optional; PDF 1.4) [Text](../../aspose.pdf.text/) that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document's contents in support of accessibility to users with disabilities or for other purposes. |
| virtual [set_Alt](../element/set_alt/)(System::String) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document's contents in support of accessibility to users with disabilities or for other purposes. |
| virtual [set_E](../element/set_e/)(System::String) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| virtual [set_Lang](../element/set_lang/)(System::String) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
## See Also

* Class [Element](../element/)
* Namespace [Aspose::Pdf::Structure](../)
* Library [Aspose.PDF for C++](../../)
