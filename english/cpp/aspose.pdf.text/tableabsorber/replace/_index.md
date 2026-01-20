---
title: Aspose::Pdf::Text::TableAbsorber::Replace method
linktitle: Replace
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TableAbsorber::Replace method. Replaces an AbsorbedTable with Table on the page in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber::Replace method


Replaces an [AbsorbedTable](../../absorbedtable/) with [Table](../../../aspose.pdf/table/) on the page.

```cpp
void Aspose::Pdf::Text::TableAbsorber::Replace(System::SharedPtr<Page> page, System::SharedPtr<AbsorbedTable> oldTable, System::SharedPtr<Table> newTable)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | [Pdf](../../../aspose.pdf/) pocument page object. |
| oldTable | System::SharedPtr\<AbsorbedTable\> | [AbsorbedTable](../../absorbedtable/) to be replaced. |
| newTable | System::SharedPtr\<Table\> | [Table](../../../aspose.pdf/table/) to replace old table. |
## Remarks



Please take into account it changes TableList collection. In case removing/replacing tables in loop please use copy of TableList collection. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [AbsorbedTable](../../absorbedtable/)
* Class [Table](../../../aspose.pdf/table/)
* Class [TableAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
