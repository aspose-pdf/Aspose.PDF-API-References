---
title: "Klass Page"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Page klass. Klass som representerar en sida i ett PDF‑dokument"
type: docs
weight: 8190
url: /sv/net/aspose.pdf/page/
---
## Page class

Klass som representerar en sida i ett PDF-dokument.

```csharp
public sealed class Page : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Hämtar samling av sidegenskaper. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Hämtar samling av sidannoteringar. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Hämtar eller anger art‑boxen för sidan. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Hämtar samling av artefakter på page. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Hämtar eller anger bakgrundsfärgen för page. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Hämtar eller anger bakgrundsbild för sidan (endast för generator, inte ifylld vid läsning av dokument). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Hämtar eller anger blödningsruta för page. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Anger färgtyp för sidor baserat på information hämtad från operatorer SetColor, bilder och formulär. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Hämtar samling av operatorer i innehållsströmmen för page. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Hämtar eller anger beskärningsruta för page. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Hämtar eller anger sidvisningens varaktighet. Detta är tiden i sekunder som page ska visas under presentationen. Returnerar -1 om varaktigheten inte är definierad. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Hämtar lista över Field-objekt i Tab-ordning på denna page. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Hämtar eller anger sidfot för page. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Hämtar eller anger en gruppattributklass som specificerar attributen för page's sidgrupp för användning i den transparenta bildmodellen. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Hämtar eller anger sidhuvud för page. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Hämtar eller anger tillägg av stycken efter sista stycket på page |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Hämtar eller anger lagerkollektion. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Hämtar eller anger mediabox för page. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Hämtar eller anger linjestil för anteckningar. (endast för generator, fylls inte i vid läsning av Document) |
| [Number](../../aspose.pdf/page/number/) { get; } | Hämta nummer för page. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Hämtar eller anger page‑info (endast för generator, fylls inte i vid läsning av Document). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Hämtar styckena. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Hämtar eller anger rektangel för page. Vid hämtning: page‑beskärningsruta returneras om angiven, annars returneras page‑mediabox. Vid angivning: page‑mediabox sätts alltid. Observera att denna egenskap inte beaktar page‑rotation. För att hämta page‑rektangel med rotation, använd ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Hämtar page‑resurser. Resources‑objektet innehåller samlingar av bilder, formulär och teckensnitt. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Hämtar eller anger rotation för page. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Hämtar transofmation‑matris för page. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Hämtar eller anger tab‑ordning för page. Möjliga värden: Row, Column. Standard, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Hämtar eller anger innehållsförteckningsinfo. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Hämtar eller anger trim‑ruta för page. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Hämtar eller anger UserUnit‑värde. Ett positivt tal som anger storleken på standardenheter i användarutrymmet, i multiplar av 1 / 72 tum. Standardvärdet är 1. Ange noll eller ett negativt värde för att rensa detta fält på sidan. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Hämtar eller anger vattenstämpeln för sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Accepterar [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Accepterar [`ImagePlacementAbsorber`](../imageplacementabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Accepterar [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Accepterar [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Lägger till grafik på sidan. Är snabbare än att lägga till element ett i taget med metoden [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Lägger till en bild på sidan och placerar den beroende på bildens rektangelposition. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Sätt en stämpel på sidan. Stämpeln kan vara sidnummer, bild eller enkel text, t.ex. en logotyp. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Konverterar aktuell sida till bitmap och returnerar sedan en byte‑array. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Konverterar aktuell sida till XML med UTF‑8‑kodning. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Beräknar bbox‑värdet – en rektangel som innehåller innehållet utan synliga marginaler. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Konvertera page till PNG för DSR-, OMR- och OCR‑bildström. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Tar bort grafik från sidan. Är snabbare än att ta bort element ett i taget med metoden [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Frigör minne |
| [Flatten](../../aspose.pdf/page/flatten/)() | Tar bort alla fält som finns på sidan och placerar deras värden istället. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Rensar cachad data |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Returnerar aviseringar om interna operationer med sidinnehåll. (Endast aviseringar om stycke‑händelser i scenarier för texttillägg stöds för närvarande.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Returnerar rektangeln för sidan enligt dess CropBox (eller MediaBox om CropBox är null). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Hämtar resurserna som är associerade med sidan. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Detekterar förekomsten av vektorgrafik, om den finns på sidan. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Hämtar flaggan som anger om sidan är tom eller inte. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Konverterar sidan till gråskala. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Slår ihop alla lager på sidan till ett enda lager med det angivna nya lagernamnet. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Slår ihop alla lager på sidan till ett enda lager med det angivna nya lagernamnet och valfritt innehållsgrupp‑Id. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Ändrar storlek på sidan. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Skickar sidan till bearbetning med given sid-enhet. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Skickar sidan till bearbetning med given sid-enhet. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Ställer in sidstorlek för sidan. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Försöker spara vektorgrafik om den finns på sidan. Sparaformatet är SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Översätter heltalsvärde till motsvarande rotations‑enumerationsmedlem. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Översätter rotationsenummedlem till heltalsvärde. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Händelse för att anpassa sidhuvud och sidfot. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Procedur för att anpassa rubrik och sidfot. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


