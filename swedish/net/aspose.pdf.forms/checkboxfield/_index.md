---
title: Class CheckboxField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.CheckboxField klass. Klass som representerar checkbox-fält
type: docs
weight: 4980
url: /sv/net/aspose.pdf.forms/checkboxfield/
---
## CheckboxField klass

Klass som representerar checkbox-fält

```csharp
public class CheckboxField : Field
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CheckboxField](checkboxfield/#constructor_1)(Document) | Konstruktör att använda med Generator. |
| [CheckboxField](checkboxfield/#constructor_2)(Document, Rectangle) | Konstruktör för CheckboxField klass. |
| [CheckboxField](checkboxfield/#constructor_3)(Page, Rectangle) | Konstruktör för CheckboxField klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Hämtar annoteringsåtgärder. (2 egenskaper) |
| override [ActiveState](../../aspose.pdf.forms/checkboxfield/activestate/) { get; set; } | Hämtar eller sätter aktuell annoteringsutseende tillstånd. |
| [AllowedStates](../../aspose.pdf.forms/checkboxfield/allowedstates/) { get; } | Returnerar lista över tillåtna tillstånd. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Hämtar eller sätter alternativt namn för fältet (Ett alternativt fältnamn som ska användas istället för det faktiska fältnamnet där fältet ska identifieras i användargränssnittet). Alternativt namn används som fältverktygstips i Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Hämtar eller sätter index för denna annotation på sidan. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendediktionären för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller sätter annoteringsgränskarakteristika. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringskarakteristika. |
| [Checked](../../aspose.pdf.forms/checkboxfield/checked/) { get; set; } | Hämtar eller sätter tillståndet för kryssrutan. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller sätter annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller sätter annoteringstext. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Hämtar antalet underfält i detta fält. (Till exempel antal objekt i radioknappfält). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Hämtar eller sätter standardutseendet för fältet. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Hämtar eller sätter exportabel flagga för fältet. |
| [ExportValue](../../aspose.pdf.forms/checkboxfield/exportvalue/) { get; set; } | Hämtar eller sätter exportvärde för CheckBox-fältet. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar fullständigt kvalificerat namn för annoteringen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller sätter höjd för annoteringen. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annoteringens markeringsläge. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller sätter fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Hämtar eller sätter bool-värde som indikerar om detta fält är ett icke-terminalt fält, dvs. en grupp av fält. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller sätter ett stycke som är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller sätter ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Egenskap för Generatorstöd. Används när fältet läggs till i sidhuvud eller sidfot. Om sant, kommer detta fält att skapas en gång och dess utseende kommer att vara synligt på alla sidor i dokumentet. Om falskt, kommer ett separat fält att skapas för varje dokument sida. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Returnerar sant om ordboken är synkroniserad. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Hämtar underfält som ingår i detta fält med namnet på underfältet. (2 indexerare) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Hämtar eller sätter mappningsnamn för fältet som ska användas vid export av interaktiva fältdata från dokumentet. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller sätter en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller sätter datum och tid när annoteringen senast ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller sätter annoteringsnamn på sidan. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | En åtgärd som ska utföras när annoteringen aktiveras. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Hämtar index för sidan som innehåller detta fält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Hämtar annoteringsförälder. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Hämtar eller sätter delvis namn för fältet. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Hämtar eller sätter skrivskyddat status för fältet. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Hämtar eller sätter fältets rektangel. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Hämtar eller sätter obligatorisk status för fältet. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendediktionären för annoteringen. |
| [Style](../../aspose.pdf.forms/checkboxfield/style/) { get; set; } | Hämtar eller sätter stil för kryssrutan. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchroniseringsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Hämtar eller sätter tabbordning för fältet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller sätter textjustering för annoteringen. |
| override [Value](../../aspose.pdf.forms/checkboxfield/value/) { get; set; } | Hämtar eller sätter värde för kryssrute-fältet. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller sätter en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller sätter bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller sätter ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepterar besökare. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption)(string) | Lägger till en ny kryssruta i en kryssrutegrupp, där högst en av kryssrutorna kan vara markerad vid varje tidpunkt. Den nya kryssrutan läggs till i botten av gruppen. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_1)(string, Rectangle) | Lägger till en ny kryssruta i en kryssrutegrupp, där högst en av kryssrutorna kan vara markerad vid varje tidpunkt. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_2)(string, int, Rectangle) | Lägger till en ny kryssruta i en kryssrutegrupp, där högst en av kryssrutorna kan vara markerad vid varje tidpunkt. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| override [Clone](../../aspose.pdf.forms/checkboxfield/clone/)() | Klonar kryssrutan. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopierar underfält av detta fält till en array som börjar från angivet index. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Utför en angiven JavaScript-åtgärd för fältet. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna strömmen. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna filen. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporterar innehållet i det angivna fältet till en JSON-ström. Värden för knappfält exporteras inte. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returnerar namnet på "markerad" tillstånd enligt befintliga tillståndsnamn. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Returnerar uppräkning av innehållna fält. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importerar data till de angivna fälten från en JSON-ström, baserat på en exakt matchning av fältens fullständiga namn. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importerar data till det angivna fältet från en JSON-ström, med hjälp av det fullständiga namnet som anges i variabeln 'fieldFullNameInJSON' för matchning. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Beräknar om alla beräknade fält på formuläret. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Sätter positionen för fältet. |

## Exempel

Exemplet visar hur man skapar ett flervärdigt kryssrute-fält.

```csharp
using (var document = new Document())
{
var page = document.Pages.Add();

var checkbox = new CheckboxField(page, new Rectangle(50, 50, 70, 70));

// Set the first checkbox group option value
checkbox.ExportValue = "option 1";

// Add new option right under existing ones
checkbox.AddOption("option 2");

// Add new option at the given rectangle
checkbox.AddOption("option 3", new Rectangle(100, 100, 120, 120));

document.Form.Add(checkbox);

// Select the added checkbox
checkbox.Value = "option 2";
document.Save("checkbox_group.pdf");
}
```

### Se Även

* klass [Field](../field/)
* namnrymd [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* sammansättning [Aspose.PDF](../../)