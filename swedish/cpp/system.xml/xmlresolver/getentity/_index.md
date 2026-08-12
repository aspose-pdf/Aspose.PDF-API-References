---
title: "System::Xml::XmlResolver::GetEntity method"
linktitle: "GetEntity"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlResolver::GetEntity method. När den åsidosätts i en avledd klass, mappar en URI till ett objekt som innehåller den faktiska resursen i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity method


När den åsidosätts i en avledd klass, mappar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI:n som returneras från [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) anropet. |
| roll | String | För närvarande används den inte. |
| ofObjectToReturn | const TypeInfo\& | Typen av objekt att returnera. Den aktuella versionen returnerar endast Stream-objekt. |

### ReturnValue

Ett Stream‑objekt eller **nullptr** om en annan typ än stream anges.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
