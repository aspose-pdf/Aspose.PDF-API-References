---
title: "Класс System::Xml::XmlAttribute"
linktitle: "XmlAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlAttribute. Представляет атрибут. Допустимые и значения по умолчанию для атрибута определены в определении типа документа (DTD) или схеме в C++."
type: docs
weight: 600
url: /ru/cpp/system.xml/xmlattribute/
---
## XmlAttribute class


Представляет атрибут. Допустимые и значения по умолчанию для атрибута определены в определении типа документа (DTD) или схеме.

```cpp
class XmlAttribute : public System::Xml::XmlNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) override | Добавляет указанный узел в конец списка дочерних узлов этого узла. |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| [get_BaseURI](./get_baseuri/)() override | Возвращает базовый Унифицированный идентификатор ресурса (URI) узла. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя узла. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Возвращает URI пространства имён этого узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Возвращает [XmlDocument](../xmldocument/), к которому принадлежит этот узел. |
| virtual [get_OwnerElement](./get_ownerelement/)() | Возвращает [XmlElement](../xmlelement/), к которому принадлежит атрибут. |
| [get_Prefix](./get_prefix/)() override | Возвращает префикс пространства имён этого узла. |
| [get_SchemaInfo](./get_schemainfo/)() override | Возвращает post-schema-validation-infoset, который был назначен этому узлу в результате проверки схемы. |
| virtual [get_Specified](./get_specified/)() | Возвращает значение, указывающее, было ли значение атрибута явно установлено. |
| [get_Value](./get_value/)() override | Возвращает значение узла. |
| [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Вставляет указанный узел сразу после указанного узла‑ссылки. |
| [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Вставляет указанный узел сразу перед указанным узлом‑ссылкой. |
| [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) override | Добавляет указанный узел в начало списка дочерних узлов этого узла. |
| [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) override | Удаляет указанный дочерний узел. |
| [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Заменяет указанный дочерний узел новым указанным дочерним узлом. |
| [set_InnerText](./set_innertext/)(String) override | Устанавливает конкатенированные значения узла и всех его дочерних элементов. |
| [set_InnerXml](./set_innerxml/)(String) override | Устанавливает значение атрибута. |
| [set_Prefix](./set_prefix/)(String) override | Устанавливает префикс пространства имён этого узла. |
| [set_Value](./set_value/)(String) override | Устанавливает значение узла. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних узлов узла в указанный [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел в указанный [XmlWriter](../xmlwriter/). |
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
