---
title: "Schriftart"
linktitle: "Schriftart"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein Schriftart-Objekt dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und die Schriftart des ersten Suchvorkommens ändert. // Open document Document doc.</pre>"
type: docs
weight: 1650
url: /de/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> Stellt ein Schriftobjekt dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und die Schrift des ersten Suchvorkommens ändert. // Open document Document doc = new Document(\"input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Bestimmt, ob die Schriftart die angegebenen Zeichen enthält |
| [getActualFontName](#getActualFontName--) | <p> Ermittelt den tatsächlichen Schriftartnamen des {@code Font} Objekts, wenn es initialisiert ist. Auch wenn die Schriftart ersetzt wurde oder einen internen Namen für PDF hat. Oder eine leere Zeichenkette, wenn die Schriftart nicht initialisiert ist. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Misst den maximalen Aufstiegspunkt. |
| [getBaseFont](#getBaseFont--) | Ermittelt den BaseFont-Wert des PDF-Schriftartobjekts. Auch bekannt als PostScript-Name der Schriftart. |
| [getDecodedFontName](#getDecodedFontName--) | Manchmal können PDF-Schriftarten (häufig chinesische/japanische/koreanische Schriftarten) einen spezifischen Schriftartnamen haben. Dieser Name ist der Wert der PDF-Schriftarteigenschaft "BaseFont" und wird manchmal in hexadezimaler Form dargestellt. Wird dieser Name direkt gelesen, kann er in nicht lesbarer Form erscheinen. Um eine lesbare Form zu erhalten, muss der Schriftartname nach für diese Schriftart spezifischen Regeln dekodiert werden. Diese Eigenschaft gibt den dekodierten Schriftartnamen zurück, daher sollte sie in Fällen verwendet werden, in denen man auf einen nicht lesbaren {@code FontName} trifft. Hat die Eigenschaft {@code FontName} eine lesbare Form, ist diese Eigenschaft identisch mit {@code FontName}, sodass Sie sie in allen Fällen verwenden können, in denen Sie den Schriftartnamen in lesbarer Form benötigen. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Misst den maximalen Abstiegspunkt. |
| [getFontName](#getFontName--) | <p> Ermittelt den Schriftartnamen des {@code Font} Objekts. </p> |
| [getFontOptions](#getFontOptions--) | Nützliche Eigenschaften zum Anpassen des Schriftverhaltens |
| [getIFont](#getIFont--) | <p> System-Schriftartobjekt. </p> <hr> <p> Nur für interne Verwendung </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Pdf-Schriftartobjekt. </p> <hr> <p> Nur für interne Verwendung </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | Ziel dieser Methode – die Fehlbeschreibung zurückzugeben, wenn ein Versuch, die Schriftart einzubetten, fehlgeschlagen ist. Gibt es keine Fehlfälle, wird eine leere Zeichenkette zurückgegeben. |
| [getType](#getType--) | Der Typname der Schriftart |
| [isAccessible](#isAccessible--) | <p> Ermittelt, ob die Schriftart im System vorhanden (installiert) ist. </p> |
| [isEmbedded](#isEmbedded--) | <p> Ermittelt einen Wert, der angibt, ob die Schriftart eingebettet ist. Schriftarten, die auf IFont basieren, werden automatisch teilunterteilt und eingebettet </p> <hr> <pre> Das folgende Beispiel zeigt, wie man eine Schriftart findet, sie als eingebettet markiert, Text auf der Seite des Dokuments sucht und die Textschriftart ersetzt. // Schriftart erstellen und als eingebettet markieren com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // Dokument öffnen com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle "hello world"-Textvorkommen zu finden com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schriftart für das erste Textvorkommen ändern absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Gibt einen Wert zurück, der angibt, ob die Schriftart ein Subset ist. Auf IFont basierende Schriftarten werden automatisch als Subset eingebettet </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und den Wert erhält, der angibt, ob die Schriftart ein Subset ist. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Misst die Zeichenkette. |
| [save](#save-java.io.OutputStream-) | Speichert die Schriftart in den Stream. Hinweis: Die Schriftart wird im Zwischenschritt im TTF-Format gespeichert, das nur in einer konvertierten Kopie des Originaldokuments verwendet werden soll. Die Schriftartdatei ist nicht für die Verwendung außerhalb des ursprünglichen Dokumentkontexts vorgesehen. |
| [setEmbedded](#setEmbedded-boolean-) | Legt einen Wert fest, der angibt, ob die Schriftart eingebettet ist. Auf IFont basierende Schriftarten werden automatisch als Subset eingebettet. |
| [setSubset](#setSubset-boolean-) | Legt einen Wert fest, der angibt, ob die Schriftart ein Subset ist. Auf IFont basierende Schriftarten werden automatisch als Subset eingebettet. |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Bestimmt, ob die Schriftart die angegebenen Zeichen enthält

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> Ermittelt den tatsächlichen Schriftartnamen des {@code Font} Objekts, wenn es initialisiert ist. Auch wenn die Schriftart ersetzt wurde oder einen internen Namen für PDF hat. Oder eine leere Zeichenkette, wenn die Schriftart nicht initialisiert ist. </p>

**Returns:**
String value <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und den tatsächlichen Schriftartnamen einer ersten Texteinstanz anzeigt. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Misst den maximalen Aufstiegspunkt.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

Ermittelt den BaseFont-Wert des PDF-Schriftartobjekts. Auch bekannt als PostScript-Name der Schriftart.

**Returns:**
String Wert

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

Manchmal können PDF-Schriftarten (häufig chinesische/japanische/koreanische Schriftarten) einen spezifischen Schriftartnamen haben. Dieser Name ist der Wert der PDF-Schriftarteigenschaft "BaseFont" und wird manchmal in hexadezimaler Form dargestellt. Wird dieser Name direkt gelesen, kann er in nicht lesbarer Form erscheinen. Um eine lesbare Form zu erhalten, muss der Schriftartname nach für diese Schriftart spezifischen Regeln dekodiert werden. Diese Eigenschaft gibt den dekodierten Schriftartnamen zurück, daher sollte sie in Fällen verwendet werden, in denen man auf einen nicht lesbaren {@code FontName} trifft. Hat die Eigenschaft {@code FontName} eine lesbare Form, ist diese Eigenschaft identisch mit {@code FontName}, sodass Sie sie in allen Fällen verwenden können, in denen Sie den Schriftartnamen in lesbarer Form benötigen.

**Returns:**
String Wert

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Misst den maximalen Abstiegspunkt.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> Ermittelt den Schriftartnamen des {@code Font} Objekts. </p>

**Returns:**
String value <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und den Schriftartnamen einer ersten Texteinstanz anzeigt. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Nützliche Eigenschaften zum Anpassen des Schriftverhaltens

**Returns:**
IFontOptions-Objekt

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> System-Schriftartobjekt. </p> <hr> <p> Nur für interne Verwendung </p>

**Returns:**
IFont-Objekt

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Pdf-Schriftartobjekt. </p> <hr> <p> Nur für interne Verwendung </p>

**Returns:**
IPdfFont-Objekt

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

Ziel dieser Methode – die Fehlbeschreibung zurückzugeben, wenn ein Versuch, die Schriftart einzubetten, fehlgeschlagen ist. Gibt es keine Fehlfälle, wird eine leere Zeichenkette zurückgegeben.

**Returns:**
Fehlerbeschreibung

### getType {#getType--}
```
public String getType()
```

Der Typname der Schriftart

**Returns:**
String-Objekt

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Ermittelt, ob die Schriftart im System vorhanden (installiert) ist. </p>

**Returns:**
boolescher Wert <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und den Wert ermittelt, der angibt, ob die Schriftart im System installiert ist. // Öffne Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get_Item(1).accept(absorber); // Zeige den IsSubset-Wert der Schriftart des ersten Textelements an if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println("die Schriftart ist im System installiert"); </pre> <hr> <p> Einige Vorgänge sind nicht verfügbar für Schriftarten, die im System nicht gefunden werden konnten. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Gibt einen Wert zurück, der angibt, ob die Schriftart eingebettet ist. Auf IFont basierende Schriftarten werden automatisch unterteilt und eingebettet </p> <hr> <pre> Das folgende Beispiel zeigt, wie man eine Schriftart findet, sie als eingebettet markiert, Text auf der Seite des Dokuments sucht und die Schriftart des Textes ersetzt. // Erstelle Schriftart und markiere sie zum Einbetten com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // Öffne Dokument com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get_Item(1).accept(absorber); // Ändere die Schriftart für das erste Textelement absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Speichere Dokument doc.save("D:\\Tests\\output.pdf"); </pre>

**Returns:**
boolescher Wert @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Gibt einen Wert zurück, der angibt, ob die Schriftart ein Subset ist. Auf IFont basierende Schriftarten werden automatisch unterteilt und eingebettet </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und den Wert ermittelt, der angibt, ob die Schriftart ein Subset ist. // Öffne Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get_Item(1).accept(absorber); // Zeige den IsSubset-Wert der Schriftart des ersten Textelements an if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("die Schriftart ist ein Subset"); </pre>

**Returns:**
boolescher Wert @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Misst die Zeichenkette.

### save {#save-java.io.OutputStream-}
Speichert die Schriftart in den Stream. Hinweis: Die Schriftart wird im Zwischenschritt im TTF-Format gespeichert, das nur in einer konvertierten Kopie des Originaldokuments verwendet werden soll. Die Schriftartdatei ist nicht für die Verwendung außerhalb des ursprünglichen Dokumentkontexts vorgesehen.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Legt einen Wert fest, der angibt, ob die Schriftart eingebettet ist. Auf IFont basierende Schriftarten werden automatisch als Subset eingebettet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Legt einen Wert fest, der angibt, ob die Schriftart ein Subset ist. Auf IFont basierende Schriftarten werden automatisch als Subset eingebettet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
