---
title: "System::Xml::XmlSecureResolver::GetEntity method"
linktitle: "GetEntity"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlSecureResolver::GetEntity method. Mappar en URI till ett objekt som innehåller den faktiska resursen i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity method


Mappar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI:n som returneras från [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) anropet. |
| roll | String | För närvarande används den inte. |
| ofObjectToReturn | const TypeInfo\& | Typen av objekt att returnera. Den aktuella versionen returnerar endast Stream-objekt. |

### ReturnValue

Strömmen som returneras genom att anropa **GetEntity** på den underliggande [XmlResolver](../../xmlresolver/). Om en annan typ än Stream anges, returnerar metoden **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
