---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment method
linktitle: CreateFileAttachment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment method. Creates file attachment annotation in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&) method


Creates file attachment annotation.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle rect, const System::String &contents, const System::SharedPtr<System::IO::Stream> &attachmentStream, const System::String &attachmentName, int32_t page, const System::String &name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | const System::String\& | The contents of the annotation. |
| attachmentStream | const System::SharedPtr\<System::IO::Stream\>\& | The attachment file stream. |
| attachmentName | const System::String\& | The attachment name. |
| page | int32_t | The number of original page where the annotation will be created. |
| name | const System::String\& | The name of an icon will be used in displaying the annotation. This value can be: "Graph", "PushPin", "Paperclip", "Tag". |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&, double) method


Creates file attachment annotation.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle rect, const System::String &contents, const System::SharedPtr<System::IO::Stream> &attachmentStream, const System::String &attachmentName, int32_t page, const System::String &name, double opacity)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | const System::String\& | The contents of the annotation. |
| attachmentStream | const System::SharedPtr\<System::IO::Stream\>\& | The attachment file stream. |
| attachmentName | const System::String\& | The attachment name. |
| page | int32_t | The number of original page where the annotation will be created. |
| name | const System::String\& | The name of an icon will be used in displaying the annotation. This value can be: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | double | Icon's opacity from 0 to 1: 0 - completely transparant, 1 - completely opaque. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&) method


Creates file attachment annotation.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle rect, const System::String &contents, const System::String &filePath, int32_t page, const System::String &name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | const System::String\& | The contents of the annotation. |
| filePath | const System::String\& | The path of the file will be attached. |
| page | int32_t | The number of original page where the annotation will be created. |
| name | const System::String\& | The name of an icon will be used in displaying the annotation. This value can be: "Graph", "PushPin", "Paperclip", "Tag". |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&, double) method


Creates file attachment annotation.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle rect, const System::String &contents, const System::String &filePath, int32_t page, const System::String &name, double opacity)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | const System::String\& | The contents of the annotation. |
| filePath | const System::String\& | The path of the file will be attached. |
| page | int32_t | The number of original page where the annotation will be created. |
| name | const System::String\& | The name of an icon will be used in displaying the annotation. This value can be: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | double | Icon's opacity from 0 to 1: 0 - completely transparant, 1 - completely opaque. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
