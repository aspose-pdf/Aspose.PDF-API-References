---
title: "Класс System::Xml::XmlNamedNodeMap"
linktitle: "XmlNamedNodeMap"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlNamedNodeMap. Представляет коллекцию узлов, к которым можно получить доступ по имени или индексу в C++."
type: docs
weight: 2200
url: /ru/cpp/system.xml/xmlnamednodemap/
---
## XmlNamedNodeMap class


Представляет коллекцию узлов, к которой можно получить доступ по имени или индексу.

```cpp
class XmlNamedNodeMap : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [begin](./begin/)() const | Возвращает итератор на первый элемент коллекции. |
| [cbegin](./cbegin/)() const | Возвращает итератор на первый элемент коллекции. |
| [cend](./cend/)() const | Возвращает итератор для несуществующего элемента, находящегося за последним элементом коллекции. |
| [end](./end/)() const | Возвращает итератор для несуществующего элемента, находящегося за последним элементом коллекции. |
| virtual [get_Count](./get_count/)() | Возвращает количество узлов в [XmlNamedNodeMap](./). |
| [GetEnumerator](./getenumerator/)() override | Обеспечивает поддержку итерации по коллекции узлов в [XmlNamedNodeMap](./). |
| virtual [GetNamedItem](./getnameditem/)(String) | Получает [XmlNode](../xmlnode/), указанный по имени. |
| virtual [GetNamedItem](./getnameditem/)(String, String) | Получает узел с совпадающими значениями [XmlNode::get_LocalName](../xmlnode/get_localname/) и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [Item](./item/)(int32_t) | Получает узел по указанному индексу в [XmlNamedNodeMap](./). |
| virtual [RemoveNamedItem](./removenameditem/)(String) | Удаляет узел из [XmlNamedNodeMap](./). |
| virtual [RemoveNamedItem](./removenameditem/)(String, String) | Удаляет узел с совпадающими значениями [XmlNode::get_LocalName](../xmlnode/get_localname/) и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) | Добавляет [XmlNode](../xmlnode/), используя его значение [XmlNode::get_Name](../xmlnode/get_name/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [iterator](./iterator/) | Тип итератора. |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
