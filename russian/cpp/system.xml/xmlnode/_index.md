---
title: "Класс System::Xml::XmlNode"
linktitle: "XmlNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlNode. Представляет отдельный узел XML‑документа в C++."
type: docs
weight: 2500
url: /ru/cpp/system.xml/xmlnode/
---
## XmlNode class


Представляет отдельный узел в XML‑документе.

```cpp
class XmlNode : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                public System::Xml::XPath::IXPathNavigable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) | Добавляет указанный узел в конец списка дочерних узлов этого узла. |
| virtual [Clone](./clone/)() | Создаёт дубликат этого узла. |
| virtual [CloneNode](./clonenode/)(bool) | Создаёт дубликат узла, когда переопределено в производном классе. |
| [CreateNavigator](./createnavigator/)() override | Создаёт XPathNavigator для навигации по этому объекту. |
| virtual [get_Attributes](./get_attributes/)() | Возвращает [XmlAttributeCollection](../xmlattributecollection/), содержащую атрибуты этого узла. |
| virtual [get_BaseURI](./get_baseuri/)() | Возвращает базовый URI текущего узла. |
| virtual [get_ChildNodes](./get_childnodes/)() | Возвращает все дочерние узлы узла. |
| virtual [get_FirstChild](./get_firstchild/)() | Возвращает первый дочерний узел. |
| virtual [get_HasChildNodes](./get_haschildnodes/)() | Возвращает значение, указывающее, имеет ли этот узел дочерние узлы. |
| virtual [get_InnerText](./get_innertext/)() | Возвращает конкатенированные значения узла и всех его дочерних узлов. |
| virtual [get_InnerXml](./get_innerxml/)() | Возвращает разметку, представляющую только дочерние узлы этого узла. |
| virtual [get_IsReadOnly](./get_isreadonly/)() | Возвращает значение, указывающее, является ли узел только для чтения. |
| virtual [get_LastChild](./get_lastchild/)() | Возвращает последний дочерний узел. |
| virtual [get_LocalName](./get_localname/)() | Возвращает локальное имя узла, когда переопределено в производном классе. |
| virtual [get_Name](./get_name/)() | Возвращает квалифицированное имя узла, когда переопределено в производном классе. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | Возвращает URI пространства имён этого узла. |
| virtual [get_NextSibling](./get_nextsibling/)() | Возвращает узел, непосредственно следующий за этим узлом. |
| virtual [get_NodeType](./get_nodetype/)() | Возвращает тип текущего узла, когда переопределено в производном классе. |
| virtual [get_OuterXml](./get_outerxml/)() | Возвращает разметку, содержащую этот узел и все его дочерние узлы. |
| virtual [get_OwnerDocument](./get_ownerdocument/)() | Возвращает [XmlDocument](../xmldocument/), к которому принадлежит этот узел. |
| virtual [get_ParentNode](./get_parentnode/)() | Возвращает родительский узел этого узла (для узлов, которые могут иметь родителя). |
| virtual [get_Prefix](./get_prefix/)() | Возвращает префикс пространства имён этого узла. |
| virtual [get_PreviousSibling](./get_previoussibling/)() | Возвращает узел, непосредственно предшествующий этому узлу. |
| virtual [get_PreviousText](./get_previoustext/)() | Возвращает текстовый узел, который непосредственно предшествует этому узлу. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Возвращает набор информации после проверки схемы, который был назначен этому узлу в результате проверки схемы. |
| virtual [get_Value](./get_value/)() | Возвращает значение узла. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель, который перебирает дочерние узлы текущего узла. |
| virtual [GetNamespaceOfPrefix](./getnamespaceofprefix/)(String) | Ищет ближайшее объявление **xmlns** для заданного префикса, которое находится в области видимости текущего узла, и возвращает URI пространства имён в объявлении. |
| virtual [GetPrefixOfNamespace](./getprefixofnamespace/)(String) | Ищет ближайшее объявление **xmlns** для заданного URI пространства имён, которое находится в области видимости текущего узла, и возвращает префикс, определённый в этом объявлении. |
| virtual [idx_get](./idx_get/)(String) | Возвращает первый дочерний элемент с указанным [XmlNode::get_Name](./get_name/). |
| virtual [idx_get](./idx_get/)(String, String) | Возвращает первый дочерний элемент со значениями [XmlNode::get_LocalName](./get_localname/) и [XmlNode::get_NamespaceURI](./get_namespaceuri/). |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Вставляет указанный узел сразу после указанного узла‑ссылки. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Вставляет указанный узел сразу перед указанным узлом‑ссылкой. |
| virtual [Normalize](./normalize/)() | Помещает все узлы [XmlText](../xmltext/) на полной глубине поддерева под этим [XmlNode](./) в \"нормальную\" форму, где только разметка (то есть теги, комментарии, инструкции обработки, секции CDATA и ссылки на сущности) разделяют узлы [XmlText](../xmltext/), то есть соседних узлов [XmlText](../xmltext/) нет. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) | Добавляет указанный узел в начало списка дочерних узлов этого узла. |
| virtual [RemoveAll](./removeall/)() | Удаляет все дочерние узлы и/или атрибуты текущего узла. |
| virtual [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) | Удаляет указанный дочерний узел. |
| virtual [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Заменяет дочерний узел **oldChild** узлом **newChild**. |
| [SelectNodes](./selectnodes/)(const String\&) | Выбирает список узлов, соответствующих выражению [XPath](../../system.xml.xpath/). |
| [SelectNodes](./selectnodes/)(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) | Выбирает список узлов, соответствующих выражению [XPath](../../system.xml.xpath/). Любые префиксы, найденные в выражении [XPath](../../system.xml.xpath/), разрешаются с помощью предоставленного [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SelectSingleNode](./selectsinglenode/)(const String\&) | Выбирает первый [XmlNode](./), который соответствует выражению [XPath](../../system.xml.xpath/). |
| [SelectSingleNode](./selectsinglenode/)(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) | Выбирает первый [XmlNode](./), который соответствует выражению [XPath](../../system.xml.xpath/). Любые префиксы, найденные в выражении [XPath](../../system.xml.xpath/), разрешаются с помощью предоставленного [XmlNamespaceManager](../xmlnamespacemanager/). |
| virtual [set_InnerText](./set_innertext/)(String) | Устанавливает конкатенированные значения узла и всех его дочерних узлов. |
| virtual [set_InnerXml](./set_innerxml/)(String) | Устанавливает разметку, представляющую только дочерние узлы этого узла. |
| virtual [set_Prefix](./set_prefix/)(String) | Устанавливает префикс пространства имён этого узла. |
| virtual [set_Value](./set_value/)(String) | Устанавливает значение узла. |
| virtual [Supports](./supports/)(String, String) | Проверяет, реализует ли реализация DOM конкретную возможность. |
| virtual [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) | Сохраняет все дочерние узлы узла в указанный [XmlWriter](../xmlwriter/), если переопределено в производном классе. |
| virtual [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) | Сохраняет текущий узел в указанный [XmlWriter](../xmlwriter/), если переопределено в производном классе. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
