---
title: "Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber metod"
linktitle: "AddPageNumber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber metod. Lägger till sidnummer på sidan. Sidnummer kan innehålla #‑tecken som kommer att ersättas med sidnumret. Sidnummer placeras längst ner på sidan centrerat horisontellt i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&) method


Lägger till sidnummer på sidan. [Page](../../../aspose.pdf/page/) nummer kan innehålla #‑tecken som kommer att ersättas med sidnumret. [Page](../../../aspose.pdf/page/) nummer placeras längst ner på sidan centrerat horisontellt.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Formatsträng för sidnummer representeras som [FormattedText](../../formattedtext/). |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, float, float) method


Lägger till sidnummer på den angivna positionen på sidan.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, float x, float y)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Formaterad text som representerar sidnummerformatet och textens egenskaper. Formatsträngen kan innehålla #‑tecken som kommer att ersättas med sidnumret. |
| x | float | X‑koordinat för sidnummer. |
| y | float | Y-koordinat för sidnummer. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, int32_t) method


Lägger till sidnummer på sidorna.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, int32_t position)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | [FormattedText](../../formattedtext/) objekt som innehåller formatet för sidnumret och textegenskaper. Denna text kan innehålla # som kommer att ersättas med sidnummer. |
| position | int32_t | Position där sidnumret kommer att placeras på sidan. 0‑nedre mitten, 1‑nedre höger, 2‑övre höger, 3‑sidor höger, 4‑övre mitten, 5‑nedre vänster, 6‑sidor vänster, 7‑övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) method


Lägger till sidnummer på dokumentets sidor.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, int32_t position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | [FormattedText](../../formattedtext/) objekt som representerar sidnummerformatet och egenskaperna för texten. |
| position | int32_t | Position där sidnumret kommer att placeras på sidan. 0‑nedre mitten, 1‑nedre höger, 2‑övre höger, 3‑sidor höger, 4‑övre mitten, 5‑nedre vänster, 6‑sidor vänster, 7‑övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Marginal på vänstra kanten av sidan. |
| rightMargin | float | Marginal på högra kanten av sidan. |
| topMargin | float | Marginal på övre kanten av sidan. |
| bottomMargin | float | Marginal på nedre kanten av sidan. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&) method


Lägg till sidnummer i filen. [Page](../../../aspose.pdf/page/) nummertext kan innehålla #‑tecken som kommer att ersättas med sidans nummer. [Page](../../../aspose.pdf/page/) nummer placeras längst ner på sidan centrerat horisontellt.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | const System::String\& | [Text](../../../aspose.pdf.text/) för sidnummer |

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, float, float) method


Lägger till sidnummer på den angivna positionen på sidan.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, float x, float y)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | const System::String\& | Formatsträng. Formatsträngen kan innehålla #‑tecken som kommer att ersättas med sidnummer. |
| x | float | X‑koordinat för sidnummer. |
| y | float | Y-koordinat för sidnummer. |

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, int32_t) method


Lägger till sidnummer på sidorna.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, int32_t position)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | const System::String\& | Format för sidnumret. Denna text kan innehålla # som kommer att ersättas med sidnummer. |
| position | int32_t | Position där sidnumret kommer att placeras på sidan. 0‑nedre mitten, 1‑nedre höger, 2‑övre höger, 3‑sidor höger, 4‑övre mitten, 5‑nedre vänster, 6‑sidor vänster, 7‑övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, int32_t, float, float, float, float) method


Lägger till sidnummer på dokumentets sidor.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, int32_t position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | const System::String\& | Formatsträng för sidnummer. |
| position | int32_t | Position där sidnumret kommer att placeras på sidan. 0‑nedre mitten, 1‑nedre höger, 2‑övre höger, 3‑sidor höger, 4‑övre mitten, 5‑nedre vänster, 6‑sidor vänster, 7‑övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Marginal på vänstra kanten av sidan. |
| rightMargin | float | Marginal på högra kanten av sidan. |
| topMargin | float | Marginal på övre kanten av sidan. |
| bottomMargin | float | Marginal på nedre kanten av sidan. |

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
