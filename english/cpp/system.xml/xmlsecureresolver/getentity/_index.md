---
title: System::Xml::XmlSecureResolver::GetEntity method
linktitle: GetEntity
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlSecureResolver::GetEntity method. Maps a URI to an object that contains the actual resource in C++.'
type: docs
weight: 200
url: /cpp/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity method


Maps a URI to an object that contains the actual resource.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | The URI that is returned from [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) call. |
| role | String | Currently not used. |
| ofObjectToReturn | const TypeInfo\& | The type of object to return. The current version only returns Stream objects. |

### ReturnValue

The stream returned by calling **GetEntity** on the underlying [XmlResolver](../../xmlresolver/). If a type other than Stream is specified, the method returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
