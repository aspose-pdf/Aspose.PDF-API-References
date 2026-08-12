---
title: "System::Xml::XmlNamedNodeMap::SetNamedItem метод"
linktitle: "SetNamedItem"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNamedNodeMap::SetNamedItem метод. Добавляет XmlNode, используя его значение XmlNode::get_Name в C++."
type: docs
weight: 1000
url: /ru/cpp/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem method


Добавляет [XmlNode](../../xmlnode/) используя его значение [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| node | SharedPtr\<XmlNode\> | Объект [XmlNode](../../xmlnode/) для хранения в [XmlNamedNodeMap](../). Если узел с таким именем уже присутствует в карте, он заменяется новым. |

### ReturnValue

Если **node** заменяет существующий узел с тем же именем, возвращается старый узел; в противном случае возвращается **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
