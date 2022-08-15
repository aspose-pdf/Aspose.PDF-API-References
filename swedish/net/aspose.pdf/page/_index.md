---
title: Page
second_title: Aspose.PDF för .NET API Referens
description: Klass som representerar sidan i PDF-dokument.
type: docs
weight: 5790
url: /sv/net/aspose.pdf/page/
---
## Page class

Klass som representerar sidan i PDF-dokument.

```csharp
public sealed class Page : IDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | Får samling av sidegenskaper. |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | Får en samling sidkommentarer. [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | Hämtar eller ställer in konstrutan för sidan. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | Hämtar en samling av artefakter på sidan. |
| [Background](../../aspose.pdf/page/background) { get; set; } | Hämtar eller ställer in bakgrundsfärgen på sidan. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | Hämtar eller ställer in bakgrundsbild för sidan (endast för generator). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | Hämtar eller ställer in utfallningsrutan för sidan. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | Ställer in färgtyp för sidorna baserat på information från operatörerna SetColor, bilder och formulär. |
| [Contents](../../aspose.pdf/page/contents) { get; } | Får samling av operatorer i innehållsströmmen på sidan. [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | Hämtar eller ställer in beskärningsrutan för sidan. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | Får inställd sidvisningstid. Detta är tiden i sekunder som sidan ska visas under presentationen. Returnerar -1 om varaktigheten inte är definierad. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | Hämtar lista över fältobjekt i tabbordning på den här sidan. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | Hämtar eller ställer in sidfot. |
| [Group](../../aspose.pdf/page/group) { get; set; } | Hämtar eller ställer in en gruppattributklass som anger attributen för sidans sidgrupp för användning i den transparenta bildmodellen. |
| [Header](../../aspose.pdf/page/header) { get; set; } | Hämtar eller ställer in sidhuvud. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | Hämtar eller ställer in tillägg av stycken efter det sista stycket på sidan |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | Hämtar eller ställer in lagersamling. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | Hämtar eller ställer in mediabox för sidan. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | Hämtar eller ställer in linjestilen för noter.(endast för generator) |
| [Number](../../aspose.pdf/page/number) { get; } | Få sidans nummer. |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | Hämtar eller ställer in sidinformationen (endast för generator, fylls inte i vid läsning av fil). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | Hämtar styckena. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | Hämtar eller ställer in sidans rektangel. Sidbeskärningsruta returneras om det anges, annars returneras sidmediabox. Observera att den här egenskapen inte tar hänsyn till sidrotation. För att få sidrektangel med tanke på rotation använd ActualRect. |
| [Resources](../../aspose.pdf/page/resources) { get; } | Hämtar sidresurser. Resursobjekt innehåller samlingar av bilder, formulär och typsnitt. [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | Hämtar eller ställer in rotation av sidan. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | Hämtar transofmationsmatris för sidan. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | Hämtar eller ställer in tabbordning på sidan. Möjliga värden: Rad, Kolumn. Standard, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | Hämtar eller ställer in innehållsförteckningsinformation. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | Hämtar eller ställer in trimruta för sidan. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | Hämtar eller ställer in UserUnit-värdet. Ett positivt tal som anger storleken på standardanvändarutrymmesenheter, i multipler av 1 ⁄ 72 tum. Standardvärdet är 1. Ange noll eller negativt värde för att radera denna post på page. |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | Hämtar eller ställer in sidans vattenstämpel. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | Accepterar[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector) besöksobjekt som ger funktionalitet för att arbeta med anteckningar. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | Accepterar[`ImagePlacementAbsorber`](../imageplacementabsorber) besöksobjekt som ger funktionalitet för att arbeta med bildplaceringsobjekt. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | Accepterar[`TextAbsorber`](../../aspose.pdf.text/textabsorber) besöksobjekt som ger funktionalitet för att arbeta med textobjekt. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | Accepterar[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber) besöksobjekt som ger funktionalitet för att arbeta med textobjekt. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | Lägger till bild på sidan och placerar den i mitten av specificerad rektangel och sparar bildens proportion. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | Lägger till bild på sidan och placerar den i mitten av specificerad rektangel och sparar bildens proportion. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | Lägger till sökbar bild på sidan och placerar den i mitten av den angivna rektangeln och sparar bildens proportion. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | Lägger till bild på sidan och placerar den beroende på bildens rektangelposition. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | Sätt stämpel på sidan. Stämpeln kan vara sidnummer, bild eller enkel text, t.ex. någon logotyp. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | Konverterar aktuell sida som bitmapp och returnerar sedan en array av byte. |
| [AsXml](../../aspose.pdf/page/asxml)() | Konverterar aktuell sida som xml i utf8-kodning. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | Beräknar bbox-värde - rektangel som innehåller innehåll utan synliga marginaler. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | Konvertera sida till PNG för DSR, OMR, OCR bildström. |
| [Dispose](../../aspose.pdf/page/dispose)() | Frigör minne |
| [Flatten](../../aspose.pdf/page/flatten)() | Tar bort alla fält på sidan och placerar deras värden istället. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | Rensar cachad data |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | Returnerar meddelanden om interna operationer med sidinnehåll. (Endast meddelanden om styckehändelser i texttilläggsscenarier stöds nu.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | Returnerar sidans rektangel. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | Får flaggan oavsett om sidan är tom eller inte. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | Konverterar sidan till gråskala. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | Skickar sida att bearbeta med given sidenhet. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | Skickar sida att bearbeta med given sidenhet. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | Anger sidstorlek för sidan. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | Översätter heltalsvärde till motsvarande rotationsuppräkningsmedlem. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | Översätter rotationsuppräkningsmedlem till heltalsvärde. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | Procedur för att anpassa sidhuvud och sidfot. |

### Se även

* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
