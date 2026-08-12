---
title: "Класс Aspose::Pdf::OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::OperatorCollection. Класс представляет собой коллекцию операторов в C++."
type: docs
weight: 12100
url: /ru/cpp/aspose.pdf/operatorcollection/
---
## OperatorCollection class


Класс представляет коллекцию операторов.

```cpp
class OperatorCollection : public Aspose::Pdf::BaseOperatorCollection,
                           public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) | Принимает объект‑посетитель [IOperatorSelector](../ioperatorselector/) для обработки операторов. |
| [Add](./add/)(const System::SharedPtr\<Operator\>\&) override | Добавляет новый оператор в коллекцию. |
| [Add](./add/)(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Добавляет операторы в конец операторов содержимого. |
| [Add](./add/)(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) | Добавляет в коллекцию все операторы из другой коллекции. |
| [CancelUpdate](./cancelupdate/)() override | Отменяет последнее обновление. Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого. |
| [Clear](./clear/)() override | Удаляет все операторы из списка. |
| [Contains](./contains/)(const System::SharedPtr\<Operator\>\&) const override | Возвращает true, если коллекция содержит указанный оператор. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>, int32_t) override | Копирует операторы в список операторов. |
| [Delete](./delete/)(int32_t) | Удаляет оператор из коллекции. |
| [Delete](./delete/)(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Удаляет операторы из коллекции. |
| [Delete](./delete/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Удаляет операторы из коллекции. |
| [Dispose](./dispose/)() override | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [get_Count](./get_count/)() const override | Получает количество операторов в коллекции. |
| [get_IsFastTextExtractionMode](./get_isfasttextextractionmode/)() const override | Указывает, ограничена ли коллекция быстрым извлечением текста. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для коллекции. |
| [idx_get](./idx_get/)(int32_t) override | Получает оператор по его индексу. |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Operator\>) override | Получает оператор по его индексу. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<Operator\>) override | Вставляет оператор в коллекцию. |
| [Insert](./insert/)(int32_t, const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Вставляет операторы в указанную позицию. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Вставляет операторы в указанную позицию. |
| [Remove](./remove/)(const System::SharedPtr\<Operator\>\&) override | Удаляет оператор из коллекции. |
| [Replace](./replace/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Заменяет операторы в коллекции другими операторами. |
| [ResumeUpdate](./resumeupdate/)(bool) | Возобновляет обновление документа. Обновляет поток содержимого, если есть ожидающие изменения. Помечает все операторы как "изменённые", если параметр invalidate установлен в true. |
| [ResumeUpdate](./resumeupdate/)() override | Возобновляет обновление документа. Обновляет поток содержимого, если есть ожидающие изменения. |
| [SuppressUpdate](./suppressupdate/)() override | Подавляет обновление данных содержимого. Поток содержимого не обновляется, пока не будет вызвано ResumeUpdate. |
| [ToString](./tostring/)() const override | Возвращает текстовое представление оператора. |
## См. также

* Class [BaseOperatorCollection](../baseoperatorcollection/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
