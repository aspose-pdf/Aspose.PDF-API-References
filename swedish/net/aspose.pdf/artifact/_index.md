---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Artifact klass. Klassen representerar PDF Artifact-objekt
type: docs
weight: 2770
url: /sv/net/aspose.pdf/artifact/
---
## Artifact klass

Klassen representerar PDF Artifact-objekt.

```csharp
public class Artifact : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | Konstruktör för artifact med angiven typ och subtype |
| [Artifact](artifact/#constructor_1)(string, string) | Konstruktör för artifact med angiven typ och subtype |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horisontell justering av artifact. Om position anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikal justering av artifact. Om position anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Nedre marginal av artifact. Om position anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Hämtar samling av artifact interna operatörer. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Hämtar namnet på artifact subtype. Kan användas om artifact subtype inte är standard subtype. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Hämtar namnet på artifact typ. Kan användas om artifact typ är icke-standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Hämtar XForm av artifact (om XForm används). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Hämtar bilden av artifact (om den finns). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Om sant placeras artifact bakom sidinnehållet. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Vänster marginal av artifact. Om position anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linjer av flerlinjig text artifact. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Hämtar eller ställer in opacitet av artifact. Möjliga värden ligger i intervallet 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Hämtar eller ställer in artifact position. Om denna egenskap anges, ignoreras då marginaler och justeringar. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Hämtar rektangeln av artifact. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Höger marginal av artifact. Om position anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Hämtar eller ställer in artifact rotationsvinkel. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Hämtar artifact subtype. Om artifact har en icke-standard subtype kan namnet på subtypen läsas via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Hämtar texten av artifact. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Textstatus för artifact text. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Övre marginal av artifact. Om position anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Hämtar artifact typ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Starta fördröjda uppdateringar. Använd denna funktion om du behöver göra flera ändringar i samma artifact för att förbättra prestanda. Vanligtvis ändras artifact-operatörer varje gång en artifact-egenskap ändras. Detta orsakar att sidinnehållet ändras varje gång artifact ändras. För att undvika denna effekt, placera alla artifact-uppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta gör att sidinnehållet endast ändras en gång. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Avyttra artifact. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Hämtar anpassat värde av artifact. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Tar bort anpassat värde från artifact. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Sparar alla uppdateringar i artifact som gjordes efter anropet av BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | Ställer in bilden av artifact. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | Ställer in bilden av artifact. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Ställer in text och textegenskaper för artifact. Möjliggör att specificera flera linjer. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Ställer in vilken sträng som kommer att ersättas med sidnumret. Standardvärdet är #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Ställer in PDF-sidan som placeras på dokumentets sida som artifact. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Ställer in texten av artifact. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Ställer in text och textegenskaper för artifact. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Ställer in anpassat värde av artifact. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | Uppräkning av möjliga artifact subtyper. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | Uppräkning av möjliga artifact typer. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)