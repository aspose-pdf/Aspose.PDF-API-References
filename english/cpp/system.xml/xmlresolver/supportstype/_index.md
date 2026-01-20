---
title: System::Xml::XmlResolver::SupportsType method
linktitle: SupportsType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlResolver::SupportsType method. Enables the resolver to return types other than Stream in C++.'
type: docs
weight: 400
url: /cpp/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType method


Enables the resolver to return types other than Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | The URI. |
| type | const TypeInfo\& | The type to return. |

### ReturnValue

**true** if the **type** is supported; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
