---
title: "Aspose::Pdf::CollectionItem::TryGetIntValue метод"
linktitle: "TryGetIntValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::CollectionItem::TryGetIntValue метод. Пытается получить целочисленное значение для указанного имени из элемента коллекции в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf/collectionitem/trygetintvalue/
---
## CollectionItem::TryGetIntValue method


Пытается получить целочисленное значение для указанного имени из элемента коллекции.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetIntValue(const System::String &name, System::SharedPtr<CollectionItem::Value<int32_t>> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const System::String\& | Имя значения для получения. |
| value | System::SharedPtr\<CollectionItem::Value\<int32_t\>\>\& | После возврата этого метода содержит значение, связанное с указанным именем, если имя найдено; в противном случае — null. |

### ReturnValue

true, если значение, связанное с указанным именем, найдено; в противном случае — false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
