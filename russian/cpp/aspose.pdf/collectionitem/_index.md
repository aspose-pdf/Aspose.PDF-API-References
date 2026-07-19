---
title: "Aspose::Pdf::CollectionItem class"
linktitle: "CollectionItem"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::CollectionItem class. Представляет класс элемента коллекции. Элемент коллекции содержит данные, описанные схемой коллекции в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf/collectionitem/
---
## CollectionItem class


Представляет класс элемента коллекции. Элемент коллекции содержит данные, описанные схемой коллекции.

```cpp
class CollectionItem : public System::Object
```

## Nested classes

* Class [Value](./value/)
## Методы

| Метод | Описание |
| --- | --- |
| [get_AllNames](./get_allnames/)() | Получает коллекцию всех имен значений элементов коллекции. |
| [get_IsEmpty](./get_isempty/)() | Получает значение, указывающее, пустой ли элемент коллекции. |
| [HasName](./hasname/)(const System::String\&) | Проверяет, существует ли указанное имя в элементе коллекции. |
| [TryGetDateTimeValue](./trygetdatetimevalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<System::DateTime\>\>\&) | Пытается получить значение типа DateTime из элемента коллекции по указанному имени. |
| [TryGetDoubleValue](./trygetdoublevalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<double\>\>\&) | Пытается получить значение double для указанного имени из элемента коллекции. |
| [TryGetIntValue](./trygetintvalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<int32_t\>\>\&) | Пытается получить целочисленное значение для указанного имени из элемента коллекции. |
| [TryGetTextValue](./trygettextvalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<System::String\>\>\&) | Пытается получить текстовое значение с указанным именем из элемента коллекции. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
