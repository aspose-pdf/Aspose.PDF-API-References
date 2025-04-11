---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileStamp klass. Klass för att lägga till stämplar, vattenmärken eller bakgrund till PDF-filer
type: docs
weight: 4570
url: /sv/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp klass

Klass för att lägga till stämplar (vattenmärke eller bakgrund) till PDF-filer.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Konstruktör för PdfFileStamp. Inmatningsfil och utmatningsfil kan specificeras via motsvarande egenskaper. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Initierar ett nytt `PdfFileStamp`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Ställer in PDF-filformat. Resultatfilen kommer att sparas i angivet filformat. Om denna egenskap inte specificeras kommer filen att sparas i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentfacaden som arbetar med. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Behåller säkerhet om sant. (Denna funktion kommer att implementeras i nästa versioner). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Hämtar eller ställer in sidnumreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Hämtar eller ställer in optimeringsflagga. Lika resursströmmar i den resulterande filen slås samman till ett PDF-objekt om denna flagga är inställd. Detta gör att den resulterande filstorleken kan minskas men kan orsaka långsammare exekvering och större minneskrav. Standardvärde: falskt. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Hämtar höjden på första sidan i källfilen. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Hämtar eller ställer in rotation av sidnumret. Rotation är i grader. Standard är 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Hämtar bredden på första sidan i inmatningsfilen. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | Stämpel-ID för nästa tillagda stämpel (inklusive sidhuvuden/sidfötter/sidnummer). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Hämtar eller ställer in startnummer för första sidan i inmatningsfilen. Nästa sidor kommer att numreras från detta värde. Till exempel, om StartingNumber är inställt på 100, kommer dokumentets sidor att ha nummer 100, 101, 102... |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Lägger till sidfot till sidorna i dokumentet. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Lägger till bild som sidfot på sidan. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Lägger till bild som sidfot till sidorna i dokumentet. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Lägger till sidfot till sidorna i dokumentet. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Lägger till bild som sidfot på sidan. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Lägger till bild som sidfot på sidorna. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Lägger till sidhuvud på sidan. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Lägger till bild som sidhuvud på sidorna. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Lägger till bild som sidhuvud till sidorna i filen. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Lägger till sidhuvud till sidorna i filen. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Lägger till bild högst upp på sidan. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Lägger till bild som sidhuvud på sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Lägger till sidnummer på sidan. Sidnumret kan innehålla # tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Lägger till sidnummer till filen. Texten för sidnumret kan innehålla # tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Lägger till sidnummer till sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Lägger till sidnummer till sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Lägger till sidnummer på den angivna positionen på sidan. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Lägger till sidnummer på den angivna positionen på sidan. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Lägger till sidnummer till sidorna i dokumentet. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Lägger till sidnummer till sidorna i dokumentet. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Lägger till stämpel till filen. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar facaden. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Stänger öppnade filer och sparar ändringar. Varning. Om inmatnings- eller utmatningsströmmar specificeras stängs de inte av Close() metoden. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter facaden. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Sparar dokumentet i angiven ström. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Sparar resultatet i angiven fil. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Nedersta vänstra position. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Nedersta mittersta position. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Nedersta högra position. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Vänster position. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Höger position. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Övre vänstra position. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Övre mittersta position. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Övre högra position. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../)