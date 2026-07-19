---
title: "System::Xml::XmlAttributeCollection::InsertAfter method"
linktitle: "InsertAfter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlAttributeCollection::InsertAfter method. Вставляет указанный атрибут сразу после указанного эталонного атрибута в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter method


Вставляет указанный атрибут сразу после указанного атрибута‑ссылки.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newNode | const SharedPtr\<XmlAttribute\>\& | Атрибут для вставки. |
| refNode | const SharedPtr\<XmlAttribute\>\& | Эталонный атрибут. **newNode** размещается после **refNode**. |

### ReturnValue

[XmlAttribute](../../xmlattribute/) для вставки в коллекцию.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
