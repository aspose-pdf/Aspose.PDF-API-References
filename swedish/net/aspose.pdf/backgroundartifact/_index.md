---
title: Class BackgroundArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BackgroundArtifact klass. Klassen beskriver bakgrundsartefakt. Denna artefakt gör det möjligt att ställa in bakgrunden för sidan
type: docs
weight: 2810
url: /sv/net/aspose.pdf/backgroundartifact/
---
## BackgroundArtifact klass

Klassen beskriver bakgrundsartefakt. Denna artefakt gör det möjligt att ställa in bakgrunden för sidan.

```csharp
public class BackgroundArtifact : Artifact
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [BackgroundArtifact](backgroundartifact/)() | Initierar BackgroundArtifact-objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horisontell justering av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikal justering av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [BackgroundColor](../../aspose.pdf/backgroundartifact/backgroundcolor/) { get; set; } | Hämtar eller ställer in bakgrundsfärgen för bakgrundsartefakten |
| [BackgroundImage](../../aspose.pdf/backgroundartifact/backgroundimage/) { get; set; } | Hämtar eller ställer in bakgrundsbilden för bakgrundsartefakten |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Nedre marginal av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Hämtar samlingen av interna operatörer för artefakt. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Hämtar namnet på artefaktens subtype. Kan användas om artefaktens subtype inte är en standard-subtype. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Hämtar namnet på artefaktens typ. Kan användas om artefaktens typ är icke-standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Hämtar XForm för artefakten (om XForm används). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Hämtar bilden av artefakten (om den finns). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Om sant placeras artefakten bakom sidinnehållet. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Vänster marginal av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linjer av flerlinjig textartefakt. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Hämtar eller ställer in opaciteten för artefakten. Möjliga värden ligger i intervallet 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Hämtar eller ställer in artefaktens position. Om denna egenskap anges, ignoreras marginaler och justeringar. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Hämtar rektangeln för artefakten. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Höger marginal av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Hämtar eller ställer in artefaktens rotationsvinkel. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Hämtar artefaktens subtype. Om artefakten har en icke-standard subtype kan namnet på subtypen läsas via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Hämtar texten för artefakten. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Textstatus för artefaktens text. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Övre marginal av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Hämtar artefaktens typ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Starta fördröjda uppdateringar. Använd denna funktion om du behöver göra flera ändringar i samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatörer varje gång en artefaktegenskap ändras. Detta orsakar att sidinnehållet ändras varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta gör att sidinnehållet endast kan ändras en gång. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Avyttra artefakten. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Hämtar anpassat värde av artefakten. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Tar bort anpassat värde från artefakten. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Sparar alla uppdateringar i artefakten som gjordes efter anropet av BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Ställer in bilden av artefakten. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Ställer in bilden av artefakten. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Ställer in text och textegenskaper för artefakten. Gör det möjligt att specificera flera rader. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Ställer in vilken sträng som ska ersättas med sidnumret. Standardvärdet är #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Ställer in PDF-sidan som placeras på dokumentets sida som artefakt. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Ställer in texten för artefakten. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Ställer in text och textegenskaper för artefakten. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Ställer in anpassat värde av artefakten. |

### Se Även

* klass [Artifact](../artifact/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)