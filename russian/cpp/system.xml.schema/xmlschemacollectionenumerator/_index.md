---
title: "System::Xml::Schema::XmlSchemaCollectionEnumerator class"
linktitle: "XmlSchemaCollectionEnumerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaCollectionEnumerator class. Поддерживает простую итерацию по коллекции. Этот класс не может быть унаследован в C++."
type: docs
weight: 1600
url: /ru/cpp/system.xml.schema/xmlschemacollectionenumerator/
---
## XmlSchemaCollectionEnumerator class


Поддерживает простую итерацию по коллекции. Этот класс не может быть унаследован.

```cpp
class XmlSchemaCollectionEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Клонирует текущий итератор. |
| [Dispose](./dispose/)() override | Ничего не делает. |
| [get_Current](./get_current/)() const override | Возвращает текущий [XmlSchema](../xmlschema/) в коллекции. |
| [MoveNext](./movenext/)() override | Перемещает перечислитель к следующей схеме в коллекции. |
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
