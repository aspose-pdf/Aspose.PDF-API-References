---
title: System::Xml::Resolvers::XmlPreloadedResolver::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Resolvers::XmlPreloadedResolver::Add method. Adds a byte array to the XmlPreloadedResolver store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden in C++.'
type: docs
weight: 200
url: /cpp/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) method


Adds a byte array to the [XmlPreloadedResolver](../) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const ArrayPtr\<uint8_t\>\& | A byte array with the data that corresponds to the provided URI. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Adds a byte array to the [XmlPreloadedResolver](../) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const ArrayPtr\<uint8_t\>\& | A byte array with the data that corresponds to the provided URI. |
| offset | int32_t | The offset in the provided byte array where the data starts. |
| count | int32_t | The number of bytes to read from the byte array, starting at the provided offset. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) method


Adds a Stream to the [XmlPreloadedResolver](../) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const SharedPtr\<IO::Stream\>\& | A Stream with the data that corresponds to the provided URI. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) method


Adds a string with preloaded data to the [XmlPreloadedResolver](../) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const String\& | A [String](../../../system/string/) with the data that corresponds to the provided URI. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
