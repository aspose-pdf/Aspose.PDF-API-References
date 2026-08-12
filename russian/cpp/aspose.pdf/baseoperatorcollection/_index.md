---
title: "Aspose::Pdf::BaseOperatorCollection класс"
linktitle: "BaseOperatorCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::BaseOperatorCollection. Представляет базовый класс для коллекции операторов в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class


Представляет базовый класс для коллекции операторов.

```cpp
class BaseOperatorCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Operator>>
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Add](./add/)(const System::SharedPtr\<Operator\>\&) | Добавляет новый оператор в коллекцию. |
| virtual [CancelUpdate](./cancelupdate/)() | Отменяет последнее обновление. Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого. |
| virtual [Clear](./clear/)() | Очищает коллекцию. |
| virtual [Contains](./contains/)(const System::SharedPtr\<Operator\>\&) const | Проверяет, существует ли оператор в коллекции. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>, int32_t) | Копирует операторы в список операторов. |
| virtual [get_Count](./get_count/)() const | Получает количество операторов в коллекции. |
| virtual [get_IsFastTextExtractionMode](./get_isfasttextextractionmode/)() const | Указывает, ограничена ли коллекция быстрым извлечением текста. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Возвращает true, если коллекция только для чтения. |
| virtual [GetEnumerator](./getenumerator/)() | Возвращает перечислитель для коллекции. |
| virtual [idx_get](./idx_get/)(int32_t) | Получает оператор по его индексу. |
| virtual [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Operator\>) | Получает оператор по его индексу. |
| virtual [Insert](./insert/)(int32_t, System::SharedPtr\<Operator\>) | Вставляет оператор в коллекцию. |
| virtual [Remove](./remove/)(const System::SharedPtr\<Operator\>\&) | Удаляет оператор из коллекции. |
| virtual [ResumeUpdate](./resumeupdate/)() | Возобновляет обновление документа. Обновляет поток содержимого, если есть ожидающие изменения. |
| virtual [SuppressUpdate](./suppressupdate/)() | Подавляет обновление данных содержимого. Поток содержимого не обновляется, пока не будет вызвано ResumeUpdate. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
