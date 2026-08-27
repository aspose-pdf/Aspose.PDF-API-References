---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar ett fragment av Pdf‑text. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF‑dokumentets sida och ersätter texten och dess teckensnitt. // Open document."
type: docs
weight: 5110
url: /sv/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> Representerar ett fragment av PDF-text. </p> <hr> <pre> Exemplet demonstrerar hur man hittar text på den första PDF-dokumentets sida och ersätter texten och dess teckensnitt. // Open document Document doc = new Document(\"input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"output.pdf\"); </pre> <hr> <pre> Med några ord innehåller {@code TextFragment}-objektet en lista med {@code TextSegment}-objekt. I detalj: Texten i en pdf-dokument i {@code com.aspose.pdf} representeras av två grundläggande objekt: {@code TextFragment} och {@code TextSegment} Skillnaderna mellan dem är mest kontextberoende. Låt oss överväga följande scenario. Användaren söker texten \"hello world\" för att arbeta med den, ändra dess egenskaper, titta etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> Den fysiska representationen av pdf-text är mycket komplex. Texten \"hello world\" kan bestå av flera fysiskt oberoende textsegment. Aspose.Pdf-textmodellen fastställer i princip att {@code TextFragment}-objektet tillhandahåller en enda logisk operationsuppsättning över fysiska {@code TextSegment}-objekt som representerar användarens fråga. I textsökningsscenario är {@code TextFragment} en logisk representation av texten \"hello world\", och {@code TextSegment}-objektkollektionen representerar alla fysiska segment som bygger upp \"hello world\"-textobjektet. Alltså är {@code TextFragment} nära den logiska textrepresentationen. Och {@code TextSegment} är nära den fysiska textrepresentationen. Uppenbarligen kan varje {@code TextSegment}-objekt ha sin egen teckensnitt, färgning och placeringsegenskaper. {@code TextFragment} erbjuder ett enkelt sätt att ändra text med dess egenskaper: sätt teckensnitt, sätt teckenstorlek, sätt teckenfärg etc. Samtidigt är {@code TextSegment}-objekt tillgängliga och användare kan arbeta med {@code TextSegment}-objekt oberoende. <p> Notera att ändring av TextFragment-egenskaper kan ändra den inre {@code Segments}-samlingen eftersom TextFragment är ett aggregatobjekt och kan omarrangera interna segment eller slå ihop dem till ett enda segment. Om ditt krav är att lämna {@code Segments}-samlingen oförändrad, vänligen ändra interna segment individuellt. </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextFragment](#TextFragment--) | Initierar en ny instans av {@code TextFragment}-objektet. |
| [TextFragment](#TextFragment-java.lang.String-) | Initierar en ny instans av {@code TextFragment}-objektet. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Initierar en ny instans av {@code TextFragment}-objektet. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Initierar en ny instans av {@code TextFragment}-objektet. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Klona fragmentet med alla segment. |
| [deepClone](#deepClone--) | Klona fragmentet. |
| [getBaselinePosition](#getBaselinePosition--) | Hämtar textposition för text, representerad med {@code TextFragment}-objektet. YIndent i Position‑strukturen representerar baslinjekoordinationen för textfragmentet. |
| [getEndNote](#getEndNote--) | Hämtar paragrafens slutnot (end note) (endast för PDF‑generering). |
| [getFootNote](#getFootNote--) | Hämtar paragrafens fotnot (foot note) (endast för PDF‑generering). |
| [getForm](#getForm--) | Hämtar formulärobjektet som innehåller TextFragment. Värdet kan vara null om TextFragment‑objektet inte tillhör ett formulär. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Hämtar en horisontell justering av textfragmentet. |
| [getPage](#getPage--) | Hämtar sidan som innehåller TextFragment. Värdet kan vara null om TextFragment‑objektet inte tillhör någon sida. |
| [getPosition](#getPosition--) | <p> Hämtar textposition för text, representerad med {@code TextFragment}-objektet. </p> |
| [getRectangle](#getRectangle--) | Hämtar rektangeln för TextFragment. |
| [getReplaceOptions](#getReplaceOptions--) | Hämtar alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts med kortare eller längre text. |
| [getSegments](#getSegments--) | <p> Hämtar textsegment för aktuell {@code TextFragment}. </p> |
| [getText](#getText--) | <p> Hämtar {@code string} textobjekt som det {@code TextFragment} objektet representerar. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Hämtar eller anger alternativ för textredigering. Alternativen definierar särskilt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| [getTextState](#getTextState--) | <p> Hämtar eller anger texttillstånd för den text som {@code TextFragment} objektet representerar. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar en vertikal justering av textfragmentet. |
| [getWrapLinesCount](#getWrapLinesCount--) | Hämtar antal radbrytningar för detta stycke (endast för PDF-generering). |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Hämtar {@code TextSegment}(er) som representerar angiven del av {@code TextFragment} texten. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Anger textposition för text som representeras med {@code TextFragment} objektet. YIndent i Position‑strukturen representerar baslinjekoordinaten för textfragmentet. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Anger styckets slutnotering (endast för PDF-generering). |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Anger styckets fotnot (endast för PDF-generering). |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Anger en horisontell justering av textfragmentet. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Anger fragmentets hyperlänk |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Anger textposition för text som representeras med {@code TextFragment} objektet. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Hämtar rektangeln för TextFragment. |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Representerar setSegments‑metoden |
| [setText](#setText-java.lang.String-) | <p> Anger {@code string} textobjekt som {@code TextFragment} objektet representerar. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Hämtar eller anger alternativ för textredigering. Alternativen definierar särskilt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Anger en vertikal justering av textfragmentet. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Anger antal radbrytningar för detta stycke (endast för PDF-generering). |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Initierar en ny instans av {@code TextFragment}-objektet.

### TextFragment {#TextFragment-java.lang.String-}
Initierar en ny instans av {@code TextFragment}-objektet.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Initierar en ny instans av {@code TextFragment}-objektet.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Initierar en ny instans av {@code TextFragment}-objektet.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Klona fragmentet med alla segment.

**Returns:**
Det klonade objektet

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klona fragmentet.

**Returns:**
Det klonade objektet

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Hämtar textposition för text, representerad med {@code TextFragment}-objektet. YIndent i Position‑strukturen representerar baslinjekoordinationen för textfragmentet.

**Returns:**
Positionsvärde

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Hämtar paragrafens slutnot (end note) (endast för PDF‑generering).

**Returns:**
Noteringsvärde

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Hämtar paragrafens fotnot (foot note) (endast för PDF‑generering).

**Returns:**
Noteringsvärde

### getForm {#getForm--}
```
public XForm getForm()
```

Hämtar formulärobjektet som innehåller TextFragment. Värdet kan vara null om TextFragment‑objektet inte tillhör ett formulär.

**Returns:**
XForm‑värde

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Hämtar en horisontell justering av textfragmentet.

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

Hämtar sidan som innehåller TextFragment. Värdet kan vara null om TextFragment‑objektet inte tillhör någon sida.

**Returns:**
Page‑objekt

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Hämtar textposition för text, representerad med {@code TextFragment}-objektet. </p>

**Returns:**
Positionsvärde <hr> <pre> Exemplet demonstrerar hur man visar placeringen av en text som representeras av {@code TextFragment} objektet. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangeln för TextFragment.

**Returns:**
Rectangle‑objekt

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Hämtar alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts med kortare eller längre text.

**Returns:**
TextReplaceOptions‑instans

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Hämtar textsegment för aktuell {@code TextFragment}. </p>

**Returns:**
TextSegmentCollection värde <hr> <pre> Exemplet visar hur man navigerar alla {@code TextSegment} objekt inom {@code TextFragment}. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world" textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Navigera alla textsegment och skriv ut deras text och placeringsinformation for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> Med några ord, {@code TextSegment} objekt är barn till {@code TextFragment} objektet. Avancerade användare kan komma åt segmenten direkt för att utföra mer komplexa textredigeringsscenarier. För mer information, se beskrivningen av {@code TextFragment} objektet. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> Hämtar {@code string} textobjekt som det {@code TextFragment} objektet representerar. </p>

**Returns:**
String värde <hr> <pre> Exemplet visar hur man söker efter text och ersätter den första förekomsten som representeras av {@code TextFragment} objektet. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world" textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra teckensnitt för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Hämtar eller anger alternativ för textredigering. Alternativen definierar särskilt beteende när begärt tecken inte kan skrivas med teckensnittet.

**Returns:**
TextEditOptions-instans

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> Hämtar eller anger texttillstånd för den text som {@code TextFragment} objektet representerar. </p>

**Returns:**
TextFragmentState-objekt <hr> <pre> Exemplet visar hur man ändrar textfärg och teckenstorlek på texten med {@code TextState} objektet. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world" textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra förgrundsfärg för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Ändra teckenstorlek för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Tillhandahåller ett sätt att ändra följande egenskaper för texten: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Hämtar en vertikal justering av textfragmentet.

**Returns:**
int värde @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Hämtar antal radbrytningar för detta stycke (endast för PDF-generering).

**Returns:**
int‑värde

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Hämtar {@code TextSegment}(er) som representerar angiven del av {@code TextFragment} texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex |  | Position i texten från vilken nya {@code TextSegment}(s) kommer att starta. |
| längd |  | Längd på den text som kommer att isoleras till {@code TextSegment}(s). |

**Returns:**
{@code TextSegmentCollection} som innehåller textsegment som representerar en texts substräng som startar vid en specificerad position och har en angiven längd.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Anger textposition för text som representeras med {@code TextFragment} objektet. YIndent i Position‑strukturen representerar baslinjekoordinaten för textfragmentet.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Anger styckets slutnotering (endast för PDF-generering).

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Anger styckets fotnot (endast för PDF-generering).

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Anger en horisontell justering av textfragmentet.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Anger fragmentets hyperlänk

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Anger textposition för text som representeras med {@code TextFragment} objektet. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Hämtar rektangeln för TextFragment.

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
Representerar setSegments‑metoden

### setText {#setText-java.lang.String-}
<p> Anger {@code string} textobjekt som {@code TextFragment} objektet representerar. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Hämtar eller anger alternativ för textredigering. Alternativen definierar särskilt beteende när begärt tecken inte kan skrivas med teckensnittet.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Anger en vertikal justering av textfragmentet.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Anger antal radbrytningar för detta stycke (endast för PDF-generering).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
