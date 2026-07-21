---
title: "Aspose::Pdf::Facades::PdfExtractor::GetNextImage método"
linktitle: "GetNextImage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfExtractor::GetNextImage method. Recupera la siguiente imagen del archivo PDF y la almacena en un flujo en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf.facades/pdfextractor/getnextimage/
---
## PdfExtractor::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&) method


Recupera la siguiente imagen del archivo PDF y la almacena en un flujo.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo donde se guardarán los datos de la imagen |

### ReturnValue

True en caso de que la imagen se extraiga correctamente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Recupera la siguiente imagen del archivo PDF y la almacena en un flujo con el formato de imagen especificado.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo donde se guardarán los datos de la imagen |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |

### ReturnValue

True en caso de que la imagen se extraiga correctamente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::String\&) method


Recupera la siguiente imagen del documento PDF. [Note](../../../aspose.pdf/note/): ExtractImage debe llamarse antes de usar este método.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | Archivo donde se almacenará la imagen |

### ReturnValue

True si la imagen se extrae correctamente

## Ver también

* Class [String](../../../system/string/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Recupera la siguiente imagen del documento PDF con el formato de imagen especificado. [Note](../../../aspose.pdf/note/): ExtractImage debe llamarse antes de usar este método.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | const System::String\& | Archivo donde se almacenará la imagen |
| formato | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | El formato de la imagen. |

### ReturnValue

True si la imagen se extrae correctamente

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
