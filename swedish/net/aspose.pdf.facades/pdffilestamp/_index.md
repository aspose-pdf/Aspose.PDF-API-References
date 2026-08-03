---
title: "Klass PdfFileStamp"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileStamp-klass. Klass för att lägga till stämplar, vattenstämplar eller bakgrund till PDF‑filer"
type: docs
weight: 4690
url: /sv/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Klass för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF files.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Konstruktor för PdfFileStamp. Indatafil och utdatafil kan anges via motsvarande egenskaper. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Initierar ett nytt `PdfFileStamp`‑objekt baserat på *document*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Behåller säkerhet om true. (Denna funktion kommer att implementeras i kommande versioner). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Hämtar eller anger sidnumreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Hämtar eller anger optimeringsflagga. Likadana resursströmmar i den resulterande filen slås ihop till ett PDF‑objekt om flaggan är satt. Detta minskar filens storlek men kan leda till långsammare körning och högre minneskrav. Standardvärde: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Hämtar höjden på den första sidan i källfilen. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Hämtar eller anger rotation för sidnummer. Rotation är i grader. Standard är 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Hämtar bredden på den första sidan i indatafilen. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | Stämpel-ID för nästa tillagda stämpel (inklusive sidhuvuden/sidfötter/sidnummer). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Hämtar eller anger startnummer för den första sidan i indatafilen. Efterföljande sidor kommer att numreras med början från detta värde. Till exempel, om StartingNumber är satt till 100, kommer dokumentets sidor att ha nummer 100, 101, 102... |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Lägger till sidfot på dokumentets sidor. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Lägger till bild som sidfot på sidan. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Lägger till bild som sidfot på dokumentets sidor. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Lägger till sidfot på dokumentets sidor. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Lägger till bild som sidfot på sidan. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Lägger till bild som sidfot på sidorna. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Lägger till sidhuvud på sidan. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Lägger till bild som sidhuvud på sidorna. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Lägger till bild som sidhuvud på filens sidor. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Lägger till sidhuvud på filens sidor. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Lägger till bild högst upp på sidan. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Lägger till bild som sidhuvud på sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Lägger till sidnummer på sidan. Sidnumret kan innehålla #-tecken som ersätts med sidnumret. Sidnumret placeras längst ner på sidan centrerat horisontellt. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Lägg till sidnummer i filen. Sidnummertexten kan innehålla #-tecken som ersätts med sidnumret. Sidnumret placeras längst ner på sidan centrerat horisontellt. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Lägger till sidnummer på sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Lägger till sidnummer på sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Lägger till sidnummer på den angivna positionen på sidan. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Lägger till sidnummer på den angivna positionen på sidan. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Lägger till sidnummer på dokumentets sidor. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Lägger till sidnummer på dokumentets sidor. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Lägger till stämpel i filen. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Stänger öppna filer och sparar ändringar. Varning. Om in- eller utdataflöden är angivna stängs de inte av Close()-metoden. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Sparar dokumentet i angiven ström. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Sparar resultatet i angiven fil. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Nedre vänstra positionen. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Nedre mittersta positionen. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Nedre högra positionen. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Vänster position. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Höger position. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Övre vänstra positionen. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Övre mittenposition. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Höger övre position. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


