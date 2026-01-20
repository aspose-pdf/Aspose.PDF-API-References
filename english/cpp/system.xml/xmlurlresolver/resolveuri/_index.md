---
title: System::Xml::XmlUrlResolver::ResolveUri method
linktitle: ResolveUri
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlUrlResolver::ResolveUri method. Resolves the absolute URI from the base and relative URIs in C++.'
type: docs
weight: 300
url: /cpp/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri method


Resolves the absolute URI from the base and relative URIs.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | The base URI used to resolve the relative URI. |
| relativeUri | String | The URI to resolve. The URI can be absolute or relative. If absolute, this value effectively replaces the **baseUri** value. If relative, it combines with the **baseUri** to make an absolute URI. |

### ReturnValue

The absolute URI, or **nullptr** if the relative URI cannot be resolved.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
