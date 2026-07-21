---
title: "System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver constructor"
linktitle: "XmlPreloadedResolver"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver constructor. Inicializa una nueva instancia de la clase XmlPreloadedResolver en C++."
type: docs
weight: 100
url: /es/cpp/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() constructor


Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## Ver también

* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) constructor


Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../) con el resolvedor de respaldo especificado.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) o tu propio resolvedor. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) constructor


Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../) con el resolvedor de respaldo especificado y los DTD bien conocidos precargados.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) o tu propio resolvedor. |
| preloadedDtds | XmlKnownDtds | Los DTD bien conocidos que deben pre-poblarse en la caché. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) constructor


Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../) con el resolvedor de respaldo especificado, DTD bien conocidos precargados y comparador de igualdad de URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) o tu propio resolvedor. |
| preloadedDtds | XmlKnownDtds | Los DTD bien conocidos que deben pre-poblarse en la caché. |
| uriComparer | const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\& | La implementación de la interfaz IEqualityComparer a usar cuando compares URIs. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) constructor


Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../) con los DTD bien conocidos precargados especificados.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| preloadedDtds | XmlKnownDtds | Los DTD bien conocidos que deben pre-poblarse en la caché. |

## Ver también

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
