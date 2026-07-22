---
title: "System::Xml::Resolvers::XmlPreloadedResolver::GetEntity-metod"
linktitle: "GetEntity"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Resolvers::XmlPreloadedResolver::GetEntity-metod. Kartlägger en URI till ett objekt som innehåller den faktiska resursen i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity method


Mappar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI:n som returneras från anropet [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| roll | String | För närvarande används den inte. |
| ofObjectToReturn | const TypeInfo\& | Typen av objekt att returnera. [XmlPreloadedResolver](../) stöder Stream-objekt och TextReader-objekt för URI:er som lagts till som [String](../../../system/string/). Om den begärda typen inte stöds av resolvern kastas ett undantag. Använd metoden XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) för att avgöra om en viss **Type** stöds av denna resolver. |

### ReturnValue

Ett Stream- eller TextReader-objekt som motsvarar den faktiska källan.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
