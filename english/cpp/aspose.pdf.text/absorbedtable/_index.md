---
title: Aspose::Pdf::Text::AbsorbedTable class
linktitle: AbsorbedTable
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::AbsorbedTable class. Represents table that exist on the page in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.text/absorbedtable/
---
## AbsorbedTable class


Represents table that exist on the page.

```cpp
class AbsorbedTable : public Aspose::Pdf::Text::ITableElement,
                      public System::IComparable<System::SharedPtr<AbsorbedTable>>
```

## Methods

| Method | Description |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<AbsorbedTable\>) override | Compares the current [AbsorbedTable](./) object with another [AbsorbedTable](./) object and returns an integer that indicates whether the current object precedes, follows, or occurs in the same position in the sort order as the other object. |
| [get_PageNum](./get_pagenum/)() const | Gets number of the page containing this table. |
| [get_Rectangle](./get_rectangle/)() override | Gets rectangle that describes position of the table on page. |
| [get_RowList](./get_rowlist/)() | Gets readonly IList containing rows of the table. |
## See Also

* Class [ITableElement](../itableelement/)
* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
