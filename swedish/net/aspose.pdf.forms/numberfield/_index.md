---
title: Class NumberField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.NumberField klass. Textfält med specificerade giltiga tecken
type: docs
weight: 5140
url: /sv/net/aspose.pdf.forms/numberfield/
---
## NumberField klass

Textfält med specificerade giltiga tecken

```csharp
public class NumberField : TextBoxField
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [NumberField](numberfield/#constructor)() | Initierar en ny instans av `NumberField` klassen. |
| [NumberField](numberfield/#constructor_1)(Document, Rectangle) | Initierar en ny instans av `NumberField` klassen. |
| [NumberField](numberfield/#constructor_2)(Page, Rectangle) | Initierar en ny instans av `NumberField` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Hämtar annoteringens åtgärder. (2 egenskaper) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in den aktuella annoteringens utseende tillstånd. |
| [AllowedChars](../../aspose.pdf.forms/numberfield/allowedchars/) { get; set; } | Hämtar eller ställer in de tillåtna tecknen. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Hämtar eller ställer in det alternativa namnet på fältet (Ett alternativt fältnamn som ska användas istället för det faktiska fältnamnet där fältet ska identifieras i användargränssnittet). Det alternativa namnet används som fältverktygstips i Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Hämtar eller ställer in index för denna annotering på sidan. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Hämtar typen av annotering. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendets ordbok för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in annoteringens kantkarakteristika. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringens egenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in annoteringens färg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in annoteringens text. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Hämtar antalet underfält i detta fält. (Till exempel antalet objekt i radioknappfältet). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Hämtar eller ställer in standardutseendet för fältet. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Hämtar eller ställer in exportflaggan för fältet. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggar för annoteringen. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | Hämtar eller ställer in flaggan som indikerar om fältet är uppdelat i avståndspositioner. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet på annoteringen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annoteringens markeringsläge. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Hämtar eller ställer in ett bool-värde som indikerar om detta fält är ett icke-terminalt fält, dvs. en grupp av fält. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Egenskap för Generatorstöd. Används när fältet läggs till i sidhuvud eller sidfot. Om sant, kommer detta fält att skapas en gång och dess utseende kommer att synas på alla sidor i dokumentet. Om falskt, kommer ett separat fält att skapas för varje dokument sida. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Returnerar sant om ordboken är synkroniserad. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Hämtar underfältet som ingår i detta fält med namnet på underfältet. (2 indexerare) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Hämtar eller ställer in mappningsnamnet för fältet som ska användas vid export av interaktiva fältdata från dokumentet. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | Hämtar eller ställer in den maximala längden på texten i fältet. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när annoteringen senast ändrades. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | Hämtar eller ställer in flervalsflaggan för fältet. Om Multiline är sant kan fältet innehålla flera rader text. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in annoteringens namn på sidan. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | En åtgärd som ska utföras när annoteringen aktiveras. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Hämtar index för sidan som innehåller detta fält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Hämtar annoteringens förälder. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Hämtar eller ställer in det partiella namnet för fältet. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Hämtar eller ställer in statusen för skrivskyddat fält. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Hämtar eller ställer in fältets rektangel. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Hämtar eller ställer in den obligatoriska statusen för fältet. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | Hämtar eller ställer in den rullbara flaggan för fältet. Om sant kan fältet rullas. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | Hämtar eller ställer in stavningskontrollflaggan för fältet. Om sant ska fältet kontrolleras för stavfel. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendets ordbok för annoteringen. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synkroniseringsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Hämtar eller ställer in tabbordningen för fältet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjusteringen för annoteringen. |
| [TextVerticalAlignment](../../aspose.pdf/forms/textboxfield/textverticalalignment/) { get; set; } | Hämtar eller ställer in textens vertikala justering för annoteringen. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | Hämtar eller ställer in värdet för fältet. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepterar besökare. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | Lägger till streckkod 128 i fältet. Fältvärdet kommer att ändras till koden och fältet blir skrivskyddat. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(Image) | Lägger till bild i fältresurserna och ritar den. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matrisens transformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återvänder alltid null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopierar underfält av detta fält till en array som börjar från angivet index. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Utför en angiven JavaScript-åtgärd för fältet. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna strömmen. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna filen. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporterar innehållet i det angivna fältet till en JSON-ström. Knappfältvärden exporteras inte. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returnerar namnet på "markerad" status enligt befintliga statusnamn. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Returnerar en uppräkning av de innehållna fälten. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importerar data till de angivna fälten från en JSON-ström, baserat på en exakt matchning av fältens fullständiga namn. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importerar data till det angivna fältet från en JSON-ström, med hjälp av det fullständiga namnet som anges i variabeln 'fieldFullNameInJSON' för matchning. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Beräknar om alla beräknade fält i formuläret. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Ställer in positionen för fältet. |

### Se Även

* klass [TextBoxField](../textboxfield/)
* namnrum [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* samling [Aspose.PDF](../../)