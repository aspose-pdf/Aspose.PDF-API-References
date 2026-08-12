---
title: "System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver конструктор"
linktitle: "XmlPreloadedResolver"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver конструктор. Инициализирует новый экземпляр класса XmlPreloadedResolver на C++."
type: docs
weight: 100
url: /ru/cpp/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() constructor


Инициализирует новый экземпляр класса [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## См. также

* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) constructor


Инициализирует новый экземпляр класса [XmlPreloadedResolver](../) с указанным резервным резольвером.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) или ваш собственный резольвер. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) constructor


Инициализирует новый экземпляр класса [XmlPreloadedResolver](../) с указанным резервным резольвером и предзагруженными известными DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) или ваш собственный резольвер. |
| preloadedDtds | XmlKnownDtds | Известные DTD, которые должны быть предварительно заполнены в кэш. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) constructor


Инициализирует новый экземпляр класса [XmlPreloadedResolver](../) с указанным резервным резольвером, предзагруженными известными DTD и сравнивателем равенства URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fallbackResolver | const SharedPtr\<XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) или ваш собственный резольвер. |
| preloadedDtds | XmlKnownDtds | Известные DTD, которые должны быть предварительно заполнены в кэш. |
| uriComparer | const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\& | Реализация интерфейса IEqualityComparer, используемая при сравнении URI. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) constructor


Инициализирует новый экземпляр класса [XmlPreloadedResolver](../) с указанными предзагруженными известными DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| preloadedDtds | XmlKnownDtds | Известные DTD, которые должны быть предварительно заполнены в кэш. |

## См. также

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
