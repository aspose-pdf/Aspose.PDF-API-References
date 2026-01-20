---
title: Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber method
linktitle: AddPageNumber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber method. Adds page number to the page. Page number may contain # sign which will be replaced with page number. Page number is placed in the bottom of the page centered horizontally in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## PdfFileStamp::AddPageNumber(System::SharedPtr\<FormattedText\>) method


Adds page number to the page. [Page](../../../aspose.pdf/page/) number may contain # sign which will be replaced with page number. [Page](../../../aspose.pdf/page/) number is placed in the bottom of the page centered horizontally.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(System::SharedPtr<FormattedText> formattedText)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | System::SharedPtr\<FormattedText\> | Format string for page number representes as [FormattedText](../../formattedtext/). |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(System::SharedPtr\<FormattedText\>, float, float) method


Adds page number at the specified position on the page.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(System::SharedPtr<FormattedText> formattedText, float x, float y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | System::SharedPtr\<FormattedText\> | Formatted text which represents page number format and properties of the text. Format string can contain # sign which will be replaced with page number. |
| x | float | X coordinate of page number. |
| y | float | Y coordinate of page number. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(System::SharedPtr\<FormattedText\>, int32_t) method


Adds page number to the pages.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(System::SharedPtr<FormattedText> formattedText, int32_t position)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | System::SharedPtr\<FormattedText\> | [FormattedText](../../formattedtext/) object which contains format of the page number and text properties. This text may contain # which will be replaced with page number. |
| position | int32_t | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(System::SharedPtr\<FormattedText\>, int32_t, float, float, float, float) method


Adds page number to the pages of document.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(System::SharedPtr<FormattedText> formattedText, int32_t position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | System::SharedPtr\<FormattedText\> | [FormattedText](../../formattedtext/) object which represents page number format and properties iof the text. |
| position | int32_t | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margin on the left edge of the page. |
| rightMargin | float | Margin on the right edge of the page. |
| topMargin | float | Margin on the top edge of the page. |
| bottomMargin | float | Margin on the bottom edge of the page. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(System::String) method


Add page number to file. [Page](../../../aspose.pdf/page/) number text may contain # sign which will be replaced with number of the page. [Page](../../../aspose.pdf/page/) number is placed in the bottom of the page centered horizontally.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(System::String formatString)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formatString | System::String | [Text](../../../aspose.pdf.text/) of page number |

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(System::String, float, float) method


Adds page number at the specified position on the page.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(System::String formatString, float x, float y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formatString | System::String | Format string. Format string can contain # sign which will be replaced with page number. |
| x | float | X coordinate of page number. |
| y | float | Y coordinate of page number. |

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(System::String, int32_t) method


Adds page number to the pages.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(System::String formatString, int32_t position)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formatString | System::String | Format of the page number. This text may contain # which will be replaced with page number. |
| position | int32_t | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(System::String, int32_t, float, float, float, float) method


Adds page number to the pages of document.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(System::String formatString, int32_t position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formatString | System::String | Format string for page number. |
| position | int32_t | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margin on the left edge of the page. |
| rightMargin | float | Margin on the right edge of the page. |
| topMargin | float | Margin on the top edge of the page. |
| bottomMargin | float | Margin on the bottom edge of the page. |

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
