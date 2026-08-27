---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar ett segment av PDF-text. </p> <hr> <pre> Exemplet visar hur man ändrar textfärg och teckenstorlek för texten med {@code TextState} objekt av {@code TextSegment} objekt. // Öppna dokument Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Skapa TextFragmentAbsorber-objekt för att hitta alla \"hello world\"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra förgrundsfärg för det första textsegmentet i den första textförekomsten absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Ändra teckenstorlek för det första textsegmentet i den första textförekomsten absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Spara dokumentet doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <pre> Med några ord är {@code TextSegment} objekt barn till {@code TextFragment} objektet. I detalj: Text i en pdf-dokument i {@code Aspose.Pdf} representeras av två grundläggande objekt: {@code TextFragment} och {@code TextSegment}. Skillnaderna mellan dem är mest kontextberoende. Låt oss överväga följande scenario. Användaren söker texten \"hello world\" för att arbeta med den, ändra dess egenskaper, visa etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> <p> Den fysiska representationen av pdf-text är mycket komplex. Texten \"hello world\" kan bestå av flera fysiskt oberoende textsegment. Aspose.PDF-textmodellen fastställer i princip att {@code TextFragment} objektet tillhandahåller en enda logisk operation över en uppsättning fysiska {@code TextSegment} objekt som representerar användarens fråga. I ett textsökscenario är {@code TextFragment} den logiska \"hello world\"-textrepresentationen, och {@code TextSegment} objektkollektionen representerar alla fysiska segment som konstruerar \"hello world\"-textobjektet. Således är {@code TextFragment} nära den logiska textrepresentationen. Och {@code TextSegment} är nära den fysiska textrepresentationen. Uppenbarligen kan varje {@code TextSegment} objekt ha sin egen teckensnitt, färgning och placeringsegenskaper. {@code TextFragment} erbjuder ett enkelt sätt att ändra text med dess egenskaper: sätt teckensnitt, sätt teckenstorlek, sätt textfärg osv. Samtidigt är {@code TextSegment} objekt tillgängliga och användare kan arbeta med {@code TextSegment} objekt oberoende. </p>"
type: docs
weight: 5300
url: /sv/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Representerar segment av PDF-text. </p> <hr> <pre> Exemplet visar hur man ändrar textfärg och teckenstorlek på texten med {@code TextState}-objektet av {@code TextSegment}-objektet. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra förgrundsfärg för det första textsegmentet i den första textförekomsten absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Ändra teckenstorlek för det första textsegmentet i den första textförekomsten absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> Med några ord är {@code TextSegment}-objekt barn till {@code TextFragment}-objekt. I detalj: Text i pdf-dokument i {@code Aspose.Pdf} representeras av två grundläggande objekt: {@code TextFragment} och {@code TextSegment} Skillnaderna mellan dem är mest kontextberoende. Låt oss överväga följande scenario. Användaren söker texten "hello world" för att arbeta med den, ändra dess egenskaper, titta etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> Den fysiska representationen av PDF-text är mycket komplex. Texten "hello world" kan bestå av flera fysiskt oberoende textsegment. Aspose.PDF-textmodellen fastställer i princip att {@code TextFragment}-objektet tillhandahåller en enda logisk operation över en uppsättning fysiska {@code TextSegment}-objekt som representerar användarens fråga. I textsökningsscenario är {@code TextFragment} den logiska "hello world"-textrepresentationen, och {@code TextSegment}-objektkollektionen representerar alla fysiska segment som bygger upp "hello world"-textobjektet. Så är {@code TextFragment} nära den logiska textrepresentationen. Och {@code TextSegment} är nära den fysiska textrepresentationen. Uppenbarligen kan varje {@code TextSegment}-objekt ha sin egen teckensnitt, färgning och placeringsegenskaper. {@code TextFragment} erbjuder ett enkelt sätt att ändra text med dess egenskaper: sätt teckensnitt, sätt teckenstorlek, sätt teckensnittsfärg osv. Samtidigt är {@code TextSegment}-objekt tillgängliga och användare kan arbeta med {@code TextSegment}-objekt oberoende. </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> Skapar TextSegment-objekt. </p> <hr> <pre> Exemplet visar hur man skapar ett textfragment-objekt, lägger till ett textsegment i textfragmentets samling och lägger till det på Pdf-sidan. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // skapa textfragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // ställ in dess textegenskaper tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // lägg till ett segment till textfragmentets Segments-samling TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // skapa TextBuilder-objekt TextBuilder builder = new TextBuilder(page); // lägg till textfragmentet på Pdf-sidan builder.appendText(tf); // spara dokumentet doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> Skapar TextSegment-objekt. </p> <hr> <pre> Exemplet visar hur man skapar ett textfragment-objekt, lägger till ett textsegment i textfragmentets samling och lägger till det på Pdf-sidan. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // skapa textfragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // ställ in dess textegenskaper tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // lägg till ett segment till textfragmentets Segments-samling TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // skapa TextBuilder-objekt TextBuilder builder = new TextBuilder(page); // lägg till textfragmentet på Pdf-sidan builder.appendText(tf); // spara dokumentet doc.save(outFile); </pre> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Hämtar textposition för text, representerad med {@code TextSegment}-objekt. YIndent i Position-strukturen representerar baslinjekoordinationen för textsegmentet. |
| [getCharacters](#getCharacters--) | Hämtar samling av CharInfo-objekt som representerar information om tecken i textsegmentet. |
| [getEndCharIndex](#getEndCharIndex--) | Hämtar slutteckensindex för aktuellt segment i show‑text‑operatorn (Tj, TJ)-segmentet. |
| [getHyperlink](#getHyperlink--) | Hämtar eller anger segmentets hyperlänk (för pdf‑generator). |
| [getPosition](#getPosition--) | Hämtar textposition för text, representerad med {@code TextSegment}-objekt. |
| [getRectangle](#getRectangle--) | Hämtar rektangeln för TextSegmentet |
| [getStartCharIndex](#getStartCharIndex--) | Hämtar startteckensindex för aktuellt segment i show‑text‑operatorn (Tj, TJ)-segmentet. |
| [getText](#getText--) | Hämtar {@code string}-textobjektet som {@code TextSegment}-objektet representerar. |
| [getTextEditOptions](#getTextEditOptions--) | Hämtar alternativ för textredigering. Alternativen definierar speciellt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| [getTextState](#getTextState--) | <p> Hämtar eller anger texttillstånd för den text som {@code TextSegment}-objektet representerar. </p> <hr> <p> Tillhandahåller ett sätt att ändra följande egenskaper för texten: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Anger textposition för text, representerad med {@code TextSegment}-objekt. YIndent i Position‑strukturen representerar baslinjekoordinationen för textsegmentet. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Hämtar eller anger segmentets hyperlänk (för pdf‑generator). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Anger textposition för text, representerad med {@code TextSegment}-objekt. |
| [setText](#setText-java.lang.String-) | Anger {@code string}-textobjektet som {@code TextSegment}-objektet representerar. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Ställer in alternativ för textredigering. Alternativen definierar speciellt beteende när den begärda symbolen inte kan skrivas med teckensnittet. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> Anger texttillstånd för den text som {@code TextSegment}-objektet representerar. </p> <hr> <p> Tillhandahåller ett sätt att ändra följande egenskaper för texten: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | Anger {@code string}-textobjektet som {@code TextSegment}-objektet representerar med undertryckt uppdatering. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> Skapar TextSegment-objekt. </p> <hr> <pre> Exemplet visar hur man skapar ett textfragment-objekt, lägger till ett textsegment i textfragmentets samling och lägger till det på Pdf-sidan. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // skapa textfragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // ställ in dess textegenskaper tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // lägg till ett segment till textfragmentets Segments-samling TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // skapa TextBuilder-objekt TextBuilder builder = new TextBuilder(page); // lägg till textfragmentet på Pdf-sidan builder.appendText(tf); // spara dokumentet doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> Skapar TextSegment-objekt. </p> <hr> <pre> Exemplet visar hur man skapar ett textfragment-objekt, lägger till ett textsegment i textfragmentets samling och lägger till det på Pdf-sidan. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // skapa textfragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // ställ in dess textegenskaper tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // lägg till ett segment till textfragmentets Segments-samling TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // skapa TextBuilder-objekt TextBuilder builder = new TextBuilder(page); // lägg till textfragmentet på Pdf-sidan builder.appendText(tf); // spara dokumentet doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Hämtar textposition för text, representerad med {@code TextSegment}-objekt. YIndent i Position-strukturen representerar baslinjekoordinationen för textsegmentet.

**Returns:**
Positionsvärde

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Hämtar samling av CharInfo-objekt som representerar information om tecken i textsegmentet.

**Returns:**
CharInfoCollection-objekt

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Hämtar slutteckensindex för aktuellt segment i show‑text‑operatorn (Tj, TJ)-segmentet.

**Returns:**
int‑värde

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Hämtar eller anger segmentets hyperlänk (för pdf‑generator).

**Returns:**
Hyperlink-objekt

### getPosition {#getPosition--}
```
public Position getPosition()
```

Hämtar textposition för text, representerad med {@code TextSegment}-objekt.

**Returns:**
Positionsvärde

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangeln för TextSegmentet

**Returns:**
Rectangle‑objekt

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Hämtar startteckensindex för aktuellt segment i show‑text‑operatorn (Tj, TJ)-segmentet.

**Returns:**
int‑värde

### getText {#getText--}
```
public String getText()
```

Hämtar {@code string}-textobjektet som {@code TextSegment}-objektet representerar.

**Returns:**
String värde

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Hämtar alternativ för textredigering. Alternativen definierar speciellt beteende när begärt tecken inte kan skrivas med teckensnittet.

**Returns:**
TextEditOptions‑värde

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> Hämtar eller anger texttillstånd för den text som {@code TextSegment}-objektet representerar. </p> <hr> <p> Tillhandahåller ett sätt att ändra följande egenskaper för texten: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
TextState värde

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Anger textposition för text, representerad med {@code TextSegment}-objekt. YIndent i Position‑strukturen representerar baslinjekoordinationen för textsegmentet.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Hämtar eller anger segmentets hyperlänk (för pdf‑generator).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Anger textposition för text, representerad med {@code TextSegment}-objekt.

### setText {#setText-java.lang.String-}
Anger {@code string}-textobjektet som {@code TextSegment}-objektet representerar.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Ställer in alternativ för textredigering. Alternativen definierar speciellt beteende när den begärda symbolen inte kan skrivas med teckensnittet.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> Anger texttillstånd för den text som {@code TextSegment}-objektet representerar. </p> <hr> <p> Tillhandahåller ett sätt att ändra följande egenskaper för texten: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
Anger {@code string}-textobjektet som {@code TextSegment}-objektet representerar med undertryckt uppdatering.
