---
title: System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver constructor
linktitle: XmlPreloadedResolver
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver constructor. Initializes a new instance of the XmlPreloadedResolver class in C++.'
type: docs
weight: 100
url: /cpp/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## See Also

* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class with the specified fallback resolver.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) or your own resolver. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class with the specified fallback resolver and preloaded well-known DTDs.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) or your own resolver. |
| preloadedDtds | XmlKnownDtds | The well-known DTDs that should be prepopulated into the cache. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class with the specified fallback resolver, preloaded well-known DTDs, and URI equality comparer.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) or your own resolver. |
| preloadedDtds | XmlKnownDtds | The well-known DTDs that should be prepopulated into cache. |
| uriComparer | const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\& | The implementation of the IEqualityComparer interface to use when you compare URIs. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class with the specified preloaded well-known DTDs.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


| Parameter | Type | Description |
| --- | --- | --- |
| preloadedDtds | XmlKnownDtds | The well-known DTDs that should be prepopulated into the cache. |

## See Also

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
