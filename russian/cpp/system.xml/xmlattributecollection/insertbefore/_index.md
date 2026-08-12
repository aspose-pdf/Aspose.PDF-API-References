---
title: "System::Xml::XmlAttributeCollection::InsertBefore метод"
linktitle: "InsertBefore"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlAttributeCollection::InsertBefore метод. Вставляет указанный атрибут непосредственно перед указанным ссылочным атрибутом в C++."
type: docs
weight: 500
url: /ru/cpp/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore method


Вставляет указанный атрибут сразу перед указанным атрибутом‑ссылкой.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newNode | const SharedPtr\<XmlAttribute\>\& | Атрибут для вставки. |
| refNode | const SharedPtr\<XmlAttribute\>\& | Справочный атрибут. **newNode** размещается перед **refNode**. |

### ReturnValue

[XmlAttribute](../../xmlattribute/) для вставки в коллекцию.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
