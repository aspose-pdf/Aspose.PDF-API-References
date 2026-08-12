---
title: "Aspose::Pdf::Text::TableAbsorber::Replace метод"
linktitle: "Заменить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TableAbsorber::Replace метод. Заменяет AbsorbedTable на Table на странице в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber::Replace method


Заменяет [AbsorbedTable](../../absorbedtable/) на [Table](../../../aspose.pdf/table/) на странице.

```cpp
void Aspose::Pdf::Text::TableAbsorber::Replace(const System::SharedPtr<Page> &page, const System::SharedPtr<AbsorbedTable> &oldTable, const System::SharedPtr<Table> &newTable)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| page | const System::SharedPtr\<Page\>\& | [Pdf](../../../aspose.pdf/) объект страницы документа. |
| oldTable | const System::SharedPtr\<AbsorbedTable\>\& | [AbsorbedTable](../../absorbedtable/) для замены. |
| newTable | const System::SharedPtr\<Table\>\& | [Table](../../../aspose.pdf/table/) для замены старой таблицы. |
## Примечания



Пожалуйста, учитывайте, что это изменяет коллекцию TableList. При удалении/замене таблиц в цикле используйте копию коллекции TableList.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [AbsorbedTable](../../absorbedtable/)
* Class [Table](../../../aspose.pdf/table/)
* Class [TableAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
