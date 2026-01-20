---
title: Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak method
linktitle: AddPageBreak
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak method. Adds page breaks into document pages in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.facades/pdffileeditor/addpagebreak/
---
## PdfFileEditor::AddPageBreak(System::SharedPtr\<Document\>, System::SharedPtr\<Document\>, System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>) method


Adds page breaks into document pages.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(System::SharedPtr<Document> src, System::SharedPtr<Document> dest, System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> pageBreaks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src | System::SharedPtr\<Document\> | Source document. |
| dest | System::SharedPtr\<Document\> | Destination document. |
| pageBreaks | System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\> | Array of [PageBreak](../pagebreak/) objects which describe places of page breaks. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddPageBreak(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>) method


Adds page breaks into document pages.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(System::SharedPtr<System::IO::Stream> src, System::SharedPtr<System::IO::Stream> dest, System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> pageBreaks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src | System::SharedPtr\<System::IO::Stream\> | Source which contains source document. |
| dest | System::SharedPtr\<System::IO::Stream\> | Source where destination document will be saved. |
| pageBreaks | System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\> | Array of [PageBreak](../pagebreak/) object describing pages and places where page break will be added. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddPageBreak(System::String, System::String, System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>) method


Adds page breaks into document pages.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(System::String src, System::String dest, System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> pageBreaks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src | System::String | Path to source document. |
| dest | System::String | Path to destination document. |
| pageBreaks | System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\> | Array of [PageBreak](../pagebreak/) object describing pages and places where page break will be added. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
