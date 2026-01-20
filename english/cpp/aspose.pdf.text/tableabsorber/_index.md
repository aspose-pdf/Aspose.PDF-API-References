---
title: Aspose::Pdf::Text::TableAbsorber class
linktitle: TableAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TableAbsorber class. Represents an absorber object of table elements. Performs search and provides access to search results via TableAbsorber::TableList collection in C++.'
type: docs
weight: 3300
url: /cpp/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class


Represents an absorber object of table elements. Performs search and provides access to search results via [TableAbsorber::TableList](../) collection.

```cpp
class TableAbsorber : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_TableList](./get_tablelist/)() | Returns readonly IList containing tables that were found. |
| virtual [get_TextSearchOptions](./get_textsearchoptions/)() | Gets text search options. |
| [get_UseFlowEngine](./get_useflowengine/)() const |  |
| [Remove](./remove/)(System::SharedPtr\<AbsorbedTable\>) | Removes an [AbsorbedTable](../absorbedtable/) from the page. |
| [Replace](./replace/)(System::SharedPtr\<Page\>, System::SharedPtr\<AbsorbedTable\>, System::SharedPtr\<Table\>) | Replaces an [AbsorbedTable](../absorbedtable/) with [Table](../../aspose.pdf/table/) on the page. |
| virtual [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Sets text search options. |
| [set_UseFlowEngine](./set_useflowengine/)(bool) |  |
| [TableAbsorber](./tableabsorber/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Initializes a new instance of the [TableAbsorber](./) with text search options. |
| [TableAbsorber](./tableabsorber/)() | Initializes a new instance of the [TableAbsorber](./). |
| virtual [Visit](./visit/)(System::SharedPtr\<Page\>) | Extracts tables on the specified page. |
| [Visit](./visit/)(System::SharedPtr\<Document\>) | Extracts tables in the specified document. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
