---
title: System::Xml::XmlResolver::GetEntity method
linktitle: GetEntity
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlResolver::GetEntity method. When overridden in a derived class, maps a URI to an object that contains the actual resource in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity method


When overridden in a derived class, maps a URI to an object that contains the actual resource.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | The URI returned from [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) call. |
| role | String | Currently not used. |
| ofObjectToReturn | const TypeInfo\& | The type of object to return. The current version only returns Stream objects. |

### ReturnValue

A stream object or **nullptr** if a type other than stream is specified.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
