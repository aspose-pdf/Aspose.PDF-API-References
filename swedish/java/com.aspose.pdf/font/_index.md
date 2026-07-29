---
title: "Font"
linktitle: "Font"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar font-objekt. </p> <hr> <pre> Exemplet visar hur man söker text på första sidan och ändrar font för den första sökträffen. // Open document Document doc."
type: docs
weight: 1650
url: /sv/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> Representerar teckensnitt-objekt. </p> <hr> <pre> Exemplet visar hur man söker text på första sidan och ändrar teckensnittet för den första sökträffen. // Öppna dokument Document doc = new Document("input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // Skapa teckensnitt och markera det för inbäddning Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Ändra teckensnittet för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Spara dokument doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Bestämmer om fonten innehåller angivna tecken |
| [getActualFontName](#getActualFontName--) | <p> Hämtar det faktiska teckensnittsnamnet för {@code Font} objektet om det är initierat. Även när teckensnittet har ersatts eller har internt namn för pdf. Eller tom sträng om teckensnittet inte är initierat. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Mäter den maximala Ascent-punkten. |
| [getBaseFont](#getBaseFont--) | Hämtar BaseFont‑värdet för PDF‑teckensnittobjektet. Även känt som PostScript‑namnet för teckensnittet. |
| [getDecodedFontName](#getDecodedFontName--) | Ibland kan PDF‑teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha ett specifikt teckensnittsnamn. Detta namn är värdet för PDF‑teckensnittsegenskapen \"BaseFont\" och ibland kan denna egenskap representeras i hexadecimal form. Om man läser detta namn direkt kan det visas i ett icke‑läsbart format. För att få ett läsbart format är det nödvändigt att avkoda teckensnittets namn enligt regler som är specifika för detta teckensnitt. Denna egenskap returnerar det avkodade teckensnittsnamnet, så använd den i fall där du stöter på ett icke‑läsbart {@code FontName}. Om egenskapen {@code FontName} har ett läsbart format kommer denna egenskap att vara densamma som {@code FontName}, så du kan använda den för alla fall där du behöver få teckensnittsnamnet i ett läsbart format. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Mäter den maximala Descent-punkten. |
| [getFontName](#getFontName--) | <p> Hämtar teckensnittsnamnet för {@code Font} objektet. </p> |
| [getFontOptions](#getFontOptions--) | Användbara egenskaper för att justera typsnittsbeteende |
| [getIFont](#getIFont--) | <p> Systemteckensnittobjekt. </p> <hr> <p> Endast för internt bruk </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Pdf‑teckensnittobjekt. </p> <hr> <p> Endast för internt bruk </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | Syftet med denna metod – att returnera felbeskrivning om ett försök att bädda in teckensnitt misslyckas. Om det inte finns några felreturneras en tom sträng. |
| [getType](#getType--) | Teckensnittets typnamn |
| [isAccessible](#isAccessible--) | <p> Hämtar indikation på om teckensnittet finns (är installerat) i systemet. </p> |
| [isEmbedded](#isEmbedded--) | <p> Hämtar ett värde som indikerar om teckensnittet är inbäddat. Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Hämtar ett värde som indikerar om teckensnittet är en delmängd. Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Mäter strängen. |
| [save](#save-java.io.OutputStream-) | Sparar teckensnittet i strömmen. Observera att teckensnittet sparas i ett mellansteg TTF-format som endast är avsett att användas i en konverterad kopia av det ursprungliga dokumentet. Teckensnittsfilen är inte avsedd att användas utanför det ursprungliga dokumentets sammanhang. |
| [setEmbedded](#setEmbedded-boolean-) | Ställer in ett värde som indikerar om teckensnittet är inbäddat. Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat |
| [setSubset](#setSubset-boolean-) | Ställer in ett värde som indikerar om teckensnittet är en delmängd. Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Bestämmer om fonten innehåller angivna tecken

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> Hämtar det faktiska teckensnittsnamnet för {@code Font} objektet om det är initierat. Även när teckensnittet har ersatts eller har internt namn för pdf. Eller tom sträng om teckensnittet inte är initierat. </p>

**Returns:**
String value <hr> <pre> Exemplet visar hur man söker text på den första sidan och visar det faktiska teckensnittsnamnet för den första textförekomsten. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Mäter den maximala Ascent-punkten.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

Hämtar BaseFont‑värdet för PDF‑teckensnittobjektet. Även känt som PostScript‑namnet för teckensnittet.

**Returns:**
String värde

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

Ibland kan PDF‑teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha ett specifikt teckensnittsnamn. Detta namn är värdet för PDF‑teckensnittsegenskapen \"BaseFont\" och ibland kan denna egenskap representeras i hexadecimal form. Om man läser detta namn direkt kan det visas i ett icke‑läsbart format. För att få ett läsbart format är det nödvändigt att avkoda teckensnittets namn enligt regler som är specifika för detta teckensnitt. Denna egenskap returnerar det avkodade teckensnittsnamnet, så använd den i fall där du stöter på ett icke‑läsbart {@code FontName}. Om egenskapen {@code FontName} har ett läsbart format kommer denna egenskap att vara densamma som {@code FontName}, så du kan använda den för alla fall där du behöver få teckensnittsnamnet i ett läsbart format.

**Returns:**
String värde

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Mäter den maximala Descent-punkten.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> Hämtar teckensnittsnamnet för {@code Font} objektet. </p>

**Returns:**
String value <hr> <pre> Exemplet visar hur man söker text på den första sidan och visar teckensnittsnamnet för den första textförekomsten. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Användbara egenskaper för att justera typsnittsbeteende

**Returns:**
IFontOptions-objekt

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> Systemteckensnittobjekt. </p> <hr> <p> Endast för internt bruk </p>

**Returns:**
IFont-objekt

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Pdf‑teckensnittobjekt. </p> <hr> <p> Endast för internt bruk </p>

**Returns:**
IPdfFont-objekt

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

Syftet med denna metod – att returnera felbeskrivning om ett försök att bädda in teckensnitt misslyckas. Om det inte finns några felreturneras en tom sträng.

**Returns:**
Felbeskrivning

### getType {#getType--}
```
public String getType()
```

Teckensnittets typnamn

**Returns:**
String-objekt

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Hämtar indikation på om teckensnittet finns (är installerat) i systemet. </p>

**Returns:**
booleskt värde <hr> <pre> Exemplet visar hur man söker text på den första sidan och får värdet som indikerar om teckensnittet är installerat i systemet. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println("the font is installed in the system"); </pre> <hr> <p> Vissa operationer är inte tillgängliga med teckensnitt som inte kunde hittas i systemet. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Hämtar ett värde som indikerar om teckensnittet är inbäddat. Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat </p> <hr> <pre> Följande exempel visar hur man hittar ett teckensnitt, markerar det som inbäddat, söker text på dokumentets sida och ersätter textens teckensnitt. // Skapa teckensnitt och markera det för inbäddning com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Arial\"); font.isEmbedded ( true); // öppna dokument com.aspose.pdf.Document doc = new com.aspose.pdf.Document(\"D:\\\\Tests\\\\input.pdf\"); // skapa TextFragmentAbsorber‑objekt för att hitta alla \"hello world\"-textförekomster com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber(\"hello world\"); // acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // ändra teckensnitt för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // spara dokumentet doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

**Returns:**
booleskt värde @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Hämtar ett värde som indikerar om teckensnittet är en delmängd. Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat </p> <hr> <pre> Exemplet visar hur man söker text på första sidan och får värdet som indikerar om teckensnittet är en delmängd. // Öppna dokument Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Skapa TextFragmentAbsorber‑objekt för att hitta alla \"hello world\"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // Visa teckensnittets IsSubset‑värde för den första textförekomsten if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println(\"the font is a subset\"); </pre>

**Returns:**
booleskt värde @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Mäter strängen.

### save {#save-java.io.OutputStream-}
Sparar teckensnittet i strömmen. Observera att teckensnittet sparas i ett mellansteg TTF-format som endast är avsett att användas i en konverterad kopia av det ursprungliga dokumentet. Teckensnittsfilen är inte avsedd att användas utanför det ursprungliga dokumentets sammanhang.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Ställer in ett värde som indikerar om teckensnittet är inbäddat. Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Ställer in ett värde som indikerar om teckensnittet är en delmängd. Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
