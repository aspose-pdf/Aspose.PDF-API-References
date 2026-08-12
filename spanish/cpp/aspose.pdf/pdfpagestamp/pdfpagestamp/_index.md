---
title: "Aspose::Pdf::PdfPageStamp::PdfPageStamp constructor"
linktitle: "PdfPageStamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PdfPageStamp::PdfPageStamp constructor. Constructor de PdfPageStamp en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf/pdfpagestamp/pdfpagestamp/
---
## PdfPageStamp::PdfPageStamp(const System::SharedPtr\<Page\>\&) constructor


Constructor de [PdfPageStamp](../).

```cpp
Aspose::Pdf::PdfPageStamp::PdfPageStamp(const System::SharedPtr<Page> &pdfPage)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfPage | const System::SharedPtr\<Page\>\& | [Page](../../page/) que se utiliza para el sellado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfPageStamp::PdfPageStamp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) constructor


Crea un sello de página [Pdf](../../) a partir de la página especificada en el documento desde el flujo.

```cpp
Aspose::Pdf::PdfPageStamp::PdfPageStamp(const System::SharedPtr<System::IO::Stream> &stream, int32_t pageIndex)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene PDF |
| pageIndex | int32_t | Índice de la página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfPageStamp::PdfPageStamp(const System::String\&, int32_t) constructor


Crea un sello de página [Pdf](../../) a partir de la página especificada del documento en el archivo especificado.

```cpp
Aspose::Pdf::PdfPageStamp::PdfPageStamp(const System::String &fileName, int32_t pageIndex)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | const System::String\& | Nombre y página del archivo PDF. |
| pageIndex | int32_t | Índice de la página. |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
