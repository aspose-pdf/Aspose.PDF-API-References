---
title: Class BatesNArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BatesNArtifact klass. Klassen beskriver Bates numrering artefakt
type: docs
weight: 2850
url: /sv/net/aspose.pdf/batesnartifact/
---
## BatesNArtifact klass

Klassen beskriver Bates numrering artefakt.

```csharp
public class BatesNArtifact : PaginationArtifact
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [BatesNArtifact](batesnartifact/)() | Initierar en ny instans av `BatesNArtifact` klassen. Denna konstruktor är intern och skapar en header artefakt instans med standardvärden. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horisontell justering av artefakt. Om position anges uttryckligen (i Position egenskap) ignoreras detta värde. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikal justering av artefakt. Om position anges uttryckligen (i Position egenskap) ignoreras detta värde. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Bottenmarginal av artefakt. Om position anges uttryckligen (i Position egenskap) ignoreras detta värde. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Hämtar samling av artefaktens interna operatörer. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Hämtar namnet på artefaktens subtype. Kan användas om artefaktens subtype inte är standard subtype. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Hämtar namnet på artefaktens typ. Kan användas om artefaktens typ är icke-standard. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | Hämtar eller ställer in slutnummer för artefakten. Värdet måste vara större än eller lika med 0. Om ett värde mindre än 0 anges, justeras det till 0. Standardvärdet 0 betyder att det inte finns några slutgränser. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Hämtar XForm av artefakten (om XForm används). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Hämtar bild av artefakten (om den finns). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Om sant placeras artefakten bakom sidinnehållet. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Vänster marginal av artefakt. Om position anges uttryckligen (i Position egenskap) ignoreras detta värde. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linjer av flerlinjig text artefakt. |
| [NumberOfDigits](../../aspose.pdf/batesnartifact/numberofdigits/) { get; set; } | Hämtar eller ställer in antalet siffror för Bates numrering. Värdet måste vara mellan 3 och 15 inklusive. Om ett värde mindre än 3 anges, justeras det till 3. Om ett värde större än 15 anges, justeras det till 15. Standardvärdet är 6. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Hämtar eller ställer in opacitet av artefakten. Möjliga värden ligger i intervallet 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Hämtar eller ställer in artefaktens position. Om denna egenskap anges, ignoreras marginaler och justeringar. |
| [Prefix](../../aspose.pdf/batesnartifact/prefix/) { get; set; } | Hämtar eller ställer in prefixet som ska läggas till Bates numret. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Hämtar rektangeln av artefakten. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Höger marginal av artefakt. Om position anges uttryckligen (i Position egenskap) ignoreras detta värde. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Hämtar eller ställer in artefaktens rotationsvinkel. |
| [StartNumber](../../aspose.pdf/batesnartifact/startnumber/) { get; set; } | Hämtar eller ställer in startnumret för Bates numrering. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | Hämtar eller ställer in startsidnumret för artefakten. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | Hämtar eller ställer in delmängden av sidor som artefakten gäller (t.ex. alla sidor, jämna sidor, udda sidor). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Hämtar artefaktens subtype. Om artefakten har en icke-standard subtype, kan namnet på subtypen läsas via CustomSubtype. |
| [Suffix](../../aspose.pdf/batesnartifact/suffix/) { get; set; } | Hämtar eller ställer in suffixet som ska läggas till Bates numret. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Hämtar texten av artefakten. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Textstatus för artefaktens text. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Toppmarginal av artefakt. Om position anges uttryckligen (i Position egenskap) ignoreras detta värde. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Hämtar artefaktens typ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Starta fördröjda uppdateringar. Använd denna funktion om du behöver göra flera ändringar i samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatörer varje gång när artefaktens egenskap ändras. Detta orsakar att sidinnehållet ändras varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates anrop. Detta gör att sidinnehållet endast kan ändras en gång. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Avyttra artefakten. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Hämtar anpassat värde av artefakten. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Tar bort anpassat värde från artefakten. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Sparar alla uppdateringar i artefakten som gjordes efter anropet av BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Sätter bilden av artefakten. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Sätter bilden av artefakten. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Sätter text och text egenskaper av artefakten. Möjliggör att specificera flera linjer. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Sätter vilken sträng som kommer att ersättas med sidnumret. Standardvärdet är #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Sätter PDF-sidan som placeras på dokumentets sida som artefakt. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Sätter texten av artefakten. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Sätter text och text egenskaper av artefakten. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Sätter anpassat värde av artefakten. |

### Se Även

* klass [PaginationArtifact](../paginationartifact/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)