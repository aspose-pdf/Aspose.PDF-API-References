---
title: "Aspose::Pdf::Facades::PdfConverter::GetNextImage método"
linktitle: "GetNextImage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfConverter::GetNextImage método. Guarda la imagen en un stream con el formato de imagen predeterminado - jpeg en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.facades/pdfconverter/getnextimage/
---
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&) method


Guarda la imagen en un flujo con el formato de imagen predeterminado - jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) method


Guarda la imagen en un flujo con el tamaño de página especificado.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página de la imagen. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Guarda la imagen en un flujo con el tamaño de página especificado.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página de la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Guarda la imagen en un flujo con el tamaño de página, formato de imagen y calidad especificados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página de la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| calidad | int32_t | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Guarda la imagen en un flujo con el formato de imagen especificado.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) method


Guarda la imagen en un flujo con el formato de imagen, tamaño y calidad proporcionados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, double imageWidth, double imageHeight, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| imageWidth | double | El ancho de la imagen, la unidad es píxel. |
| imageHeight | double | El alto de la imagen, la unidad es píxel. |
| calidad | int32_t | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) method


Guarda la imagen en un flujo con el formato de imagen, tamaño y calidad proporcionados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| imageWidth | int32_t | El ancho de la imagen, la unidad es píxel. |
| imageHeight | int32_t | El alto de la imagen, la unidad es píxel. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) method


Guarda la imagen en un flujo con el formato de imagen, dimensiones y calidad proporcionados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| imageWidth | int32_t | El ancho de la imagen, la unidad es píxel. |
| imageHeight | int32_t | El alto de la imagen, la unidad es píxel. |
| calidad | int32_t | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Guarda la imagen en un flujo con el formato de imagen y calidad especificados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | El stream para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| calidad | int32_t | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&) method


Guarda la imagen en un archivo con el formato de imagen predeterminado - jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&) method


Guarda la imagen en un archivo con el tamaño de página dado y el formato de imagen predeterminado - jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página de la imagen. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Guarda la imagen en un archivo con el tamaño de página y el formato de imagen especificados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página de la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Guarda la imagen en un archivo con el tamaño de página, formato de imagen y calidad especificados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página de la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| calidad | int32_t | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Guarda la imagen en un archivo con el formato de imagen proporcionado.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) method


Guarda la imagen en un archivo con el formato de imagen, tamaño de imagen y calidad proporcionados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, double imageWidth, double imageHeight, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| imageWidth | double | El ancho de la imagen, la unidad es píxeles. |
| imageHeight | double | El alto de la imagen, la unidad es píxeles.. |
| calidad | int32_t | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) method


Guarda la imagen en un archivo con el formato de imagen y dimensiones especificados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| imageWidth | int32_t | El ancho de la imagen, la unidad es píxel. |
| imageHeight | int32_t | El alto de la imagen, la unidad es píxel. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) method


Guarda la imagen en un archivo con el formato de imagen, dimensiones y calidad especificados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| imageWidth | int32_t | El ancho de la imagen, la unidad es píxel. |
| imageHeight | int32_t | El alto de la imagen, la unidad es píxel. |
| calidad | int32_t | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Guarda la imagen en un archivo con el formato de imagen y calidad especificados.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | La ruta del archivo y el nombre para guardar la imagen. |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |
| calidad | int32_t | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
