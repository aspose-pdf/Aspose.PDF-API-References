---
title: "Aspose::Pdf::CollectionItem::TryGetDoubleValue метод"
linktitle: "TryGetDoubleValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::CollectionItem::TryGetDoubleValue метод. Пытается получить значение типа double для указанного имени из элемента коллекции в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf/collectionitem/trygetdoublevalue/
---
## CollectionItem::TryGetDoubleValue method


Пытается получить значение double для указанного имени из элемента коллекции.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetDoubleValue(const System::String &name, System::SharedPtr<CollectionItem::Value<double>> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const System::String\& | Имя значения для получения. |
| value | System::SharedPtr\<CollectionItem::Value\<double\>\>\& | После возврата этого метода содержит значение типа double, связанное с указанным именем, если имя найдено; в противном случае — null. Этот параметр передаётся неинициализированным. |

### ReturnValue

true, если значение успешно получено; в противном случае — false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
