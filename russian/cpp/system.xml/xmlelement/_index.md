---
title: "System::Xml::XmlElement класс"
linktitle: "XmlElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlElement класс. Представляет элемент в C++."
type: docs
weight: 1700
url: /ru/cpp/system.xml/xmlelement/
---
## XmlElement class


Представляет элемент.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Возвращает значение **bool**, указывающее, имеет ли текущий узел какие‑либо атрибуты. |
| [get_InnerText](./get_innertext/)() override | Возвращает конкатенированные значения узла и всех его дочерних узлов. |
| [get_InnerXml](./get_innerxml/)() override | Возвращает разметку, представляющую только дочерние узлы этого узла. |
| [get_IsEmpty](./get_isempty/)() | Возвращает формат тега элемента. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя текущего узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя узла. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Возвращает URI пространства имён этого узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Возвращает [XmlDocument](../xmldocument/), к которому принадлежит этот узел. |
| [get_Prefix](./get_prefix/)() override | Возвращает префикс пространства имён этого узла. |
| [get_SchemaInfo](./get_schemainfo/)() override | Возвращает набор информации после проверки схемы, который был назначен этому узлу в результате проверки схемы. |
| virtual [GetAttribute](./getattribute/)(String) | Возвращает значение атрибута с указанным именем. |
| virtual [GetAttribute](./getattribute/)(String, String) | Возвращает значение атрибута с указанным локальным именем и URI пространства имён. |
| virtual [GetAttributeNode](./getattributenode/)(String) | Возвращает [XmlAttribute](../xmlattribute/) с указанным именем. |
| virtual [GetAttributeNode](./getattributenode/)(String, String) | Возвращает [XmlAttribute](../xmlattribute/) с указанным локальным именем и URI пространства имён. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Возвращает [XmlNodeList](../xmlnodelist/), содержащий список всех дочерних элементов, соответствующих указанному [XmlElement::get_Name](./get_name/). |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Возвращает [XmlNodeList](../xmlnodelist/), содержащий список всех дочерних элементов, соответствующих указанным значениям [XmlElement::get_LocalName](./get_localname/) и [XmlElement::get_NamespaceURI](./get_namespaceuri/). |
| virtual [HasAttribute](./hasattribute/)(String) | Определяет, имеет ли текущий узел атрибут с указанным именем. |
| virtual [HasAttribute](./hasattribute/)(String, String) | Определяет, имеет ли текущий узел атрибут с указанным локальным именем и URI пространства имён. |
| [RemoveAll](./removeall/)() override | Удаляет все указанные атрибуты и дочерние элементы текущего узла. Атрибуты по умолчанию не удаляются. |
| virtual [RemoveAllAttributes](./removeallattributes/)() | Удаляет все указанные атрибуты из элемента. Атрибуты по умолчанию не удаляются. |
| virtual [RemoveAttribute](./removeattribute/)(String) | Удаляет атрибут по имени. |
| virtual [RemoveAttribute](./removeattribute/)(String, String) | Удаляет атрибут с указанным локальным именем и URI пространства имён. (Если удалённый атрибут имеет значение по умолчанию, оно сразу заменяется). |
| virtual [RemoveAttributeAt](./removeattributeat/)(int32_t) | Удаляет узел атрибута с указанным индексом из элемента. (Если удалённый атрибут имеет значение по умолчанию, оно сразу заменяется). |
| virtual [RemoveAttributeNode](./removeattributenode/)(SharedPtr\<XmlAttribute\>) | Удаляет указанный [XmlAttribute](../xmlattribute/). |
| virtual [RemoveAttributeNode](./removeattributenode/)(String, String) | Удаляет [XmlAttribute](../xmlattribute/), указанный локальным именем и URI пространства имён. (Если удалённый атрибут имеет значение по умолчанию, оно сразу заменяется). |
| [set_InnerText](./set_innertext/)(String) override | Устанавливает конкатенированные значения узла и всех его дочерних элементов. |
| [set_InnerXml](./set_innerxml/)(String) override | Устанавливает разметку, представляющую только дочерние элементы этого узла. |
| [set_IsEmpty](./set_isempty/)(bool) | Устанавливает формат тега элемента. |
| [set_Prefix](./set_prefix/)(String) override | Устанавливает префикс пространства имён этого узла. |
| virtual [SetAttribute](./setattribute/)(String, String) | Устанавливает значение атрибута с указанным именем. |
| virtual [SetAttribute](./setattribute/)(String, String, String) | Устанавливает значение атрибута с указанным локальным именем и URI пространства имён. |
| virtual [SetAttributeNode](./setattributenode/)(SharedPtr\<XmlAttribute\>) | Добавляет указанный [XmlAttribute](../xmlattribute/). |
| virtual [SetAttributeNode](./setattributenode/)(String, String) | Добавляет указанный [XmlAttribute](../xmlattribute/). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних узлов узла в указанный [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет текущий узел в указанный [XmlWriter](../xmlwriter/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
