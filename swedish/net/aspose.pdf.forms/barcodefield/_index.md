---
title: BarcodeField
second_title: Aspose.PDF för .NET API Referens
description: Klass representerar streckkodsfält.
type: docs
weight: 2900
url: /sv/net/aspose.pdf.forms/barcodefield/
---
## BarcodeField class

Klass representerar streckkodsfält.

```csharp
public sealed class BarcodeField : TextBoxField
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BarcodeField](barcodefield#constructor)(Document, Rectangle) | Initierar ny instans av[`BarcodeField`](../barcodefield) class. |
| [BarcodeField](barcodefield#constructor_1)(Page, Rectangle) | Initierar ny instans av[`BarcodeField`](../barcodefield) class. |

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
| [Caption](../../aspose.pdf.forms/barcodefield/caption) { get; } | Hämtar bildtexten för streckkodsobjektet. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Får annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Hämtar eller ställer in antal underfält i detta fält. (Till exempel antal objekt i alternativknappsfältet). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Hämtar eller ställer in fältets standardutseende. |
| [ECC](../../aspose.pdf.forms/barcodefield/ecc) { get; } | Får ett heltalsvärde som representerar felkorrigeringskoefficienten. För PDF417 ska vara från 0 till 8. För QRCode ska vara från 0 till 3 (0 för �L�, 1 för �M�, 2 för �Q� och 3 för �H�)._x000 |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Hämtar eller ställer in exportbar flagga för fältet. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flaggor för annoteringen. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs) { get; set; } | Hämtar eller ställer in flagga som indikerar att ett fält är uppdelat i åtskilda positioner. |
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
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen) { get; set; } | Hämtar eller ställer in maximal textlängd i fältet. |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Hämtar eller ställer in datum och tid när anteckningen nyligen ändrades. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline) { get; set; } | Hämtar eller ställer in flerradsflagga för fältet. Om Multiline är sant kan fältet innehålla flera rader text. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Hämtar eller ställer in anteckningsnamn på sidan. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | En åtgärd som ska utföras när anteckningen aktiveras. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Hämtar index över sidan som innehåller detta fält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Får anteckningsförälder. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Hämtar eller ställer in partiellt namn på fältet. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Hämtar eller ställer in skrivskyddad status för fältet. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Hämtar eller ställer in fältrektangeln. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Hämtar eller ställer in obligatorisk status för fältet. |
| [Resolution](../../aspose.pdf.forms/barcodefield/resolution) { get; } | Hämtar upplösningen, i dots-per-inch (dpi), vid vilken streckkodsobjektet renderas. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable) { get; set; } | Hämtar eller ställer in rullningsbar flagga för fält. Om sant fält kan rullas. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck) { get; set; } | Hämtar eller ställer in stavningskontrollflagga för fält. Om sant fält ska stavningskontrolleras. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Hämtar utseendeordbok för anteckningar. |
| [Symbology](../../aspose.pdf.forms/barcodefield/symbology) { get; } | Anger vilken streckkods- eller glyphteknologi som ska användas i denna annotering, se[`Symbology`](./symbology) för detaljer. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Synkroniseringsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Hämtar eller ställer in tabbordning för fältet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Hämtar eller ställer in textjustering för anteckning. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment) { get; set; } | Hämtar eller ställer in text vertikal justering för anteckning. |
| override [Value](../../aspose.pdf.forms/textboxfield/value) { get; set; } | Hämtar eller ställer in fältets värde. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [XSymHeight](../../aspose.pdf.forms/barcodefield/xsymheight) { get; } | Hämtar det vertikala avståndet mellan två streckkodsmoduler, mätt i pixlar. Förhållandet XSymHeight/XSymWidth ska vara ett heltalsvärde. För PDF417 är det acceptabla förhållandet från 1 till 4. För QRCode och DataMatrix, ska detta förhållande alltid vara 1 |
| [XSymWidth](../../aspose.pdf.forms/barcodefield/xsymwidth) { get; } | Hämtar det horisontella avståndet, i pixlar, mellan två streckkodsmoduler. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Accepterar besökare. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode)(string) | Lägger till streckkod 128 i fältet. Fältvärdet kommer att ändras till koden och fältet blir skrivskyddat. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage)(Image) | Lägger till bild i fältresurserna och ritar den. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Uppdatera parametrar och utseende, enligt matristransformationen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klonar denna instans. Virtuell metod. Returnera alltid null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Kopierar underfält av detta fält till array med början från angivet index. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Returnerar enumerator av inneslutna fält. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returnerar rektangel av anteckning med hänsyn till sidrotation. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Rekakulerar alla beräknade fält i formuläret. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Ställ in fältets position. |

### Se även

* class [TextBoxField](../textboxfield)
* namnutrymme [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
