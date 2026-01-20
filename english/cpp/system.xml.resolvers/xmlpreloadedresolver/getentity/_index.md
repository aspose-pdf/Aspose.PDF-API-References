---
title: System::Xml::Resolvers::XmlPreloadedResolver::GetEntity method
linktitle: GetEntity
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Resolvers::XmlPreloadedResolver::GetEntity method. Maps a URI to an object that contains the actual resource in C++.'
type: docs
weight: 400
url: /cpp/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity method


Maps a URI to an object that contains the actual resource.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | The URI returned from [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) call. |
| role | String | Currently not used. |
| ofObjectToReturn | const TypeInfo\& | The type of object to return. The [XmlPreloadedResolver](../) supports Stream objects and TextReader objects for URIs that were added as [String](../../../system/string/). If the requested type is not supported by the resolver, an exception will be thrown. Use the XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) method to determine whether a certain **Type** is supported by this resolver. |

### ReturnValue

A Stream or TextReader object that corresponds to the actual source.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
