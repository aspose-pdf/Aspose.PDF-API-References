---
title: "Método Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak"
linktitle: "AddPageBreak"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak. Añade saltos de página en las páginas del documento en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.facades/pdffileeditor/addpagebreak/
---
## PdfFileEditor::AddPageBreak(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Agrega saltos de página en las páginas del documento.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::SharedPtr<Document> &src, const System::SharedPtr<Document> &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const System::SharedPtr\<Document\>\& | Documento de origen. |
| dest | const System::SharedPtr\<Document\>\& | Documento de destino. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Matriz de objetos [PageBreak](../pagebreak/) que describen los lugares de los saltos de página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddPageBreak(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Agrega saltos de página en las páginas del documento.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::SharedPtr<System::IO::Stream> &src, const System::SharedPtr<System::IO::Stream> &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const System::SharedPtr\<System::IO::Stream\>\& | Origen que contiene el documento de origen. |
| dest | const System::SharedPtr\<System::IO::Stream\>\& | Origen donde se guardará el documento de destino. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Matriz de objetos [PageBreak](../pagebreak/) que describen páginas y lugares donde se añadirá el salto de página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddPageBreak(const System::String\&, const System::String\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Agrega saltos de página en las páginas del documento.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::String &src, const System::String &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const System::String\& | Ruta al documento fuente. |
| dest | const System::String\& | Ruta al documento de destino. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Matriz de objetos [PageBreak](../pagebreak/) que describen páginas y lugares donde se añadirá el salto de página. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
