---
title: "Klass Field"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Forms.Field klass. Basisklass för acro-formulärfält"
type: docs
weight: 5170
url: /sv/net/aspose.pdf.forms/field/
---
## Field class

Basklass för acro-formulärfält.

```csharp
public class Field : WidgetAnnotation, ICollection<WidgetAnnotation>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Field](field/)(Document) | Skapar fält för användning i Generator. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Hämtar annoteringsåtgärderna. (2 egenskaper) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller anger aktuellt annoteringsutseende. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Hämtar eller anger alternativt namn för fältet (Ett alternativt fältnamn som ska användas i stället för det faktiska fältnamnet där fältet identifieras i användargränssnittet). Alternativt namn används som verktygstips för fältet i Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Hämtar eller anger index för denna annotation på sidan. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendedictionary för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller anger annoteringskantens egenskaper. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller anger annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller anger annoteringstext. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Hämtar antalet underfält i detta fält. (Till exempel antalet objekt i radioknappsfält). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Hämtar eller anger standardutseende för fältet. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Hämtar eller anger exportflagga för fältet. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar fullt kvalificerat namn för annoteringen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller anger höjd för annoteringen. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annoteringsmarkeringsläge. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller anger fragmentets hyperlänk (för PDF‑generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Hämtar eller anger ett booleskt värde som indikerar om detta fält är ett icke‑terminalt fält, dvs. en grupp av fält. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Egenskap för Generator-stöd. Används när fält läggs till i sidhuvud eller sidfot. Om true, kommer detta fält att skapas en gång och dess utseende kommer att vara synligt på alla dokumentets sidor. Om false, kommer separata fält att skapas för varje dokumentsida. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Returnerar true om ordboken är synkroniserad. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Hämtar delfält som finns i detta fält enligt namn på delfältet. (2 indexerare) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Hämtar eller anger mappningsnamnet för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller anger datum och tid då annotationen senast ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller anger annoteringsnamn på sidan. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | En åtgärd som ska utföras när annotationen aktiveras. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Hämtar index för sidan som innehåller detta fält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Hämtar annotationens förälder. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Hämtar eller anger delnamn för fältet. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Hämtar eller anger skrivskyddsstatus för fältet. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Hämtar eller anger fältrektangeln. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Hämtar eller anger obligatorisk status för fältet. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendeordbok för annotationen. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synkroniseringsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Hämtar eller anger tabbordning för fältet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller anger textjustering för annotationen. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | Hämtar eller anger värde för fältet. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller anger bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |
| static [FitIntoRectangle](../../aspose.pdf.forms/field/fitintorectangle/) { get; set; } | Om true så minskas teckenstorleken för att passa texten i den angivna rektangeln. |
| static [MaxFontSize](../../aspose.pdf.forms/field/maxfontsize/) { get; set; } | Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storleken. |
| static [MinFontSize](../../aspose.pdf.forms/field/minfontsize/) { get; set; } | Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storleken. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepterar besökare. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Returnerar alltid null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/#copyto)(WidgetAnnotation[], int) | Kopierar underfält från detta fält till en array med start från angivet index. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Utför en specificerad JavaScript‑åtgärd för fältet. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporterar det angivna PDF‑formulärfältet till JSON‑format och skriver resultatet till den angivna strömmen. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporterar det angivna PDF‑formulärfältet till JSON‑format och skriver resultatet till den angivna filen. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporterar innehållet i det angivna fältet till en JSON‑ström. Värdet för knappfält exporteras inte. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returnerar namnet på "checked"‑tillståndet enligt befintliga tillståndsnamn. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Returnerar en enumerator för de innehållna fälten. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotationen. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/#importvaluefromjson)(Stream) | Importerar data till de angivna fälten från en JSON‑ström, baserat på en exakt matchning av fältens fullständiga namn. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/#importvaluefromjson_1)(Stream, string) | Importerar data till det angivna fältet från en JSON‑ström, med hjälp av det fullständiga namn som anges i variabeln 'fieldFullNameInJSON' för matchning. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Beräknar om alla beräknade fält i formuläret. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Ställ in fältets position. |

### Se även

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


