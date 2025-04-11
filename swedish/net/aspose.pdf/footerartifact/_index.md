---
title: Class FooterArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FooterArtifact klass. Beskriver fotartefakt. Detta kan användas för att ställa in sidfoten
type: docs
weight: 4930
url: /sv/net/aspose.pdf/footerartifact/
---
## FooterArtifact klass

Beskriver fotartefakt. Detta kan användas för att ställa in sidfoten.

```csharp
public class FooterArtifact : Artifact
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FooterArtifact](footerartifact/)() | Skapar en instans av Footer Artifact. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horisontell justering av artefakten. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikal justering av artefakten. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Nedre marginal av artefakten. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Hämtar samlingen av interna operatörer för artefakten. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Hämtar namnet på artefaktens undertyp. Kan användas om artefaktens undertyp inte är en standardundertyp. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Hämtar namnet på artefaktens typ. Kan användas om artefaktens typ är icke-standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Hämtar XForm av artefakten (om XForm används). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Hämtar bilden av artefakten (om den finns). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Om sant placeras artefakten bakom sidinnehållet. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Vänster marginal av artefakten. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linjer av flerradig textartefakt. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Hämtar eller ställer in opaciteten av artefakten. Möjliga värden ligger i intervallet 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Hämtar eller ställer in artefaktens position. Om denna egenskap anges, ignoreras marginaler och justeringar. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Hämtar rektangeln av artefakten. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Höger marginal av artefakten. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Hämtar eller ställer in artefaktens rotationsvinkel. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Hämtar artefaktens undertyp. Om artefakten har en icke-standard undertyp kan namnet på undertypen läsas via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Hämtar texten av artefakten. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Texttillstånd för artefaktens text. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Övre marginal av artefakten. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
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
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Ställer in text och textegenskaper för artefakten. Möjliggör att specificera flera rader. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Ställer in vilken sträng som kommer att ersättas med sidnumret. Standardvärdet är #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Ställer in PDF-sidan som placeras på dokumentets sida som artefakt. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Ställer in texten av artefakten. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Ställer in text och textegenskaper för artefakten. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Ställer in anpassat värde av artefakten. |

### Se Även

* klass [Artifact](../artifact/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)