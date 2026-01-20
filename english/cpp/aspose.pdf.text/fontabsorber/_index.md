---
title: Aspose::Pdf::Text::FontAbsorber class
linktitle: FontAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontAbsorber class. Represents an absorber object of fonts. Performs search for fonts and provides access to search results via FontAbsorber::Fonts collection in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.text/fontabsorber/
---
## FontAbsorber class


Represents an absorber object of fonts. Performs search for fonts and provides access to search results via [FontAbsorber::Fonts](../) collection.

```cpp
class FontAbsorber : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [FontAbsorber](./fontabsorber/)() | Initializes a new instance of the [FontAbsorber](./) that performs search for fonts of the document. |
| [get_Fonts](./get_fonts/)() const | Gets collection of search occurrences that are presented with [Font](../font/) objects. |
| virtual [Visit](./visit/)(System::SharedPtr\<Document\>, int32_t, int32_t) | Performs search in the specified range of pages of the document. |
| virtual [Visit](./visit/)(System::SharedPtr\<Document\>) | Performs search on the specified document. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
