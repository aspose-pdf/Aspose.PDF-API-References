---
title: System::Xml::XmlSecureResolver::ResolveUri method
linktitle: ResolveUri
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlSecureResolver::ResolveUri method. Resolves the absolute URI from the base and relative URIs by calling ResolveUri on the underlying XmlResolver in C++.'
type: docs
weight: 300
url: /cpp/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri method


Resolves the absolute URI from the base and relative URIs by calling **ResolveUri** on the underlying [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | The base URI used to resolve the relative URI. |
| relativeUri | String | The URI to resolve. The URI can be absolute or relative. If absolute, this value effectively replaces the **baseUri** value. If relative, it combines with the **baseUri** to make an absolute URI. |

### ReturnValue

The absolute URI or **nullptr** if the relative URI cannot be resolved (returned by calling **ResolveUri** on the underlying [XmlResolver](../../xmlresolver/)).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
