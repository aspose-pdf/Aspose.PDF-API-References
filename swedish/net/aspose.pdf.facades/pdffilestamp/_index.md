---
title: PdfFileStamp
second_title: Aspose.PDF för .NET API Referens
description: Klass för att lägga till stämplar vattenstämpel eller bakgrund till PDF-filer.
type: docs
weight: 2580
url: /sv/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Klass för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF-filer.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | Konstruktör av PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | Initierar ny[`PdfFileStamp`](../pdffilestamp) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | Hämtar eller ställer in namnet på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | Hämtar eller ställer in hur innehåll ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | Ställer in PDF-filformat. Resultatfilen kommer att sparas i angivet filformat. Om den här egenskapen inte anges sparas filen i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | Behåller säkerheten om sant. (Denna funktion kommer att implementeras i nästa versioner). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | Hämtar eller ställer in sidnumreringsstil. Möjliga värden: Numerals Arabic, NumeralsRomanVersaler, NumeralsRomanGeser, BokstäverAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | Hämtar eller ställer in optimeringsflagga. Lika resursströmmar i den resulterande filen slås samman till ett PDF-objekt om denna flagga är inställd. Detta gör det möjligt att minska den resulterande filstorleken men kan orsaka långsammare exekvering och större minneskrav. Standardvärde: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | Får höjden på första sidan i källfilen. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | Hämtar eller ställer in rotation av sidnummer. Rotationen är i grader. Standard är 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | Får bredden på första sidan i inmatningsfilen. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | Hämtar eller ställer in svarsobjekt där resultatet av operationen kommer att lagras. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | Hämtar eller ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | Stämpel-ID för nästa stämpel som lagts till (inklusive sidhuvuden/tittare/sidnummer). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | Hämtar eller ställer in startnummer för första sidan i inmatningsfilen. Nästa sidor kommer att numreras från detta värde. Till exempel om StartingNumber är inställt på 100 kommer dokumentsidorna att ha nummer 100, 101, 102... |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | Lägger till sidfot på dokumentets sidor. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | Lägger till bild som sidfot på sidan. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | Lägger till bild som sidfot på dokumentets sidor. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | Lägger till sidfot på dokumentets sidor. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | Lägger till bild som sidfot på sidan. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | Lägger till bild som sidfot på sidorna. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | Lägger till sidhuvud på sidan. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | Lägger till bild som rubrik på sidorna. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | Lägger till bild som rubrik på filens sidor. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | Lägger till sidhuvud till filsidorna. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | Lägger till bild överst på sidan. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | Lägger till bild som rubrik på sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | Lägger till sidnummer på sidan. Sidnummer kan innehålla #-tecken som kommer att ersättas med sidnummer. Sidnummer placeras längst ner på sidan centrerat horisontellt. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | Lägg till sidnummer i filen. Sidnummertext kan innehålla #-tecken som kommer att ersättas med sidans nummer. Sidnummer placeras längst ner på sidan centrerat horisontellt. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | Lägger till sidnummer på sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | Lägger till sidnummer på sidorna. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | Lägger till sidnummer på den angivna positionen på sidan. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | Lägger till sidnummer på den angivna positionen på sidan. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | Lägger till sidnummer på sidorna i dokumentet. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | Lägger till sidnummer på sidorna i dokumentet. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | Lägger till stämpel till filen. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | Stänger öppnade filer och sparar ändringar. Varning. Om in- eller utströmmar är specificerade stängs de inte av metoden Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | Sparar dokument i angiven ström. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | Sparar resultatet i angiven fil. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | Nedre vänstra position. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | Nedre mittposition. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | Nedre högra position. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | Vänster position. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | Höger position. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | Övre låtposition. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | Övre mittläge. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | Höger övre position. |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
