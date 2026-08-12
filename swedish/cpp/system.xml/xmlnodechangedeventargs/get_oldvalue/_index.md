---
title: "System::Xml::XmlNodeChangedEventArgs::get_OldValue-metod"
linktitle: "get_OldValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeChangedEventArgs::get_OldValue-metod. Returnerar det ursprungliga värdet på noden i C++."
type: docs
weight: 700
url: /sv/cpp/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue method


Returnerar det ursprungliga värdet av noden.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### ReturnValue

Det ursprungliga värdet på noden. Denna metod returnerar **nullptr** om noden varken är ett attribut eller en textnod, eller om noden infogas. Om den anropas i ett **XmlDocument::NodeChanging**-event, returnerar **get_OldValue** det aktuella värdet på noden som kommer att ersättas om ändringen lyckas. Om den anropas i ett **XmlDocument::NodeChanged**-event, returnerar **get_OldValue** värdet på noden före ändringen.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
