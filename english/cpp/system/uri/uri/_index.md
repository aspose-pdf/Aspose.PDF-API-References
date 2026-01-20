---
title: System::Uri::Uri constructor
linktitle: Uri
second_title: Aspose.PDF for C++ API Reference
description: 'System::Uri::Uri constructor. Constructs an Uri abject from the specified base and relative URIs in C++.'
type: docs
weight: 100
url: /cpp/system/uri/uri/
---
## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) constructor


Constructs an [Uri](../) abject from the specified base and relative URIs.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | The base URI |
| relativeUri | const SharedPtr\<Uri\>\& | The relative URI that is added to the base URI |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) constructor


Constructs an [Uri](../) abject from the specified base and relative URIs.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | The base URI |
| relativeUri | const String\& | The relative URI that is added to the base URI |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) constructor


Constructs an [Uri](../) abject from the specified [Uri](../) object representing the base URI and the string representation of relative URI; an argument specifies if the URI should be escaped.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```


| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | The base URI |
| relativeUri | const String\& | The relative URI that is added to the base URI |
| dontEscape | bool | Specifies if the URI should not be escaped |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::Uri(const String\&) constructor


Constructs a [Uri](../) object that represents the specified URI.

```cpp
System::Uri::Uri(const String &uriString)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const String\& | The string URI to be represented by the object being constructed |

## See Also

* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::Uri(const String\&, bool) constructor


Constructs a [Uri](../) object that represents the specified URI; an argument specifies if the URI should be escaped.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const String\& | The string URI to be represented by the object being constructed |
| dontEscape | bool | Specifies if the URI should not be escaped |

## See Also

* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::Uri(const String\&, UriKind) constructor


Constructs a [Uri](../) object that represents the specified URI; an argument specifies the URI kind.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const String\& | The string URI to be represented by the object being constructed |
| uriKind | UriKind | Specifies the URI kind |

## See Also

* Class [String](../../string/)
* Enum [UriKind](../../urikind/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
