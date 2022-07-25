---
title: DocSaveOptions
second_title: Aspose.PDF för .NET API Referens
description: Spara alternativ för export till Doc format
type: docs
weight: 1840
url: /sv/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Spara alternativ för export till Doc format

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [DocSaveOptions](docsaveoptions)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend) { get; set; } | Använd stycke- eller radbrytningar |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize) { get; set; } | Definierar batchstorlek om batchkonvertering är tillämplig till käll- och målformatpar. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Hämtar eller ställer in booleskt värde som indikerar kommer Response-objektet att stängas efter att dokumentet har sparats i respons. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Det här attributet aktiverade funktionalitet för att extrahera bild eller text för PDF-dokument med OCR-underlager. |
| [Format](../../aspose.pdf/docsaveoptions/format) { get; set; } | Utdataformat |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx) { get; set; } | Konverterade bilder X upplösning. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony) { get; set; } | Konverterade bilder Y-upplösning. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines) { get; set; } | Den här parametern används för att gruppera textrader i stycken. Bestämmer hur långt från varandra som kan vara två relativa textrader. Anges i hundratals procent av textradernas höjd. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath) { get; set; } | Definierar sökvägen (filnamn eller katalognamn) till hold temporär data vid konvertering i minnessparläge. |
| [Mode](../../aspose.pdf/docsaveoptions/mode) { get; set; } | Igenkänningsläge. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets) { get; set; } | Slå på igenkänningen av kulor |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity) { get; set; } | I Pdf kan ord representeras internt med operatorer som skriver ut words genom att oberoende skriva ut deras bokstäver eller stavelser. Så för att upptäcka ord behöver vi ibland detektera grupper av oberoende tecken som i själva verket är ord. Den här inställningen definierar utrymmets bredd mellan textelement (bokstäver, stavelser) som måste behandlas som avstånd mellan ord under igenkänning av ord i käll-PDF . (närvaro av tomt utrymme åtminstone med denna bredd mellan bokstäverna betyder att textelement hänför sig till olika ord). Det är normerat till teckenstorlek - 1.0 betyder 100 % av det antagna ordets teckenstorlek. används endast i fall! när käll-PDF innehåller specifika sällan använda fonts för vilka optimalt värde inte kan beräknas från font. Så i de allra flesta fall ändrar denna parameter ingenting i resultatdokumentet. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Format för att spara data. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction enum-objektet som anger antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och åtgärden Spara fortsätter, men användaren kan också returnera Avbryt i vilket fall åtgärden Spara bör upphöra. |

## Fält

| namn | Beskrivning |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler) | Denna hanterare kan användas för att hantera konverteringsförloppshändelser fe den kan användas för att visa förloppsindikator eller meddelanden om aktuell mängd av bearbetade sidor, exempel på hanterarens kod som visar framsteg på konsolen är: |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) konstruerade av flera samma sida vid sida bakgrundsbilder placerade nära varandra. I sådana fall genererar renderare av målformat (t.ex. MsWord för DOCS-format) ibland synliga gränser av bakgrundsbilder mellan delar av bakgrundsbilder , orsakar att deras tekniker för bildkantsutjämning (kantutjämning) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med oönskad effekt. OBS! Denna optimering av kvalitet saktar vanligtvis ner konverteringen, så använd det här alternativet endast när det verkligen är nödvändigt. |

### Se även

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
