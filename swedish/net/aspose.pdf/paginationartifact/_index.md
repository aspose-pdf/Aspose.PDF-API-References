---
title: Class PaginationArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PaginationArtifact klass. Representerar en abstrakt basklass för pagineringsartefakter i ett dokument
type: docs
weight: 8260
url: /sv/net/aspose.pdf/paginationartifact/
---
## PaginationArtifact klass

Representerar en abstrakt basklass för pagineringsartefakter i ett dokument.

```csharp
public abstract class PaginationArtifact : Artifact
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horisontell justering av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikal justering av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Nedre marginal av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Hämtar samling av interna operatörer för artefakt. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Hämtar namnet på artefaktens undertyp. Kan användas om artefaktens undertyp inte är en standardundertyp. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Hämtar namnet på artefaktens typ. Kan användas om artefaktens typ är icke-standard. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | Hämtar eller ställer in slutnummer för artefakt. Värdet måste vara större än eller lika med 0. Om ett värde mindre än 0 anges, justeras det till 0. Standardvärdet 0 betyder att det inte finns några slutgränser. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Hämtar XForm för artefakt (om XForm används). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Hämtar bild av artefakt (om den finns). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Om sant placeras artefakt bakom sidinnehållet. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Vänster marginal av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Rader av flerlinjig textartefakt. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Hämtar eller ställer in opacitet för artefakt. Möjliga värden ligger i intervallet 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Hämtar eller ställer in artefaktens position. Om denna egenskap anges, ignoreras marginaler och justeringar. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Hämtar rektangel av artefakt. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Höger marginal av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Hämtar eller ställer in artefaktens rotationsvinkel. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | Hämtar eller ställer in startnummer för artefakt. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | Hämtar eller ställer in delmängden av sidor som artefakt gäller för (t.ex. alla sidor, jämna sidor, udda sidor). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Hämtar artefaktens undertyp. Om artefakten har en icke-standard undertyp kan namnet på undertypen läsas via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Hämtar texten av artefakt. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Textstatus för artefaktens text. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Övre marginal av artefakt. Om positionen anges uttryckligen (i Position-egenskapen) ignoreras detta värde. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Hämtar artefaktens typ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Starta fördröjda uppdateringar. Använd denna funktion om du behöver göra flera ändringar i samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatörer varje gång en artefaktegenskap ändras. Detta orsakar att sidinnehållet ändras varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta gör att sidinnehållet endast kan ändras en gång. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Avyttra artefakt. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Hämtar anpassat värde av artefakt. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Tar bort anpassat värde från artefakt. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Sparar alla uppdateringar i artefakt som gjordes efter anropet av BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Ställer in bild av artefakt. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Ställer in bild av artefakt. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Ställer in text och textegenskaper för artefakt. Möjliggör att specificera flera rader. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Ställer in vilken sträng som ska ersättas med sidnumret. Standardvärdet är #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Ställer in PDF-sidan som placeras på dokumentets sida som artefakt. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Ställer in texten av artefakt. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Ställer in text och textegenskaper för artefakt. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Ställer in anpassat värde av artefakt. |

### Se Även

* klass [Artifact](../artifact/)
* namnrum [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)