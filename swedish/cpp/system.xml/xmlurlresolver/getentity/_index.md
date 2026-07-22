---
title: "System::Xml::XmlUrlResolver::GetEntity metod"
linktitle: "GetEntity"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlUrlResolver::GetEntity metod. Kartlägger en URI till ett objekt som innehåller den faktiska resursen i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity method


Mappar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI:n som returneras från anropet [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| roll | String | För närvarande används den inte. |
| ofObjectToReturn | const TypeInfo\& | Typen av objekt att returnera. Den aktuella implementationen returnerar endast Stream‑objekt. |

### ReturnValue

Ett Stream‑objekt eller **nullptr** om en annan typ än stream anges.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
