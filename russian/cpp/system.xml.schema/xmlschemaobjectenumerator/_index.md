---
title: "Класс System::Xml::Schema::XmlSchemaObjectEnumerator"
linktitle: "XmlSchemaObjectEnumerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaObjectEnumerator. Представляет перечислитель для XmlSchemaObjectCollection в C++."
type: docs
weight: 5200
url: /ru/cpp/system.xml.schema/xmlschemaobjectenumerator/
---
## XmlSchemaObjectEnumerator class


Представляет перечислитель для [XmlSchemaObjectCollection](../xmlschemaobjectcollection/).

```cpp
class XmlSchemaObjectEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchemaObject>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Клонирует текущий итератор. |
| [Dispose](./dispose/)() override | Ничего не делает. |
| [get_Current](./get_current/)() const override | Возвращает текущий [XmlSchemaObject](../xmlschemaobject/) в коллекции. |
| [MoveNext](./movenext/)() override | Переходит к следующему элементу в коллекции. |
| [Reset](./reset/)() override | Сбрасывает перечислитель в начало коллекции. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
