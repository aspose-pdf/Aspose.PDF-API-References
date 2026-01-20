---
title: System::Xml::Resolvers::XmlPreloadedResolver::SupportsType method
linktitle: SupportsType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Resolvers::XmlPreloadedResolver::SupportsType method. Determines whether the resolver supports other Types than just Stream in C++.'
type: docs
weight: 800
url: /cpp/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType method


Determines whether the resolver supports other Types than just Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | The absolute URI to check. |
| type | const TypeInfo\& | The Type to return. |

### ReturnValue

**true** if the Type is supported; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
