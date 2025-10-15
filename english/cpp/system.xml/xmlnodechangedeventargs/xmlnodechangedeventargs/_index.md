---
title: System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs constructor
linktitle: XmlNodeChangedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs constructor. Initializes a new instance of the XmlNodeChangedEventArgs class in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs constructor


Initializes a new instance of the [XmlNodeChangedEventArgs](../) class.

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


| Parameter | Type | Description |
| --- | --- | --- |
| node | const SharedPtr\<XmlNode\>\& | The [XmlNode](../../xmlnode/) that generated the event. |
| oldParent | const SharedPtr\<XmlNode\>\& | The old parent [XmlNode](../../xmlnode/) of the [XmlNode](../../xmlnode/) that generated the event. |
| newParent | const SharedPtr\<XmlNode\>\& | The new parent [XmlNode](../../xmlnode/) of the [XmlNode](../../xmlnode/) that generated the event. |
| oldValue | const String\& | The old value of the [XmlNode](../../xmlnode/) that generated the event. |
| newValue | const String\& | The new value of the [XmlNode](../../xmlnode/) that generated the event. |
| action | XmlNodeChangedAction | The [XmlNodeChangedAction](../../xmlnodechangedaction/). |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
