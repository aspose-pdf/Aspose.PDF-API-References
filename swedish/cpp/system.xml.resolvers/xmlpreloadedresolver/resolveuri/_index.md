---
title: "System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri metod"
linktitle: "ResolveUri"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri metod. Löser den absoluta URI:n från bas- och relativa URI:er i C++."
type: docs
weight: 600
url: /sv/cpp/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri method


Löser den absoluta URI:n från bas- och relativa URI:er.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | Den bas-URI som används för att lösa upp den relativa URI:n. |
| relativeUri | String | URI:n att lösa upp. URI:n kan vara absolut eller relativ. Om den är absolut ersätter detta värde effektivt **baseUri**‑värdet. Om den är relativ kombineras den med **baseUri** för att skapa en absolut URI. |

### ReturnValue

Den [Uri](../../../system/uri/) som representerar den absoluta URI:n eller **nullptr** om den relativa URI:n inte kan lösas.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
