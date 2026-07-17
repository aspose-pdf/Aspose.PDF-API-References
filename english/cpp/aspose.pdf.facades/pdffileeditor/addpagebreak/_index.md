---
title: Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak method
linktitle: AddPageBreak
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak method. Adds page breaks into document pages in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.facades/pdffileeditor/addpagebreak/
---
## PdfFileEditor::AddPageBreak(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Adds page breaks into document pages.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::SharedPtr<Document> &src, const System::SharedPtr<Document> &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::SharedPtr\<Document\>\& | Source document. |
| dest | const System::SharedPtr\<Document\>\& | Destination document. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Array of [PageBreak](../pagebreak/) objects which describe places of page breaks. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddPageBreak(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Adds page breaks into document pages.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::SharedPtr<System::IO::Stream> &src, const System::SharedPtr<System::IO::Stream> &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::SharedPtr\<System::IO::Stream\>\& | Source which contains source document. |
| dest | const System::SharedPtr\<System::IO::Stream\>\& | Source where destination document will be saved. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Array of [PageBreak](../pagebreak/) object describing pages and places where page break will be added. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddPageBreak(const System::String\&, const System::String\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Adds page breaks into document pages.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::String &src, const System::String &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::String\& | Path to source document. |
| dest | const System::String\& | Path to destination document. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Array of [PageBreak](../pagebreak/) object describing pages and places where page break will be added. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
