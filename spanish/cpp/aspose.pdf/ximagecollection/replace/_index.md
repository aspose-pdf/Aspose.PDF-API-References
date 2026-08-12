---
title: "Método Aspose::Pdf::XImageCollection::Replace"
linktitle: "Reemplazar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::XImageCollection::Replace. Reemplaza la imagen en la colección con otra imagen en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.pdf/ximagecollection/replace/
---
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Reemplazar la imagen en la colección con otra imagen.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int32_t | Índice del elemento de la colección que será reemplazado en el rango [1..images count]. |
| flujo | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene datos de imagen (en formato JPEG). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t) method


Reemplazar la imagen en la colección con otra imagen.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int32_t | Índice del elemento de la colección que será reemplazado en el rango [1..images count]. |
| flujo | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene datos de imagen (en formato JPEG). |
| calidad | int32_t | Calidad JPEG. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, bool) method


Reemplazar la imagen en la colección con otra imagen.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream, int32_t quality, bool isBlackAndWhite)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int32_t | Índice del elemento de la colección que será reemplazado en el rango [1..images count]. |
| flujo | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene datos de imagen (en formato JPEG). |
| calidad | int32_t | Calidad de la compresión JPEG, en porcentaje (los valores válidos son 0..100). |
| isBlackAndWhite | bool | Si es true, la imagen se comprime con el método de compresión CCITT que proporciona mejor compresión para imágenes en blanco y negro. Solo se puede usar para imágenes en blanco y negro. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
