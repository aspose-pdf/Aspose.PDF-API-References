---
title: "Constructor System::Drawing::Bitmap::Bitmap"
linktitle: "Bitmap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::Drawing::Bitmap::Bitmap. Construye un nuevo objeto Bitmap a partir de la imagen existente especificada en C++."
type: docs
weight: 100
url: /es/cpp/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor


Construye un nuevo objeto [Bitmap](../) a partir de la imagen existente especificada.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | La imagen existente de la cual crear la imagen bitmap |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor


Construye un nuevo objeto [Bitmap](../) a partir de la imagen existente especificada, escalado al tamaño especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | La imagen existente de la cual crear la imagen bitmap |
| size | const Size\& | El tamaño de la nueva imagen |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Size](../../size/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor


Construye un nuevo objeto [Bitmap](../) a partir de la imagen existente especificada con el ancho y alto escalados a los valores especificados.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | La imagen existente de la cual crear la imagen bitmap |
| ancho | int | Ancho de la nueva imagen |
| altura | int | Altura de la nueva imagen |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor


Construye un nuevo objeto [Bitmap](../) a partir del flujo especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<System::IO::Stream\>\& | Un flujo que contiene datos de imagen |
| useIcm | bool | IGNORED |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const String\&) constructor


Construye un nuevo objeto [Bitmap](../) a partir del archivo especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const String\& | Un nombre del archivo que contiene datos de imagen |

## Ver también

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const String\&, bool) constructor


Construye un nuevo objeto [Bitmap](../) a partir del archivo especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const String\& | Un nombre del archivo que contiene datos de imagen |
| useIcm | bool | IGNORED |

## Ver también

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor


Construye un nuevo objeto [Bitmap](../) que representa una imagen bitmap con el ancho, alto, formato de píxel y datos de píxel especificados.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | int | El ancho de la imagen |
| altura | int | La altura de la imagen |
| formato | Imaging::PixelFormat | El formato de píxel de la imagen |

## Ver también

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
