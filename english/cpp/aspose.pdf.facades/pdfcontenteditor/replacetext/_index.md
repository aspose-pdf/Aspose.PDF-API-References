---
title: Aspose::Pdf::Facades::PdfContentEditor::ReplaceText method
linktitle: ReplaceText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::ReplaceText method. Replaces text in the PDF file on the specified page in C++.'
type: docs
weight: 4500
url: /cpp/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## PdfContentEditor::ReplaceText(System::String, int32_t, System::String) method


Replaces text in the PDF file on the specified page.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, int32_t thePage, System::String destString)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | The sting to be replaced. |
| thePage | int32_t | [Page](../../../aspose.pdf/page/) number (0 for all pages) |
| destString | System::String | Replacing string. |

### ReturnValue

Returns true if replacement was made.

## See Also

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(System::String, int32_t, System::String, System::SharedPtr\<Text::TextState\>) method


Replaces text in the PDF file on the specified page. [TextState](../) object (font family, color) can be specified to replaced text.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, int32_t thePage, System::String destString, System::SharedPtr<Text::TextState> textState)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | The string to be replaced. |
| thePage | int32_t | [Page](../../../aspose.pdf/page/) number (0 means "all pages"). |
| destString | System::String | The replaced string. |
| textState | System::SharedPtr\<Text::TextState\> | [Text](../../../aspose.pdf.text/) state ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Font etc). |

### ReturnValue

Returns true if replacement was made.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(System::String, System::String) method


Replaces text in the PDF file.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, System::String destString)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | The string to be replaced. |
| destString | System::String | Replacing string. |

### ReturnValue

Returns true if replacement was made.

## See Also

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(System::String, System::String, int32_t) method


Replaces text in the PDF file and sets font size.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, System::String destString, int32_t fontSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | String to be replaced. |
| destString | System::String | Replacing string. |
| fontSize | int32_t | Font size. |

### ReturnValue

Returns true if replacement was made.

## See Also

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(System::String, System::String, System::SharedPtr\<Text::TextState\>) method


Replaces text in the PDF file using specified [TextState](../) object.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, System::String destString, System::SharedPtr<Text::TextState> textState)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | String to be replaced |
| destString | System::String | Replacing string |
| textState | System::SharedPtr\<Text::TextState\> | [Text](../../../aspose.pdf.text/) state ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Font etc) |

### ReturnValue

Returns true if replacement was made.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
