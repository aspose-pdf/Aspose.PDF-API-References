---
title: "Метод Aspose::Pdf::PageCollection::IndexOf"
linktitle: "IndexOf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::PageCollection::IndexOf. Возвращает индекс указанной страницы в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf/pagecollection/indexof/
---
## PageCollection::IndexOf method


Возвращает индекс указанной страницы.

```cpp
int32_t Aspose::Pdf::PageCollection::IndexOf(const System::SharedPtr<Page> &entity) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| entity | const System::SharedPtr\<Page\>\& | Объект [Page](../../page/). Номера страниц начинаются с 1. |

### ReturnValue

Индекс страницы в коллекции.
## Примечания


Номера страниц начинаются с 1. Возвращает 0, если коллекция не содержит страницу.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
