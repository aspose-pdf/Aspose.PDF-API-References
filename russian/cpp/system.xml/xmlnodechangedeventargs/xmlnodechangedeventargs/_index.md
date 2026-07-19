---
title: "System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs конструктор"
linktitle: "XmlNodeChangedEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs конструктор. Инициализирует новый экземпляр класса XmlNodeChangedEventArgs в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs constructor


Инициализирует новый экземпляр класса [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| node | const SharedPtr\<XmlNode\>\& | [XmlNode](../../xmlnode/), который сгенерировал событие. |
| oldParent | const SharedPtr\<XmlNode\>\& | Старый родительский [XmlNode](../../xmlnode/) узла [XmlNode](../../xmlnode/), который сгенерировал событие. |
| newParent | const SharedPtr\<XmlNode\>\& | Новый родительский [XmlNode](../../xmlnode/) узла [XmlNode](../../xmlnode/), который сгенерировал событие. |
| oldValue | const String\& | Старое значение [XmlNode](../../xmlnode/), который сгенерировал событие. |
| newValue | const String\& | Новое значение [XmlNode](../../xmlnode/), который сгенерировал событие. |
| action | XmlNodeChangedAction | [XmlNodeChangedAction](../../xmlnodechangedaction/). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
