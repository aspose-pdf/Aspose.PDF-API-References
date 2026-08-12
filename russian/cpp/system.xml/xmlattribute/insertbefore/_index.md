---
title: "System::Xml::XmlAttribute::InsertBefore метод"
linktitle: "InsertBefore"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlAttribute::InsertBefore метод. Вставляет указанный узел непосредственно перед указанным узлом‑ссылкой в C++."
type: docs
weight: 1500
url: /ru/cpp/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore method


Вставляет указанный узел сразу перед указанным узлом‑ссылкой.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | Элемент [XmlNode](../../xmlnode/) для вставки. |
| refChild | SharedPtr\<XmlNode\> | Элемент [XmlNode](../../xmlnode/), который является опорным узлом. **newChild** размещается перед этим узлом. |

### ReturnValue

Вставленный [XmlNode](../../xmlnode/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
