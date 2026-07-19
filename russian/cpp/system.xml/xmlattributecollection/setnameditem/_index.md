---
title: "System::Xml::XmlAttributeCollection::SetNamedItem method"
linktitle: "SetNamedItem"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlAttributeCollection::SetNamedItem method. Добавляет XmlNode, используя результат XmlNode::get_Name, в C++."
type: docs
weight: 1000
url: /ru/cpp/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem method


Добавляет [XmlNode](../../xmlnode/) используя результат [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | SharedPtr\<XmlNode\> | Узел‑атрибут для хранения в этой коллекции. Позже к узлу можно будет обратиться по его имени. Если узел с таким именем уже присутствует в коллекции, он будет заменён новым; в противном случае узел будет добавлен в конец коллекции. |

### ReturnValue

Если **node** заменяет существующий узел с тем же именем, возвращается старый узел; в противном случае возвращается добавленный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
