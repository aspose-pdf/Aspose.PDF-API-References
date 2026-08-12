---
title: "Método Aspose::Pdf::Facades::Stamp::BindPdf"
linktitle: "BindPdf"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::Stamp::BindPdf. Establece el archivo PDF y el número de página que se utilizará como sello en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.facades/stamp/bindpdf/
---
## Stamp::BindPdf(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) method


Establece el archivo PDF y el número de página que se usarán como sello.

```cpp
void Aspose::Pdf::Facades::Stamp::BindPdf(const System::SharedPtr<System::IO::Stream> &pdfStream, int32_t pageNumber)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia que contiene el documento PDF. |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) índice de la página del documento que se usará como sello. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Stamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Stamp::BindPdf(const System::String\&, int32_t) method


Establece el archivo PDF y el número de página que se usarán como sello.

```cpp
void Aspose::Pdf::Facades::Stamp::BindPdf(const System::String &pdfFile, int32_t pageNumber)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfFile | const System::String\& | Ruta al archivo PDF. |
| pageNumber | int32_t | Número de página en el archivo PDF |

## Ver también

* Class [String](../../../system/string/)
* Class [Stamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
