---
title: "System::Uri::TryCreate method"
linktitle: "TryCreate"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Uri::TryCreate method. Skapar ett Uri-objekt från den angivna bas- och relativa URI:n i C++."
type: docs
weight: 4400
url: /sv/cpp/system/uri/trycreate/
---
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method


Skapar ett [Uri](../)-objekt från den angivna bas- och relativa URI:n.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | Bas-URI:n |
| relativeUri | const SharedPtr\<Uri\>\& | Den relativa URI:n som läggs till bas-URI:n |
| result | SharedPtr\<Uri\>\& | Utdataargumentet som, om konstruktionen lyckas, pekar på det nykonstruerade [Uri](../)-objektet vid metodens återgång |

### ReturnValue

Sant om konstruktionen lyckades, annars - falskt

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method


Skapar ett [Uri](../)-objekt från det angivna [Uri](../)-objektet som representerar bas-URI:n och den strängrepresentation av den relativa URI:n.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | Bas-URI:n |
| relativeUri | const String\& | Den relativa URI:n som läggs till bas-URI:n |
| result | SharedPtr\<Uri\>\& | Utdataargumentet som, om konstruktionen lyckas, pekar på det nykonstruerade [Uri](../)-objektet vid metodens återgång |

### ReturnValue

Sant om konstruktionen lyckades, annars - falskt

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method


Skapar ett [Uri](../)-objekt som representerar den angivna URI:n; ett argument anger URI-typen.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriString | const String\& | Sträng-URI:n som ska representeras av objektet som konstrueras |
| uriKind | UriKind | Anger URI-typen |
| result | SharedPtr\<Uri\>\& | Utdataargumentet som, om konstruktionen lyckas, pekar på det nykonstruerade [Uri](../)-objektet vid metodens återgång |

### ReturnValue

Sant om konstruktionen lyckades, annars - falskt

## Se även

* Class [String](../../string/)
* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
