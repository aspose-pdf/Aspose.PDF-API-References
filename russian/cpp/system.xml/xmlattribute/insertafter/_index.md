---
title: "System::Xml::XmlAttribute::InsertAfter метод"
linktitle: "InsertAfter"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlAttribute::InsertAfter. Вставляет указанный узел сразу после указанного узла‑ссылки в C++."
type: docs
weight: 1400
url: /ru/cpp/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter method


Вставляет указанный узел сразу после указанного узла‑ссылки.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | Элемент [XmlNode](../../xmlnode/) для вставки. |
| refChild | SharedPtr\<XmlNode\> | Элемент [XmlNode](../../xmlnode/), являющийся узлом‑ссылкой. **newChild** размещается после **refChild**. |

### ReturnValue

Вставленный [XmlNode](../../xmlnode/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
