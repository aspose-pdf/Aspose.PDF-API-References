---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Page klass. Klass som representerar sidan av PDF-dokumentet
type: docs
weight: 8050
url: /sv/net/aspose.pdf/page/
---
## Sida klass

Klass som representerar sidan av PDF-dokumentet.

```csharp
public sealed class Page : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Hämtar samling av sidans egenskaper. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Hämtar samling av sidans anteckningar. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Hämtar eller ställer in konstlådan för sidan. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Hämtar samling av artefakter på sidan. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Hämtar eller ställer in bakgrundsfärgen för sidan. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Hämtar eller ställer in bakgrundsbild för sidan (endast för generator, inte ifyllt vid läsning av dokument). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Hämtar eller ställer in bleed-boxen för sidan. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Ställer in färgtyp för sidor baserat på information som erhålls från operatörerna SetColor, bilder och formulär. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Hämtar samling av operatörer i innehållsströmmen för sidan. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Hämtar eller ställer in crop-boxen för sidan. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Hämtar eller ställer in sidans visningstid. Detta är tiden i sekunder som sidan ska visas under presentationen. Returnerar -1 om varaktigheten inte är definierad. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Hämtar lista över fältobjekt i tabordning på denna sida. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Hämtar eller ställer in sidfoten. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Hämtar eller ställer in en gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta bildmodellen. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Hämtar eller ställer in sidhuvudet. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Hämtar eller ställer in tillägget av stycken efter det sista stycket på sidan. |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Hämtar eller ställer in samlingen av lager. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Hämtar eller ställer in mediaboxen för sidan. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Hämtar eller ställer in linjestilen för anteckningar. (endast för generator, inte ifyllt vid läsning av dokument) |
| [Number](../../aspose.pdf/page/number/) { get; } | Hämtar sidnumret. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Hämtar eller ställer in sidinformationen (endast för generator, inte ifyllt vid läsning av dokument). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Hämtar styckena. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Hämtar eller ställer in rektangeln för sidan. För get: sidans crop-box returneras om den anges, annars returneras sidans mediabox. För set: sidans mediabox ställs alltid in. Observera att denna egenskap inte tar hänsyn till sidrotation. För att få sidrektangeln med hänsyn till rotation, vänligen använd ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Hämtar sidresurser. Resursobjektet innehåller samlingar av bilder, formulär och typsnitt. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Hämtar eller ställer in rotationen av sidan. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Hämtar transformationsmatrisen för sidan. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Hämtar eller ställer in tabordningen för sidan. Möjliga värden: Rad, Kolumn. Standard, Manuell |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Hämtar eller ställer in information om innehållsförteckningen. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Hämtar eller ställer in trim-boxen för sidan. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Hämtar eller ställer in UserUnit-värdet. Ett positivt tal som ger storleken på standardanvändarutrymmesenheter, i multiplar av 1 / 72 tum. Standardvärdet är 1. Vänligen ställ in noll eller negativt värde för att rensa denna post på sidan. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Hämtar eller ställer in vattenstämpeln för sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Accepterar [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) besöksobjekt som tillhandahåller funktionalitet för att arbeta med anteckningar. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Accepterar [`ImagePlacementAbsorber`](../imageplacementabsorber/) besöksobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringselement. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Accepterar [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) besöksobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Accepterar [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) besöksobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Lägger till grafik på sidan. Fungerar snabbare än att lägga till element ett och ett med [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/) metoden. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Lägger till bild på sidan och placerar den i mitten av den angivna rektangeln och bevarar bildens proportioner. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Lägger till bild på sidan och placerar den i mitten av den angivna rektangeln och bevarar bildens proportioner. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Lägger till sökbar bild på sidan och placerar den i mitten av den angivna rektangeln och bevarar bildens proportioner. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Lägger till bild på sidan och placerar den beroende på bildrektangelns position. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Sätter stämpel på sidan. Stämpeln kan vara sidnummer, bild eller enkel text, t.ex. en logotyp. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Konverterar nuvarande sida till bitmap och returnerar sedan en byte-array. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Konverterar nuvarande sida till xml i utf8-kodning. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Beräknar bbox-värdet - rektangel som innehåller innehållet utan synliga marginaler. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Konverterar sidan till PNG för DSR, OMR, OCR bildström. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Tar bort grafik från sidan. Fungerar snabbare än att ta bort element ett och ett med [`Remove`](../../aspose.pdf.vector/graphicelement/remove/) metoden. |
| [Dispose](../../aspose.pdf/page/dispose/)() | Frigör minne |
| [Flatten](../../aspose.pdf/page/flatten/)() | Tar bort alla fält som finns på sidan och placerar deras värden istället. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Rensar cachelagrad data |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Returnerar meddelanden om interna operationer med sidinnehållet. (Endast meddelanden om stycke-händelser i texttilläggsscenarier stöds nu.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Returnerar rektangeln för sidan enligt dess CropBox (eller MediaBox om CropBox är null). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Hämtar resurser kopplade till sidan. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Upptäck närvaron av vektorgrafik, om den finns på sidan. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Hämtar flaggan om sidan är tom eller inte. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Konverterar sidan till gråskala. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet och valfritt innehållsgrupp-ID. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Ändrar storlek på sidan. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Skickar sidan för att bearbeta med angiven sidapparat. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Skickar sidan för att bearbeta med angiven sidapparat. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Ställer in sidstorlek för sidan. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Försöker spara vektorgrafik om de finns på sidan. Sparaformatet är SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Översätter heltalsvärde till motsvarande rotationsenumerationsmedlem. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Översätter rotationsenumerationsmedlem till heltalsvärde. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Händelse för att anpassa sidhuvud och sidfot. |

## Andra Medlemmar

| Namn | Beskrivning |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Procedur för att anpassa sidhuvud och sidfot. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)