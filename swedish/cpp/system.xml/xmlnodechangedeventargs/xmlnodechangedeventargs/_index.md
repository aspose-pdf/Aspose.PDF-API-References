---
title: "System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs-konstruktor"
linktitle: "XmlNodeChangedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs-konstruktor. Initierar en ny instans av klassen XmlNodeChangedEventArgs i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs constructor


Initierar en ny instans av klassen [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | const SharedPtr\<XmlNode\>\& | Den [XmlNode](../../xmlnode/) som genererade händelsen. |
| oldParent | const SharedPtr\<XmlNode\>\& | Den gamla föräldern [XmlNode](../../xmlnode/) till [XmlNode](../../xmlnode/) som genererade händelsen. |
| newParent | const SharedPtr\<XmlNode\>\& | Den nya föräldern [XmlNode](../../xmlnode/) till [XmlNode](../../xmlnode/) som genererade händelsen. |
| oldValue | const String\& | Det gamla värdet på [XmlNode](../../xmlnode/) som genererade händelsen. |
| newValue | const String\& | Det nya värdet på [XmlNode](../../xmlnode/) som genererade händelsen. |
| action | XmlNodeChangedAction | Den [XmlNodeChangedAction](../../xmlnodechangedaction/). |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
