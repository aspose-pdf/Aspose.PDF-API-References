---
title: "System::Xml::XmlAttributeCollection класс"
linktitle: "XmlAttributeCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlAttributeCollection класс. Представляет собой коллекцию атрибутов, к которым можно получить доступ по имени или индексу в C++."
type: docs
weight: 700
url: /ru/cpp/system.xml/xmlattributecollection/
---
## XmlAttributeCollection class


Представляет коллекцию атрибутов, к которой можно получить доступ по имени или индексу.

```cpp
class XmlAttributeCollection : public System::Xml::XmlNamedNodeMap
```

## Методы

| Метод | Описание |
| --- | --- |
| [Append](./append/)(const SharedPtr\<XmlAttribute\>\&) | Вставляет указанный атрибут как последний узел в коллекцию. |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&, int32_t) | Копирует все объекты [XmlAttribute](../xmlattribute/) из этой коллекции в заданный массив. |
| [idx_get](./idx_get/)(int32_t) | Возвращает атрибут с указанным индексом. |
| [idx_get](./idx_get/)(const String\&) | Возвращает атрибут с указанным именем. |
| [idx_get](./idx_get/)(const String\&, const String\&) | Возвращает атрибут с указанным локальным именем и пространством имён Uniform Resource Identifier (URI). |
| [InsertAfter](./insertafter/)(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) | Вставляет указанный атрибут сразу после указанного атрибута‑ссылки. |
| [InsertBefore](./insertbefore/)(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) | Вставляет указанный атрибут сразу перед указанным атрибутом‑ссылкой. |
| [Prepend](./prepend/)(const SharedPtr\<XmlAttribute\>\&) | Вставляет указанный атрибут как первый узел в коллекцию. |
| [Remove](./remove/)(const SharedPtr\<XmlAttribute\>\&) | Удаляет указанный атрибут из коллекции. |
| [RemoveAll](./removeall/)() | Удаляет все атрибуты из коллекции. |
| [RemoveAt](./removeat/)(int32_t) | Удаляет из коллекции атрибут, соответствующий указанному индексу. |
| [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) override | Добавляет [XmlNode](../xmlnode/) используя результат его [XmlNode::get_Name](../xmlnode/get_name/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlNamedNodeMap](../xmlnamednodemap/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
