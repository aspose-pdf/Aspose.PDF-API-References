---
title: "System::Xml::XmlNodeChangedEventArgs::get_NewValue-metod"
linktitle: "get_NewValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeChangedEventArgs::get_NewValue-metod. Returnerar det nya värdet på noden i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue method


Returnerar det nya värdet av noden.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### ReturnValue

Det nya värdet på noden. Denna metod returnerar **nullptr** om noden varken är ett attribut eller en textnod, eller om noden tas bort. Om den anropas i ett **XmlDocument::NodeChanging**-event, returnerar **get_NewValue** värdet på noden om ändringen lyckas. Om den anropas i ett **XmlDocument::NodeChanged**-event, returnerar **get_NewValue** det aktuella värdet på noden.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
