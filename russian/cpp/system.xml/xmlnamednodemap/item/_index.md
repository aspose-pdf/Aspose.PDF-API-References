---
title: "System::Xml::XmlNamedNodeMap::Item method"
linktitle: "Элемент"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNamedNodeMap::Item method. Получает узел по указанному индексу в XmlNamedNodeMap в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item method


Получает узел по указанному индексу в [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int32_t | Позиция индекса узла, который нужно получить из [XmlNamedNodeMap](../). Индекс начинается с нуля; поэтому индекс первого узла равен 0, а индекс последнего узла — [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### ReturnValue

Узел [XmlNode](../../xmlnode/) по указанному индексу. Если **index** меньше 0 или больше либо равен значению [XmlNamedNodeMap::get_Count](../get_count/), возвращается **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
