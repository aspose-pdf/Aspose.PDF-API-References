---
title: "Aspose::Pdf::CollectionItem::TryGetTextValue метод"
linktitle: "TryGetTextValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::CollectionItem::TryGetTextValue метод. Пытается получить текстовое значение с указанным именем из элемента коллекции в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf/collectionitem/trygettextvalue/
---
## CollectionItem::TryGetTextValue method


Пытается получить текстовое значение с указанным именем из элемента коллекции.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetTextValue(const System::String &name, System::SharedPtr<CollectionItem::Value<System::String>> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const System::String\& | Имя текстового значения. |
| value | System::SharedPtr\<CollectionItem::Value\<System::String\>\>\& | После возврата этого метода содержит текстовое значение, связанное с указанным именем, если имя найдено; в противном случае — null. |

### ReturnValue

true, если текстовое значение с указанным именем найдено; в противном случае — false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
