---
title: System::Xml::XmlUrlResolver::GetEntity method
linktitle: GetEntity
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlUrlResolver::GetEntity method. Maps a URI to an object that contains the actual resource in C++.'
type: docs
weight: 200
url: /cpp/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity method


Maps a URI to an object that contains the actual resource.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | The URI returned from [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) call. |
| role | String | Currently not used. |
| ofObjectToReturn | const TypeInfo\& | The type of object to return. The current implementation only returns Stream objects. |

### ReturnValue

A stream object or **nullptr** if a type other than stream is specified.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
