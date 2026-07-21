---
title: "Aspose::Pdf::Document::Validate método"
linktitle: "Validar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Document::Validate método. Valida el documento en el archivo especificado en C++."
type: docs
weight: 11600
url: /es/cpp/aspose.pdf/document/validate/
---
## Document::Validate(const System::SharedPtr\<PdfFormatConversionOptions\>\&) method


Validar el documento en el archivo especificado.

```cpp
bool Aspose::Pdf::Document::Validate(const System::SharedPtr<PdfFormatConversionOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opciones | const System::SharedPtr\<PdfFormatConversionOptions\>\& | conjunto de opciones para convertir documento PDF |

### ReturnValue

El resultado de la operación

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat) method


Validar el documento en el archivo especificado.

```cpp
bool Aspose::Pdf::Document::Validate(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream donde se almacenarán los comentarios. |
| formato | Aspose::Pdf::PdfFormat | El formato pdf. |

### ReturnValue

El resultado de la operación

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(const System::String\&, Aspose::Pdf::PdfFormat) method


Validar el documento en el archivo especificado.

```cpp
bool Aspose::Pdf::Document::Validate(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Ruta al archivo donde se almacenarán los comentarios. |
| formato | Aspose::Pdf::PdfFormat | El formato pdf. |

### ReturnValue

El resultado de la operación

## Ver también

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
