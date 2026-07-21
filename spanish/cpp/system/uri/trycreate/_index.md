---
title: "System::Uri::TryCreate método"
linktitle: "TryCreate"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Uri::TryCreate método. Construye un objeto Uri a partir de los URIs base y relativos especificados en C++."
type: docs
weight: 4400
url: /es/cpp/system/uri/trycreate/
---
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method


Construye un [Uri](../) objeto a partir de la base y los URIs relativos especificados.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | El URI base |
| relativeUri | const SharedPtr\<Uri\>\& | El URI relativo que se agrega al URI base |
| result | SharedPtr\<Uri\>\& | El argumento de salida que, si la construcción tiene éxito, apunta al nuevo objeto [Uri](../) construido al regresar del método |

### ReturnValue

True si la construcción tuvo éxito, de lo contrario - false

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method


Construye un [Uri](../) objeto a partir del objeto [Uri](../) especificado que representa el URI base y la representación en cadena del URI relativo.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | El URI base |
| relativeUri | const String\& | El URI relativo que se agrega al URI base |
| result | SharedPtr\<Uri\>\& | El argumento de salida que, si la construcción tiene éxito, apunta al nuevo objeto [Uri](../) construido al regresar del método |

### ReturnValue

True si la construcción tuvo éxito, de lo contrario - false

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method


Construye un objeto [Uri](../) que representa el URI especificado; un argumento especifica el tipo de URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriString | const String\& | El URI en forma de cadena que será representado por el objeto que se está construyendo |
| uriKind | UriKind | Especifica el tipo de URI |
| result | SharedPtr\<Uri\>\& | El argumento de salida que, si la construcción tiene éxito, apunta al nuevo objeto [Uri](../) construido al regresar del método |

### ReturnValue

True si la construcción tuvo éxito, de lo contrario - false

## Ver también

* Class [String](../../string/)
* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
