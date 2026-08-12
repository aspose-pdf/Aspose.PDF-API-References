---
title: "System::Text::RegularExpressions::CaptureCollection класс"
linktitle: "CaptureCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Text::RegularExpressions::CaptureCollection. Список захватов, выполненных одной захватывающей группой. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.text.regularexpressions/capturecollection/
---
## CaptureCollection class


Список захватов, выполненных одной захватывающей группой. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CaptureCollection : public System::Collections::Generic::List<CapturePtr>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const CapturePtr\&) override | Отключает изменение коллекции. |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Сервисный метод для добавления захвата в коллекцию. |
| [Clear](./clear/)() override | Отключает очистку коллекции. |
| [get_Count](./get_count/)() const override | Возвращает количество захватов. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Помечает коллекцию как только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() const | Помечает коллекцию как несинхронизированную. |
| [idx_get](./idx_get/)(int) const override | [Capture](../capture/) аксессор. |
| [operator[]](./operator[]/)(int) | [Capture](../capture/) аксессор. |
| [operator[]](./operator[]/)(int) const | [Capture](../capture/) аксессор. |
| [Remove](./remove/)(const CapturePtr\&) override | Отключает изменение коллекции. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Base](./base/) | [Base](./base/) тип. |
## См. также

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
