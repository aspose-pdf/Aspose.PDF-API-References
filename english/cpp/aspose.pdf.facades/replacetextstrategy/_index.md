---
title: Aspose::Pdf::Facades::ReplaceTextStrategy class
linktitle: ReplaceTextStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::ReplaceTextStrategy class. This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed in C++.'
type: docs
weight: 3200
url: /cpp/aspose.pdf.facades/replacetextstrategy/
---
## ReplaceTextStrategy class


This class contains parameters which define [PdfContentEditor](../pdfcontenteditor/) behavior when ReplaceText operation is performed.

```cpp
class ReplaceTextStrategy : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsRegularExpressionUsed](./get_isregularexpressionused/)() const | If false, string to find is a simple text. If true, string to find is regular expression. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [get_ReplaceScope](./get_replacescope/)() const | Scope of the replacement operation (replace first occurence or replace all occurences). |
| [ReplaceTextStrategy](./replacetextstrategy/)() |  |
| [set_IsRegularExpressionUsed](./set_isregularexpressionused/)(bool) | If false, string to find is a simple text. If true, string to find is regular expression. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(ReplaceTextStrategy::NoCharacterAction) | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [set_ReplaceScope](./set_replacescope/)(ReplaceTextStrategy::Scope) | Scope of the replacement operation (replace first occurence or replace all occurences). |
## See Also

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
