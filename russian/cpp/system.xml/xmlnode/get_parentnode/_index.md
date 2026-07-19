---
title: "System::Xml::XmlNode::get_ParentNode метод"
linktitle: "get_ParentNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNode::get_ParentNode метод. Возвращает родительский узел для данного узла (для узлов, которые могут иметь родителей) в C++."
type: docs
weight: 2100
url: /ru/cpp/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode method


Возвращает родительский узел этого узла (для узлов, которые могут иметь родителя).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### ReturnValue

Этот [XmlNode](../) является родителем текущего узла.
## Примечания



Если узел только что создан и ещё не добавлен в дерево, или если он был удалён из дерева, родитель равен **nullptr**. Для всех остальных узлов возвращаемое значение зависит от [XmlNode::get_NodeType](../get_nodetype/) узла. Следующая таблица описывает возможные возвращаемые значения для метода **get_NodeType**. |||
|-|-|
| NodeType | Возвращаемое значение ParentNode |
| Attribute, Document, DocumentFragment, Entity, Notation | Возвращает nullptr; эти узлы не имеют родителей. |
| CDATA | Возвращает элемент или ссылку на сущность, содержащие секцию CDATA. |
| Comment | Возвращает элемент, ссылку на сущность, тип документа или документ, содержащий комментарий. |
| DocumentType | Возвращает узел документа. |
| Элемент | Возвращает родительский узел элемента. Если элемент является корневым узлом в дереве, родителем является узел документа. |
| EntityReference | Возвращает элемент, атрибут или ссылку на сущность, содержащую ссылку на сущность. |
| ProcessingInstruction | Возвращает документ, элемент, тип документа или ссылку на сущность, содержащие инструкцию обработки. |
| Text | Возвращает родительский элемент, атрибут или ссылку на сущность, содержащие текстовый узел. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
