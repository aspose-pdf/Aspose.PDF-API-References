---
title: RadioButtonField
second_title: Aspose.PDF för .NET API Referens
description: Klass som representerar alternativknappsfält.
type: docs
weight: 3160
url: /sv/net/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class

Klass som representerar alternativknappsfält.

```csharp
public sealed class RadioButtonField : ChoiceField
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RadioButtonField](radiobuttonfield#constructor)(Document) | Konstruktör för RadioButtonField. |
| [RadioButtonField](radiobuttonfield#constructor_1)(Page) | Konstruktör för RadiouttonField |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Hämtar anteckningsåtgärderna. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Hämtar eller ställer in aktuellt annoteringsutseendeläge. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Hämtar eller ställer in alternativt namn på fältet (Ett alternativt fält namn som ska användas i stället för det faktiska fältnamnet varhelst fältet ska identifieras i användargränssnittet). Alternativt namn används som fältverktygstips i Adobe Acrobat . |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Hämtar eller ställer in index för denna anteckning på sidan. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Får typ av anteckning. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Hämtar utseendeordbok för anteckningen. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Hämtar eller ställer in annoteringsgränsegenskaper.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Får annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately) { get; set; } | Får eller ställer in commit vid valändringsflagga. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Hämtar eller ställer in antal underfält i detta fält. (Till exempel antal objekt i alternativknappsfältet). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Hämtar eller ställer in fältets standardutseende. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Hämtar eller ställer in exportbar flagga för fältet. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Får det fullständiga kvalificerade namnet på anteckningen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Annotationsmarkeringsläge. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om detta stycke kommer att finnas i nästa kolumn. Standard är falskt.(för pdf-generering) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Hämtar eller ställer in booleskt värde som indikerar är detta fält icke-terminalt fält, dvs grupp av fält. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Hämtar eller ställer in ett stycke inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Hämtar eller ställer in ett boolvärde som tvingar fram detta stycke vid ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om det aktuella stycket finns kvar på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Egenskap för generatorstöd. Används när fält läggs till i sidhuvud eller sidfot. Om det är sant skapas det här fältet en gång och dess utseende kommer att synas på alla sidor i dokumentet. Om det är falskt skapas ett separat fält för varje dokumentsida. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Returnerar sant om ordlistan är synkroniserad. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Hämtar underfält i detta fält med namnet på underfältet. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Hämtar eller ställer in mappningsnamn för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Hämtar eller ställer in en yttre marginal för stycke (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Hämtar eller ställer in datum och tid när anteckningen nyligen ändrades. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect) { get; set; } | Hämtar eller ställer in flervalsflagga. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Hämtar eller ställer in anteckningsnamn på sidan. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | En åtgärd som ska utföras när anteckningen aktiveras. |
| override [Options](../../aspose.pdf.forms/radiobuttonfield/options) { get; } | Får en samling alternativ för alternativknappen. |
| override [PageIndex](../../aspose.pdf.forms/radiobuttonfield/pageindex) { get; } | Hämtar index över sidan som innehåller detta RadioButton-fält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Får anteckningsförälder. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Hämtar eller ställer in partiellt namn på fältet. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Hämtar eller ställer in skrivskyddad status för fältet. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Hämtar eller ställer in fältrektangeln. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Hämtar eller ställer in obligatorisk status för fältet. |
| override [Selected](../../aspose.pdf.forms/radiobuttonfield/selected) { get; set; } | Hämtar eller ställer in index för valt objekt. Numrering av objekt börjar från 1. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems) { get; set; } | Hämtar eller ställer in array av valda objekt. För multiselect innehåller listarrayen mer än ett objekt. För en enda urvalslista innehåller den enstaka objekt. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Hämtar utseendeordbok för anteckningar. |
| [Style](../../aspose.pdf.forms/radiobuttonfield/style) { get; set; } | Typ av fältlåda. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Synkroniseringsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Hämtar eller ställer in tabbordning för fältet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Hämtar eller ställer in textjustering för anteckning. |
| override [Value](../../aspose.pdf.forms/radiobuttonfield/value) { get; set; } | Hämtar eller ställer in fältets värde. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Accepterar besökare. |
| [Add](../../aspose.pdf.forms/radiobuttonfield/add)(RadioButtonOptionField) | Lägger till nytt alternativfält till RadioButton field |
| override [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption#addoption)(string) | Lägg till alternativ till radioknapp. |
| [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption#addoption_1)(string, Rectangle) | Lägg till alternativknapp med specificerad rektangel. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string, string) | Lägger till nytt alternativ med specificerat exportvärde och namn. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Uppdatera parametrar och utseende, enligt matristransformationen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klonar denna instans. Virtuell metod. Returnera alltid null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Kopierar underfält av detta fält till array med början från angivet index. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption)(string) | Tar bort alternativet efter dess namn. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Returnerar enumerator av inneslutna fält. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returnerar rektangel av anteckning med hänsyn till sidrotation. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Rekakulerar alla beräknade fält i formuläret. |
| override [SetPosition](../../aspose.pdf.forms/radiobuttonfield/setposition)(Point) | Flytta alla underposter i alternativknappen till angivna positioner på sidan. |

### Se även

* class [ChoiceField](../choicefield)
* namnutrymme [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
