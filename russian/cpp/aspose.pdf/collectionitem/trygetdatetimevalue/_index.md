---
title: "Aspose::Pdf::CollectionItem::TryGetDateTimeValue метод"
linktitle: "TryGetDateTimeValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::CollectionItem::TryGetDateTimeValue метод. Пытается получить значение типа DateTime из элемента коллекции по указанному имени в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf/collectionitem/trygetdatetimevalue/
---
## CollectionItem::TryGetDateTimeValue method


Пытается получить значение типа DateTime из элемента коллекции по указанному имени.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetDateTimeValue(const System::String &name, System::SharedPtr<CollectionItem::Value<System::DateTime>> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const System::String\& | Имя значения для получения. |
| value | System::SharedPtr\<CollectionItem::Value\<System::DateTime\>\>\& | Когда этот метод возвращается, содержит значение, связанное с указанным именем, если имя найдено; в противном случае — null. Этот параметр передаётся неинициализированным. |

### ReturnValue

true, если значение, связанное с указанным именем, успешно получено; в противном случае — false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [DateTime](../../../system/datetime/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
