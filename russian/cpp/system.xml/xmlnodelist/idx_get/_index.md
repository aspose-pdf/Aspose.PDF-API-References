---
title: "System::Xml::XmlNodeList::idx_get метод"
linktitle: "idx_get"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeList::idx_get метод. Возвращает узел по заданному индексу в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get method


Возвращает узел по указанному индексу.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int32_t | Индекс, начинающийся с нуля, в списке узлов. |

### ReturnValue

Элемент [XmlNode](../../xmlnode/) с указанным индексом в коллекции. Если индекс больше или равен количеству узлов в списке, возвращается **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeList](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
