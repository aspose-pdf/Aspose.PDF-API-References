---
title: "Класс System::Xml::XmlEntity"
linktitle: "XmlEntity"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlEntity. Представляет объявление сущности, например <!ENTITY...> в C++."
type: docs
weight: 1800
url: /ru/cpp/system.xml/xmlentity/
---
## XmlEntity class


Представляет объявление сущности, например **<!ENTITY... >**.

```cpp
class XmlEntity : public System::Xml::XmlNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. Узлы сущностей нельзя клонировать. Вызов этого метода для объекта [XmlEntity](./) вызывает исключение. |
| [get_BaseURI](./get_baseuri/)() override | Возвращает базовый Uniform Resource Identifier (URI) текущего узла. |
| [get_InnerText](./get_innertext/)() override | Возвращает объединённые значения узла сущности и всех его дочерних элементов. |
| [get_InnerXml](./get_innerxml/)() override | Возвращает разметку, представляющую дочерние элементы этого узла. |
| [get_IsReadOnly](./get_isreadonly/)() override | Возвращает значение, указывающее, является ли узел только для чтения. |
| [get_LocalName](./get_localname/)() override | Возвращает имя узла без префикса пространства имён. |
| [get_Name](./get_name/)() override | Возвращает имя узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип узла. |
| [get_NotationName](./get_notationname/)() | Возвращает имя необязательного атрибута NDATA в объявлении сущности. |
| [get_OuterXml](./get_outerxml/)() override | Возвращает разметку, представляющую этот узел и все его дочерние элементы. |
| [get_PublicId](./get_publicid/)() | Возвращает значение публичного идентификатора в объявлении сущности. |
| [get_SystemId](./get_systemid/)() | Возвращает значение системного идентификатора в объявлении сущности. |
| [set_InnerText](./set_innertext/)(String) override | Устанавливает объединённые значения узла сущности и всех его дочерних элементов. |
| [set_InnerXml](./set_innerxml/)(String) override | Устанавливает разметку, представляющую дочерние элементы этого узла. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних элементов узла в указанный [XmlWriter](../xmlwriter/). Для узлов [XmlEntity](./) этот метод не оказывает никакого эффекта. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел в указанный [XmlWriter](../xmlwriter/). Для узлов [XmlEntity](./) этот метод не оказывает никакого эффекта. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
