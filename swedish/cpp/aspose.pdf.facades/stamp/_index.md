---
title: "Aspose::Pdf::Facades::Stamp klass"
linktitle: "Stamp"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::Stamp klass. Klass som representerar stämpel i C++."
type: docs
weight: 3500
url: /sv/cpp/aspose.pdf.facades/stamp/
---
## Stamp class


Klass som representerar stämpel.

```cpp
class Stamp : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BindImage](./bindimage/)(const System::String\&) | Ställer in bild som en stämpel. |
| [BindImage](./bindimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in bild som kommer att användas som stämpel. |
| [BindLogo](./bindlogo/)(const System::SharedPtr\<FormattedText\>\&) | Ställer in text som stämpel. |
| [BindPdf](./bindpdf/)(const System::String\&, int32_t) | Ställer in PDF-fil och sidnummer som kommer att användas som stämpel. |
| [BindPdf](./bindpdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Ställer in PDF-fil och sidnummer som kommer att användas som stämpel. |
| [BindTextState](./bindtextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Ställer in texttillstånd för stämpeltext. |
| [get_BlendingSpace](./get_blendingspace/)() const | Hämtar ett [BlendingColorSpace](../blendingcolorspace/)-värde som definierar ett färgrymd som används för att utföra transparens- och blandningsoperationer på sidan. |
| [get_IsBackground](./get_isbackground/)() const | Hämtar bakgrundsstatus. Om sant kommer stämpeln att placeras som bakgrund på den stämplade sidan. Som standard är den satt till falskt. |
| [get_Opacity](./get_opacity/)() | Hämtar opaciteten för stämpeln. |
| [get_PageNumber](./get_pagenumber/)() const | Hämtar sidnummer. |
| [get_Pages](./get_pages/)() const | Hämtar en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla sidor i dokumentet. |
| [get_Quality](./get_quality/)() const | Hämtar kvaliteten på bildstämpeln i procent. Tillåtna värden 0..100%. |
| [get_Rotation](./get_rotation/)() const | Hämtar rotationen för stämpeln i grader. |
| [get_StampId](./get_stampid/)() const | Hämtar identifieraren för stämpeln. |
| [set_BlendingSpace](./set_blendingspace/)(BlendingColorSpace) | Ställer in ett [BlendingColorSpace](../blendingcolorspace/)‑värde som definierar ett färgrymd som används för att utföra transparens‑ och blandningsoperationer på sidan. |
| [set_IsBackground](./set_isbackground/)(bool) | Ställer in bakgrundsstatus. Om true placeras stämpeln som bakgrund på den spampade sidan. Som standard är den satt till false. |
| [set_Opacity](./set_opacity/)(float) | Ställer in opaciteten för stämpeln. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Ställer in sidnummer. |
| [set_Pages](./set_pages/)(const System::ArrayPtr\<int32_t\>\&) | Ställer in en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla sidor i dokumentet. |
| [set_Quality](./set_quality/)(int32_t) | Ställer in kvaliteten på bildstämpeln i procent. Tillåtna värden 0..100%. |
| [set_Rotation](./set_rotation/)(float) | Ställer in rotationen för stämpeln i grader. |
| [set_StampId](./set_stampid/)(int32_t) | Ställer in identifieraren för stämpeln. |
| [SetImageSize](./setimagesize/)(float, float) | Ställer in storleken på bildstämpeln. [Image](../../aspose.pdf/image/) kommer att skalas enligt de angivna värdena. |
| [SetOrigin](./setorigin/)(float, float) | Ställer in positionen på sidan där stämpeln kommer att placeras. |
| [Stamp](./stamp/)() | Konstruktor för [Stamp](./)-objektet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
