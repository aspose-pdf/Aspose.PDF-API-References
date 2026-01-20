---
title: Aspose::Pdf::Structure::Element class
linktitle: Element
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Structure::Element class. Class representing base element of logical structure in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.structure/element/
---
## Element class


Class representing base element of logical structure.

```cpp
class Element : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_ActualText](./get_actualtext/)() | (Optional; PDF 1.4) [Text](../../aspose.pdf.text/) that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document's contents in support of accessibility to users with disabilities or for other purposes. |
| virtual [get_Alt](./get_alt/)() | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document's contents in support of accessibility to users with disabilities or for other purposes. |
| [get_Children](./get_children/)() | Gets child elements collection. |
| virtual [get_E](./get_e/)() | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| virtual [get_Lang](./get_lang/)() | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
| [Remove](./remove/)() | Remove element. |
| virtual [set_ActualText](./set_actualtext/)(System::String) | (Optional; PDF 1.4) [Text](../../aspose.pdf.text/) that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document's contents in support of accessibility to users with disabilities or for other purposes. |
| virtual [set_Alt](./set_alt/)(System::String) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document's contents in support of accessibility to users with disabilities or for other purposes. |
| virtual [set_E](./set_e/)(System::String) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| virtual [set_Lang](./set_lang/)(System::String) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Structure](../)
* Library [Aspose.PDF for C++](../../)
