---
title: System::Uri::TryCreate method
linktitle: TryCreate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Uri::TryCreate method. Constructs an Uri abject from the specified base and relative URIs in C++.'
type: docs
weight: 4400
url: /cpp/system/uri/trycreate/
---
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method


Constructs an [Uri](../) abject from the specified base and relative URIs.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | The base URI |
| relativeUri | const SharedPtr\<Uri\>\& | The relative URI that is added to the base URI |
| result | SharedPtr\<Uri\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### ReturnValue

True if the construction succeeded, otherwise - false

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method


Constructs an [Uri](../) abject from the specified [Uri](../) object representing the base URI and the string representation of relative URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | The base URI |
| relativeUri | const String\& | The relative URI that is added to the base URI |
| result | SharedPtr\<Uri\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### ReturnValue

True if the construction succeeded, otherwise - false

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method


Constructs a [Uri](../) object that represents the specified URI; an argument specifies the URI kind.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const String\& | The string URI to be represented by the object being constructed |
| uriKind | UriKind | Specifies the URI kind |
| result | SharedPtr\<Uri\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### ReturnValue

True if the construction succeeded, otherwise - false

## See Also

* Class [String](../../string/)
* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
