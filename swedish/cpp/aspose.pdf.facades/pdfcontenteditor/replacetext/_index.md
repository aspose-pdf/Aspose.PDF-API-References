---
title: "Aspose::Pdf::Facades::PdfContentEditor::ReplaceText metod"
linktitle: "ReplaceText"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::ReplaceText metod. Ersätter text i PDF-filen i C++."
type: docs
weight: 4500
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&) method


Ersätter text i PDF‑filen.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | const System::String\& | Strängen som ska ersättas. |
| destString | const System::String\& | Ersättningssträng. |

### ReturnValue

Returnerar true om ersättningen gjordes.

## Se även

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) method


Ersätter text i PDF‑filen med hjälp av det specificerade objektet [TextState](../).

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString, const System::SharedPtr<Text::TextState> &textState)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | const System::String\& | Sträng att ersätta |
| destString | const System::String\& | Ersättningssträng |
| textState | const System::SharedPtr\<Text::TextState\>\& | [Text](../../../aspose.pdf.text/) tillstånd ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Teckensnitt osv) |

### ReturnValue

Returnerar true om ersättningen gjordes.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&, int32_t) method


Ersätter text i PDF‑filen och anger teckenstorlek.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString, int32_t fontSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | const System::String\& | Sträng som ska ersättas. |
| destString | const System::String\& | Ersättningssträng. |
| fontSize | int32_t | Teckensnittsstorlek. |

### ReturnValue

Returnerar true om ersättningen gjordes.

## Se även

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, int32_t, const System::String\&) method


Ersätter text i PDF‑filen på den angivna sidan.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, int32_t thePage, const System::String &destString)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | const System::String\& | Strängen som ska ersättas. |
| thePage | int32_t | [Sida](../../../aspose.pdf/page/) nummer (0 för alla sidor) |
| destString | const System::String\& | Ersättningssträng. |

### ReturnValue

Returnerar true om ersättningen gjordes.

## Se även

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, int32_t, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) method


Ersätter text i PDF‑filen på den angivna sidan. Objektet [TextState](../) (teckensnittsfamilj, färg) kan specificeras för den ersatta texten.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, int32_t thePage, const System::String &destString, const System::SharedPtr<Text::TextState> &textState)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | const System::String\& | Strängen som ska ersättas. |
| thePage | int32_t | [Sida](../../../aspose.pdf/page/) nummer (0 betyder "alla sidor"). |
| destString | const System::String\& | Den ersatta strängen. |
| textState | const System::SharedPtr\<Text::TextState\>\& | [Text](../../../aspose.pdf.text/) tillstånd ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Teckensnitt osv). |

### ReturnValue

Returnerar true om ersättningen gjordes.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
