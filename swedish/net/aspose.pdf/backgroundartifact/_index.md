---
title: BackgroundArtifact
second_title: Aspose.PDF för .NET API Referens
description: Klass beskriver bakgrundsartefakt. Denna artefakt gör det möjligt att ställa in bakgrunden för sidan.
type: docs
weight: 1350
url: /sv/net/aspose.pdf/backgroundartifact/
---
## BackgroundArtifact class

Klass beskriver bakgrundsartefakt. Denna artefakt gör det möjligt att ställa in bakgrunden för sidan.

```csharp
public class BackgroundArtifact : Artifact
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BackgroundArtifact](backgroundartifact)() | Initierar BackgroundArtifact-objekt. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment) { get; set; } | Horisontell justering av artefakt. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment) { get; set; } | Vertikal justering av artefakt. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [BackgroundColor](../../aspose.pdf/backgroundartifact/backgroundcolor) { get; set; } | Hämtar eller ställer in bakgrundsfärg för bakgrundsartefakt |
| [BackgroundImage](../../aspose.pdf/backgroundartifact/backgroundimage) { get; set; } | Hämtar eller ställer in bakgrundsbild av bakgrundsartefakt |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin) { get; set; } | Artefaktens nedre marginal. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [Contents](../../aspose.pdf/artifact/contents) { get; } | Får en samling av artefakt interna operatorer. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype) { get; set; } | Får namn på artefaktundertyp. Kan användas om artefaktsubtypen inte är standardsubtypen. |
| [CustomType](../../aspose.pdf/artifact/customtype) { get; set; } | Får namn på artefakttyp. Kan användas om artefakttypen inte är standard. |
| [Form](../../aspose.pdf/artifact/form) { get; } | Hämtar XForm av artefakten (om XForm används). |
| [Image](../../aspose.pdf/artifact/image) { get; } | Får bild av artefakten (om den finns). |
| [IsBackground](../../aspose.pdf/artifact/isbackground) { get; set; } | Om true Artifact placeras bakom sidinnehållet. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin) { get; set; } | Vänster marginal på artefakten. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [Lines](../../aspose.pdf/artifact/lines) { get; } | Rader med flerradstextartefakt. |
| [Opacity](../../aspose.pdf/artifact/opacity) { get; set; } | Hämtar eller ställer in opaciteten för artefakten. Möjliga värden ligger inom intervallet 0..1. |
| [Position](../../aspose.pdf/artifact/position) { get; set; } | Hämtar eller ställer in artefaktposition. Om den här egenskapen anges ignoreras marginaler och justeringar. |
| [Rectangle](../../aspose.pdf/artifact/rectangle) { get; } | Hämtar rektangel av artefakten. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin) { get; set; } | Höger marginal av artefakt. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [Rotation](../../aspose.pdf/artifact/rotation) { get; set; } | Hämtar eller ställer in artefaktrotationsvinkel. |
| [Subtype](../../aspose.pdf/artifact/subtype) { get; set; } | Hämtar artefaktundertyp. Om artefakten har en icke-standard undertyp, kan namnet på undertypen läsas via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text) { get; set; } | Hämtar text av artefakten. |
| [TextState](../../aspose.pdf/artifact/textstate) { get; set; } | Texttillstånd för artefakttext. |
| [TopMargin](../../aspose.pdf/artifact/topmargin) { get; set; } | Artefaktens övre marginal. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [Type](../../aspose.pdf/artifact/type) { get; set; } | Hämtar artefakttyp. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates)() | Starta borttagna uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestandan. Vanligtvis ändras artefaktoperatorer när som helst när artefaktegenskapen ändrades. Detta gör att sidans innehåll ändras varje gång artefakten ändrades. För att undvika denna effekt placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta gör det möjligt att ändra sidinnehåll endast en gång. |
| [Dispose](../../aspose.pdf/artifact/dispose)() | Kasta artefakten. |
| [GetValue](../../aspose.pdf/artifact/getvalue)(string) | Får anpassat värde för artefakt. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue)(string) | Ta bort anpassat värde från artefakten. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates)() | Sparar alla uppdateringar i artefakt som gjordes efter BeginUpdates()-anrop. |
| [SetImage](../../aspose.pdf/artifact/setimage)(Stream) | Ställer in bilden av artefakten. |
| [SetImage](../../aspose.pdf/artifact/setimage)(string) | Ställer in bilden av artefakten. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate)(string[], TextState) | Ställ in text- och textegenskaper för artefakten. Tillåter att ange flera rader. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage)(Page) | Anger PDF-sida som placeras på dokumentsidan som artefakt. |
| [SetText](../../aspose.pdf/artifact/settext)(FormattedText) | Ställer in text för artefakten. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate)(string, TextState) | Ställ in text- och textegenskaper för artefakten. |
| [SetValue](../../aspose.pdf/artifact/setvalue)(string, string) | Anger anpassat värde för artefakt. |

### Se även

* class [Artifact](../artifact)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
