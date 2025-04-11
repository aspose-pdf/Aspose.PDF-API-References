---
title: Class ButtonField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ButtonField klass. Klassen representerar tryckknappfält
type: docs
weight: 4970
url: /sv/net/aspose.pdf.forms/buttonfield/
---
## ButtonField klass

Klassen representerar tryckknappfält.

```csharp
public class ButtonField : Field
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ButtonField](buttonfield/#constructor)() | Konstruktör för knappfält för Generator. |
| [ButtonField](buttonfield/#constructor_1)(Document, Rectangle) | Konstruktör för ButtonField. |
| [ButtonField](buttonfield/#constructor_2)(Page, Rectangle) | Konstruktör för ButtonField. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Hämtar annoteringens åtgärder. (2 egenskaper) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in aktuell annoteringsutseende tillstånd. |
| [AlternateCaption](../../aspose.pdf.forms/buttonfield/alternatecaption/) { get; set; } | Hämtar eller ställer in alternativ rubrik för knappen som ska visas när musknappen trycks inom dess aktiva område. |
| [AlternateIcon](../../aspose.pdf.forms/buttonfield/alternateicon/) { get; set; } | Hämtar eller ställer in alternativ ikon som ska visas när musknappen trycks inom dess aktiva område. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Hämtar eller ställer in alternativ namn för fältet (Ett alternativt fältnamn som ska användas istället för det faktiska fältnamnet där fältet ska identifieras i användargränssnittet). Alternativt namn används som fältverktygstips i Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Hämtar eller ställer in index för denna annotering på sidan. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Hämtar typ av annotering. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendediktionären för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in annoteringsgränskarakteristika. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringskarakteristika. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Hämtar antalet underfält i detta fält. (Till exempel antalet objekt i radioknappfältet). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Hämtar eller ställer in standardutseendet för fältet. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Hämtar eller ställer in exportabel flagga för fältet. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet för annoteringen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annoteringens markeringsläge. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmenthyperlänken (för pdf-generator). |
| [IconFit](../../aspose.pdf.forms/buttonfield/iconfit/) { get; } | Hämtar ikonutrymmesobjekt som specificerar hur widgetannoteringens ikon ska visas inom dess annoteringsrektangel. |
| [ICPosition](../../aspose.pdf.forms/buttonfield/icposition/) { get; set; } | Hämtar eller ställer in ikonens rubrikposition. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Hämtar eller ställer in ett bool-värde som indikerar om detta fält är ett icke-terminalt fält, dvs. en grupp av fält. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Egenskap för Generatorstöd. Används när fältet läggs till i sidhuvud eller sidfot. Om sant, kommer detta fält att skapas en gång och dess utseende kommer att vara synligt på alla sidor i dokumentet. Om falskt, kommer ett separat fält att skapas för varje dokument sida. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Returnerar sant om ordboken är synkroniserad. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Hämtar underfält som ingår i detta fält efter namnet på underfältet. (2 indexerare) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Hämtar eller ställer in mappningsnamnet för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när annoteringen senast ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in annoteringens namn på sidan. |
| [NormalCaption](../../aspose.pdf.forms/buttonfield/normalcaption/) { get; set; } | Hämtar eller ställer in normal rubrik. |
| [NormalIcon](../../aspose.pdf.forms/buttonfield/normalicon/) { get; set; } | Hämtar eller ställer in normal ikon för knappen som ska visas när den inte interagerar med användaren. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | En åtgärd som ska utföras när annoteringen aktiveras. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Hämtar index för sidan som innehåller detta fält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Hämtar annoteringens förälder. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Hämtar eller ställer in delnamnet för fältet. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Hämtar eller ställer in skrivskyddat status för fältet. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Hämtar eller ställer in fältets rektangel. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Hämtar eller ställer in obligatorisk status för fältet. |
| [RolloverCaption](../../aspose.pdf.forms/buttonfield/rollovercaption/) { get; set; } | Hämtar eller ställer in rullande rubrik för knappen som ska visas när användaren rullar muspekaren in i dess aktiva område utan att trycka på musknappen. |
| [RolloverIcon](../../aspose.pdf.forms/buttonfield/rollovericon/) { get; set; } | Hämtar eller ställer in rullande ikon för knappen som ska visas när användaren rullar muspekaren in i dess aktiva område utan att trycka på musknappen. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendediktionären för annoteringen. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchroniseringsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Hämtar eller ställer in tabbordningen för fältet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjustering för annoteringen. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | Hämtar eller ställer in värdet för fältet. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepterar besökare. |
| [AddImage](../../aspose.pdf.forms/buttonfield/addimage/)(Image) | Lägger till bild i fältresurserna och ritar den. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återger alltid null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopierar underfält av detta fält till en array som börjar från angiven index. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Utför en angiven JavaScript-åtgärd för fältet. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna strömmen. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna filen. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporterar innehållet i det angivna fältet till en JSON-ström. Värden för knappfält exporteras inte. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returnerar namnet på "kontrollerad" status enligt befintliga statusnamn. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Returnerar uppräkning av innehållna fält. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importerar data till de angivna fälten från en JSON-ström, baserat på en exakt matchning av fältens fullständiga namn. |
| [ImportValueFromJson](../../aspose.pdf/forms/field/importvaluefromjson/)(Stream, string) | Importerar data till det angivna fältet från en JSON-ström, med hjälp av det fullständiga namnet som anges i variabeln 'fieldFullNameInJSON' för matchning. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Beräknar om alla beräknade fält i formuläret. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Ställer in positionen för fältet. |

### Se Även

* klass [Field](../field/)
* namnrymd [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* samling [Aspose.PDF](../../)