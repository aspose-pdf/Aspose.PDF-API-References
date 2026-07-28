---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar ett absorberingsobjekt för text. Utför textutvinning och ger åtkomst till resultatet via {@code TextAbsorber.Text} objekt. </p> <hr> <pre> Exemplet.</pre>"
type: docs
weight: 4900
url: /sv/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Representerar ett absorberingsobjekt för text. Utför textutdragning och ger åtkomst till resultatet via {@code TextAbsorber.Text}-objektet. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentets sida. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Objektet {@code TextAbsorber} används för att extrahera text från ett PDF-dokument eller dokumentets sida. </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> Initierar en ny instans av {@code TextAbsorber}. </p> <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Utför textutvinning och ger åtkomst till den extraherade texten via {@code TextAbsorber.Text} objekt. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> Initierar en ny instans av {@code TextAbsorber}. </p> <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Utför textutvinning och ger åtkomst till den extraherade texten via {@code TextAbsorber.Text} objekt. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> Initierar en ny instans av {@code TextAbsorber}. </p> <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Utför textutvinning och ger åtkomst till den extraherade texten via {@code TextAbsorber.Text} objekt. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Initierar en ny instans av {@code TextAbsorber}. </p> <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Utför textutvinning och ger åtkomst till den extraherade texten via {@code TextAbsorber.Text} objekt. </p> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getErrors](#getErrors--) | Lista över {@code TextExtractionError}-objekt. Den innehåller information om fel som hittades under textutdragning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Hämtar alternativ för textutvinning. </p> <hr> <pre> Exemplet visar hur man ställer in Pure-textformateringsläge och utför textutvinning. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text med formatering TextAbsorber absorber = new TextAbsorber(); // ställ in Pure-textformateringsläge absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Tillåter att definiera textformateringsläge {@code TextExtractionOptions} under utvinning. Standardläget är {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> Hämtar extraherad text som {@code TextAbsorber} extraherar i PDF-dokumentet eller på sidan. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Hämtar alternativ för textsökning. Tillåter att definiera en rektangel som avgränsar den extraherade texten. Som standard är rektangeln tom. Det betyder att sidgränserna ensamt definierar textutdragsområdet. |
| [hasErrors](#hasErrors--) | Värdet indikerar om fel hittades under textutvinning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestandan. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Ställer in alternativ för textutdragning. </p> <hr> <pre> Exemplet visar hur man ställer in Pure-textformateringsläge och utför textutdragning. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text med formatering TextAbsorber absorber = new TextAbsorber(); // ställ in pure-textformateringsläge absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Tillåter att definiera textformateringsläge {@code TextExtractionOptions} under extraktion. Standardläget är {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Ställer in alternativ för textsökning. Tillåter att definiera en rektangel som avgränsar den extraherade texten. Som standard är rektangeln tom. Det betyder att sidgränserna ensamt definierar textutdragsområdet. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extraherar text i det angivna dokumentet </p> <hr> <pre> Exemplet visar hur man extraherar text i ett PDF-dokument. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor absorber.visit(doc); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extraherar text på den angivna sidan </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentets sida. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor absorber.visit(doc.getPages(1)); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Extraherar text på den angivna XFormen. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentets sida. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> Initierar en ny instans av {@code TextAbsorber}. </p> <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Utför textutvinning och ger åtkomst till den extraherade texten via {@code TextAbsorber.Text} objekt. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> Initierar en ny instans av {@code TextAbsorber}. </p> <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Utför textutvinning och ger åtkomst till den extraherade texten via {@code TextAbsorber.Text} objekt. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> Initierar en ny instans av {@code TextAbsorber}. </p> <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Utför textutvinning och ger åtkomst till den extraherade texten via {@code TextAbsorber.Text} objekt. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Initierar en ny instans av {@code TextAbsorber}. </p> <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Utför textutvinning och ger åtkomst till den extraherade texten via {@code TextAbsorber.Text} objekt. </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Lista över {@code TextExtractionError}-objekt. Den innehåller information om fel som hittades under textutdragning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda.

**Returns:**
Lista över TextExtractionError-objekt

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Hämtar alternativ för textutvinning. </p> <hr> <pre> Exemplet visar hur man ställer in Pure-textformateringsläge och utför textutvinning. // öppna dokumentet Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text med formatering TextAbsorber absorber = new TextAbsorber(); // ställ in Pure-textformateringsläge absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Tillåter att definiera textformateringsläge {@code TextExtractionOptions} under utvinning. Standardläget är {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
TextExtractionOptions värde

### getText {#getText--}
```
public String getText()
```

<p> Hämtar extraherad text som {@code TextAbsorber} extraherar i PDF-dokumentet eller på sidan. </p>

**Returns:**
String värde <hr> <pre> Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Hämtar alternativ för textsökning. Tillåter att definiera en rektangel som avgränsar den extraherade texten. Som standard är rektangeln tom. Det betyder att sidgränserna ensamt definierar textutdragsområdet.

**Returns:**
TextSearchOptions värde

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

Värdet indikerar om fel hittades under textutvinning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestandan.

**Returns:**
booleskt värde

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Ställer in alternativ för textutdragning. </p> <hr> <pre> Exemplet visar hur man ställer in Pure-textformateringsläge och utför textutdragning. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text med formatering TextAbsorber absorber = new TextAbsorber(); // ställ in pure-textformateringsläge absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText(); </pre> <hr> <p> Tillåter att definiera textformateringsläge {@code TextExtractionOptions} under extraktion. Standardläget är {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Ställer in alternativ för textsökning. Tillåter att definiera en rektangel som avgränsar den extraherade texten. Som standard är rektangeln tom. Det betyder att sidgränserna ensamt definierar textutdragsområdet.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extraherar text i det angivna dokumentet </p> <hr> <pre> Exemplet visar hur man extraherar text i ett PDF-dokument. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor absorber.visit(doc); // hämta den extraherade texten String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extraherar text på den angivna sidan </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentets sida. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor absorber.visit(doc.getPages(1)); // hämta den extraherade texten String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Extraherar text på den angivna XFormen. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentets sida. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // hämta den extraherade texten String extractedText = absorber.getText(); </pre>
