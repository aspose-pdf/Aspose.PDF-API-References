---
title: "System::Xml::Schema::XmlSchemaObjectCollection класс"
linktitle: "XmlSchemaObjectCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaObjectCollection класс. Коллекция XmlSchemaObjects в C++."
type: docs
weight: 5100
url: /ru/cpp/system.xml.schema/xmlschemaobjectcollection/
---
## XmlSchemaObjectCollection class


Коллекция XmlSchemaObjects.

```cpp
class XmlSchemaObjectCollection : public System::Collections::CollectionBase<SharedPtr<System::Xml::Schema::XmlSchemaObject>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const SharedPtr\<XmlSchemaObject\>\&) | Добавляет [XmlSchemaObject](../xmlschemaobject/) в [XmlSchemaObjectCollection](./). |
| [Contains](./contains/)(const SharedPtr\<XmlSchemaObject\>\&) | Указывает, находится ли указанный [XmlSchemaObject](../xmlschemaobject/) в [XmlSchemaObjectCollection](./). |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchemaObject\>\>\&, int32_t) | Копирует все XmlSchemaObjects из коллекции в заданный массив, начиная с указанного индекса. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для перебора XmlSchemaObjects, содержащихся в [XmlSchemaObjectCollection](./). |
| virtual [idx_get](./idx_get/)(int32_t) | Возвращает [XmlSchemaObject](../xmlschemaobject/) по указанному индексу. |
| virtual [idx_set](./idx_set/)(int32_t, SharedPtr\<XmlSchemaObject\>) | Устанавливает [XmlSchemaObject](../xmlschemaobject/) по указанному индексу. |
| [IndexOf](./indexof/)(const SharedPtr\<XmlSchemaObject\>\&) | Возвращает индекс в коллекции, соответствующий указанному [XmlSchemaObject](../xmlschemaobject/). |
| [Insert](./insert/)(int32_t, const SharedPtr\<XmlSchemaObject\>\&) | Вставляет [XmlSchemaObject](../xmlschemaobject/) в [XmlSchemaObjectCollection](./). |
| [Remove](./remove/)(const SharedPtr\<XmlSchemaObject\>\&) | Удаляет [XmlSchemaObject](../xmlschemaobject/) из [XmlSchemaObjectCollection](./). |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Устанавливает n‑й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| [XmlSchemaObjectCollection](./xmlschemaobjectcollection/)() | Инициализирует новый экземпляр класса [XmlSchemaObjectCollection](./). |
| [XmlSchemaObjectCollection](./xmlschemaobjectcollection/)(const SharedPtr\<XmlSchemaObject\>\&) | Инициализирует новый экземпляр класса [XmlSchemaObjectCollection](./), принимающий [XmlSchemaObject](../xmlschemaobject/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [CollectionBase](../../system.collections/collectionbase/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
