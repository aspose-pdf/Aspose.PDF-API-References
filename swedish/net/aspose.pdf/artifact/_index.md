---
title: "Klass Artifact"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Artifact-klass. Klassen representerar PDF Artifact‑objekt."
type: docs
weight: 2870
url: /sv/net/aspose.pdf/artifact/
---
## Artifact class

Klassen representerar PDF Artifact-objekt.

```csharp
public class Artifact : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | Konstruktor för artifact med angiven typ och subtyp. |
| [Artifact](artifact/#constructor_1)(string, string) | Konstruktor för artifact med angiven typ och subtyp. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horisontell justering av artefakt. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikal justering av artefakt. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Bottenmarginal för artefakt. Om position anges explicit (i Position-egenskapen) ignoreras detta värde. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Hämtar samling av artefaktens interna operatorer. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Hämtar namn på artefaktens undertyp. Kan användas om artefaktens undertyp inte är en standardundertyp. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Hämtar namn på artefaktens typ. Kan användas om artefaktens typ är icke-standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Hämtar XForm för artefakten (om XForm används). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Hämtar bild av artefakten (om den finns). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Om sant placeras artefakten bakom sidans innehåll. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Vänster marginal för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Rader i flerradig textartefakt. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Hämtar eller anger opaciteten för artefakten. Möjliga värden är i intervallet 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Hämtar eller anger artefaktens position. Om denna egenskap anges, ignoreras marginaler och justeringar. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Hämtar rektangeln för artefakten. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Höger marginal för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Hämtar eller anger artefaktens rotationsvinkel. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Hämtar artefaktens undertyp. Om artefakten har en icke-standard undertyp kan namnet på undertypen läsas via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Hämtar texten för artefakten. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Texttillstånd för artefaktens text. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Övre marginal för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Hämtar artefaktens typ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Starta försenade uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatorer varje gång en artefakt‑egenskap ändras. Detta leder till att sidans innehåll ändras varje gång artefakten ändras. För att undvika detta, placera alla artefaktuppdateringar mellan anropen StartUpdates/SaveUpdates. Detta möjliggör att sidans innehåll bara ändras en gång. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Frigör artefakten. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Hämtar anpassat värde för artefakten. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Tar bort anpassat värde från artefakten. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Sparar alla uppdateringar i artefakten som gjorts efter anropet BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | Anger bild för artefakten. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | Anger bild för artefakten. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Anger text och textegenskaper för artefakten. Tillåter att ange flera rader. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Anger vilken sträng som ska ersättas med sidnumret. Standardvärdet är #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Anger PDF‑sida som placeras på dokumentets sida som artefakt. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Ställer in text för artefakten. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Ställer in text och textegenskaper för artefakten. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Ställer in anpassat värde för artefakten. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | Enumeration av möjliga artifact‑subtyper. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | Uppräkning av möjliga artefakttyper. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


