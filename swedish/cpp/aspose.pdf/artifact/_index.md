---
title: "Aspose::Pdf::Artifact-klass"
linktitle: "Artifact"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Artifact-klass. Klassen representerar PDF Artifact-objekt i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf/artifact/
---
## Artifact class


Klassen representerar PDF [Artifact](./)-objekt.

```cpp
class Artifact : public System::IDisposable
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [ArtifactSubtype](./artifactsubtype/) | Enumeration av möjliga artefaktsundertyper. |
| [ArtifactType](./artifacttype/) | Enumeration av möjliga artefakttyper. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Artifact](./artifact/)(const System::String\&, const System::String\&) | Konstruktor för artefakt med angiven typ och undertyp. |
| [Artifact](./artifact/)(Artifact::ArtifactType, Artifact::ArtifactSubtype) | Konstruktor för artefakt med angiven typ och undertyp. |
| [BeginUpdates](./beginupdates/)() | Starta försenade uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatorer när artefaktens egenskap ändras. Detta orsakar att sidinnehållet ändras varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta möjliggör att sidinnehållet bara ändras en gång. |
| [Dispose](./dispose/)() override | Frigör artefakten. |
| [get_ArtifactHorizontalAlignment](./get_artifacthorizontalalignment/)() const | Horisontell justering av artefakt. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [get_ArtifactVerticalAlignment](./get_artifactverticalalignment/)() const | Vertikal justering av artefakt. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [get_BottomMargin](./get_bottommargin/)() const | Bottenmarginal för artefakt. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [get_Contents](./get_contents/)() | Hämtar samling av artefaktens interna operatorer. |
| [get_CustomSubtype](./get_customsubtype/)() | Hämtar namn på artefaktens undertyp. Kan användas om artefaktens undertyp inte är standard. |
| [get_CustomType](./get_customtype/)() | Hämtar namn på artefaktens typ. Kan användas om artefaktens typ är icke-standard. |
| [get_Form](./get_form/)() | Hämtar [XForm](../xform/) för artefakten (om [XForm](../xform/) används). |
| [get_Image](./get_image/)() | Hämtar bild av artefakten (om den finns). |
| [get_IsBackground](./get_isbackground/)() const | Om sant placeras [Artifact](./) bakom sidinnehållet. |
| [get_LeftMargin](./get_leftmargin/)() const | [Left](../left/) marginal för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [get_Lines](./get_lines/)() | Rader i flerradig textartefakt. |
| [get_Opacity](./get_opacity/)() const | Hämtar opaciteten för artefakten. Möjliga värden är i intervallet 0..1. |
| [get_Position](./get_position/)() const | Hämtar artefaktens position. Om denna egenskap är angiven ignoreras marginaler och justeringar. |
| [get_Rectangle](./get_rectangle/)() | Hämtar rektangeln för artefakten. |
| [get_RightMargin](./get_rightmargin/)() const | [Right](../right/) marginal för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [get_Rotation](./get_rotation/)() | Hämtar artefaktens rotationsvinkel. |
| [get_Subtype](./get_subtype/)() | Hämtar artefaktens undertyp. Om artefakten har en icke-standard undertyp kan namnet på undertypen läsas via CustomSubtype. |
| [get_Text](./get_text/)() | Hämtar texten för artefakten. |
| [get_TextState](./get_textstate/)() | [Text](../../aspose.pdf.text/) tillstånd för artefaktens text. |
| [get_TopMargin](./get_topmargin/)() const | Topmargin för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [get_Type](./get_type/)() | Hämtar artefaktens typ. |
| [GetValue](./getvalue/)(const System::String\&) | Hämtar anpassat värde för artefakten. |
| [RemoveValue](./removevalue/)(const System::String\&) | Ta bort anpassat värde från artefakten. |
| [SaveUpdates](./saveupdates/)() | Sparar alla uppdateringar i artefakten som gjordes efter anropet av [BeginUpdates()](./beginupdates/). |
| [set_ArtifactHorizontalAlignment](./set_artifacthorizontalalignment/)(HorizontalAlignment) | Horisontell justering av artefakt. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [set_ArtifactVerticalAlignment](./set_artifactverticalalignment/)(VerticalAlignment) | Vertikal justering av artefakt. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [set_BottomMargin](./set_bottommargin/)(double) | Bottenmarginal för artefakt. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [set_CustomSubtype](./set_customsubtype/)(const System::String\&) | Hämtar namn på artefaktens undertyp. Kan användas om artefaktens undertyp inte är standard. |
| [set_CustomType](./set_customtype/)(const System::String\&) | Hämtar namn på artefaktens typ. Kan användas om artefaktens typ är icke-standard. |
| [set_IsBackground](./set_isbackground/)(bool) | Om sant placeras [Artifact](./) bakom sidinnehållet. |
| [set_LeftMargin](./set_leftmargin/)(double) | [Left](../left/) marginal för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [set_Opacity](./set_opacity/)(double) | Ställer in opaciteten för artefakten. Möjliga värden ligger i intervallet 0..1. |
| [set_Position](./set_position/)(const System::SharedPtr\<Point\>\&) | Ställer in artefaktens position. Om den här egenskapen anges ignoreras marginaler och justeringar. |
| [set_RightMargin](./set_rightmargin/)(double) | [Right](../right/) marginal för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [set_Rotation](./set_rotation/)(double) | Ställer in artefaktens rotationsvinkel. |
| [set_Subtype](./set_subtype/)(Artifact::ArtifactSubtype) | Hämtar artefaktens undertyp. Om artefakten har en icke-standard undertyp kan namnet på undertypen läsas via CustomSubtype. |
| [set_Text](./set_text/)(const System::String\&) | Hämtar texten för artefakten. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | [Text](../../aspose.pdf.text/) tillstånd för artefaktens text. |
| [set_TopMargin](./set_topmargin/)(double) | Topmargin för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [set_Type](./set_type/)(Artifact::ArtifactType) | Hämtar artefaktens typ. |
| [SetImage](./setimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in bilden för artefakten. |
| [SetImage](./setimage/)(const System::String\&) | Ställer in bilden för artefakten. |
| [SetLinesAndState](./setlinesandstate/)(const System::ArrayPtr\<System::String\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Ställ in text och textegenskaper för artefakten. Tillåter att ange flera rader. |
| [SetPageNumberReplacementString](./setpagenumberreplacementstring/)(const System::String\&) | Anger vilken sträng som kommer att ersättas med sidnumret. Standardvärdet är #. |
| [SetPdfPage](./setpdfpage/)(const System::SharedPtr\<Page\>\&) | Ställer in PDF-sida som placeras på dokumentsidan som artefakt. |
| [SetText](./settext/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Ställer in texten för artefakten. |
| [SetTextAndState](./settextandstate/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Ställ in text och textegenskaper för artefakten. |
| [SetValue](./setvalue/)(const System::String\&, const System::String\&) | Ställer in ett anpassat värde för artefakten. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
