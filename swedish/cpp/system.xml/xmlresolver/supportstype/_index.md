---
title: "System::Xml::XmlResolver::SupportsType method"
linktitle: "SupportsType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlResolver::SupportsType method. Gör det möjligt för resolvern att returnera typer annat än Stream i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType method


Gör det möjligt för resolvern att returnera typer annat än Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI:n. |
| typ | const TypeInfo\& | Typen att returnera. |

### ReturnValue

**true** if the **type** is supported; otherwise, **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
