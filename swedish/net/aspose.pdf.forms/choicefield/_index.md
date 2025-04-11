---
title: Class ChoiceField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ChoiceField klass. Representerar basklass för valfält
type: docs
weight: 4990
url: /sv/net/aspose.pdf.forms/choicefield/
---
## ChoiceField klass

Representerar basklass för valfält.

```csharp
public abstract class ChoiceField : Field
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ChoiceField](choicefield/#constructor)(Document) | Skapar valfält (för Generator) |
| [ChoiceField](choicefield/#constructor_1)(Document, Rectangle) | Konstruktör för ChoiceField. |
| [ChoiceField](choicefield/#constructor_2)(Page, Rectangle) | Konstruktör för ChoiceField. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Hämtar annoteringsåtgärder. (2 egenskaper) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in aktuell annoteringsutseende tillstånd. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Hämtar eller ställer in alternativt namn för fältet (Ett alternativt fältnamn som ska användas istället för det faktiska fältnamnet där fältet ska identifieras i användargränssnittet). Alternativt namn används som fältverktygstips i Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Hämtar eller ställer in index för denna annotation på sidan. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendediktionären för annotationen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in annoteringsgränskarakteristika. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringskarakteristika. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Hämtar eller ställer in flaggan för åtagande vid valändring. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Hämtar antalet underfält i detta fält. (Till exempel antalet objekt i radioknappfält). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Hämtar eller ställer in standardutseendet för fältet. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Hämtar eller ställer in exportabel flagga för fältet. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annotationen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet för annotationen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på annotationen. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annoteringens markeringsläge. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmenthyperlänken (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Hämtar eller ställer in ett bool-värde som indikerar om detta fält är ett icke-terminalt fält, dvs. en grupp av fält. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Egenskap för Generatorstöd. Används när fältet läggs till i sidhuvud eller sidfot. Om sant, kommer detta fält att skapas en gång och dess utseende kommer att synas på alla sidor i dokumentet. Om falskt, kommer ett separat fält att skapas för varje dokument sida. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Returnerar sant om ordboken är synkroniserad. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Hämtar underfält som ingår i detta fält med namnet på underfältet. (2 indexerare) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Hämtar eller ställer in mappningsnamnet för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när annotationen senast ändrades. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Hämtar eller ställer in flervalsflaggan. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in annoteringsnamnet på sidan. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | En åtgärd som ska utföras när annotationen aktiveras. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Hämtar samlingen av valalternativ. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Hämtar index för sidan som innehåller detta fält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Hämtar annoteringsförälder. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Hämtar eller ställer in delnamnet för fältet. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Hämtar eller ställer in status för skrivskyddat fält. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Hämtar eller ställer in fältets rektangel. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Hämtar eller ställer in status för obligatoriskt fält. |
| virtual [Selected](../../aspose.pdf.forms/choicefield/selected/) { get; set; } | Hämtar eller ställer in index för valt alternativ. Denna egenskap tillåter att ändra valet. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | Hämtar eller ställer in array av valda objekt. För flervalslista innehåller arrayen mer än ett objekt. För enkelval lista innehåller den ett enda objekt. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendediktionären för annotationen. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synkroniseringsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Hämtar eller ställer in tabbordningen för fältet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjustering för annotationen. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Hämtar eller ställer in värdet för fältet. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på annotationen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepterar besökare. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/#addoption)(string) | Lägger till nytt alternativ med angivet namn. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/#addoption_1)(string, string) | Lägger till nytt alternativ med angivet exportvärde och namn. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Returnerar alltid null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopierar underfält av detta fält till arrayen som börjar från angivet index. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Tar bort alternativet med dess namn. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Utför en angiven JavaScript-åtgärd för fältet. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna strömmen. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna filen. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporterar innehållet i det angivna fältet till en JSON-ström. Värdet för knappfält exporteras inte. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returnerar namnet på "kontrollerad" tillstånd enligt befintliga tillståndsnamn. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Returnerar enumerator för de innehållna fälten. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annotationen med hänsyn till sidrotation. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importerar data till de angivna fälten från en JSON-ström, baserat på en exakt matchning av fältens fullständiga namn. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importerar data till det angivna fältet från en JSON-ström, med hjälp av det fullständiga namnet som anges i variabeln 'fieldFullNameInJSON' för matchning. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Beräknar om alla beräknade fält i formuläret. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Ställer in positionen för fältet. |

### Se Även

* klass [Field](../field/)
* namnrymd [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)