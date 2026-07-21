---
title: "Aspose::Pdf::Facades::PdfExtractor::GetAttachment method"
linktitle: "GetAttachment"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfExtractor::GetAttachment method. Guarda todos los archivos adjuntos en flujos en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf.facades/pdfextractor/getattachment/
---
## PdfExtractor::GetAttachment() method


Guarda todos los archivos adjuntos en flujos.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfExtractor::GetAttachment()
```


### ReturnValue

La matriz de flujos del archivo adjunto en el documento pdf.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetAttachment(const System::String\&) method


Guarda el adjunto en un archivo.

```cpp
void Aspose::Pdf::Facades::PdfExtractor::GetAttachment(const System::String &outputPath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputPath | const System::String\& | Ruta del directorio donde se almacenarán los archivos adjuntos. Null o cadena vacía significa que los archivos adjuntos se colocarán en el directorio de la aplicación. |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
