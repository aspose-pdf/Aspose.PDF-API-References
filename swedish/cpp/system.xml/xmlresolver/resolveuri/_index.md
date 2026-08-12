---
title: "System::Xml::XmlResolver::ResolveUri method"
linktitle: "ResolveUri"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlResolver::ResolveUri method. När den åsidosätts i en avledd klass, löser den den absoluta URI:n från bas- och relativa URI:er i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri method


När den åsidosätts i en avledd klass, löser upp den absoluta URI:n från bas- och relativa URI:er.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | Den bas-URI som används för att lösa upp den relativa URI:n. |
| relativeUri | String | URI:n att lösa upp. URI:n kan vara absolut eller relativ. Om den är absolut ersätter detta värde effektivt **baseUri**‑värdet. Om den är relativ kombineras den med **baseUri** för att skapa en absolut URI. |

### ReturnValue

Den absoluta URI:n eller **nullptr** om den relativa URI:n inte kan lösas upp.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
