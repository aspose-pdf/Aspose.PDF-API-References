---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein Absorber-Objekt für Text dar. Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf das Ergebnis bereit. </p> <hr> <pre> Das Beispiel."
type: docs
weight: 4900
url: /de/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Stellt ein Absorber-Objekt für Text dar. Führt Textextraktion durch und bietet Zugriff auf das Ergebnis über das {@code TextAbsorber.Text}-Objekt. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Das {@code TextAbsorber}-Objekt wird verwendet, um Text aus einem Pdf-Dokument oder einer Dokumentenseite zu extrahieren. </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> Initialisiert eine neue Instanz des {@code TextAbsorber}. </p> <hr> <pre> Das Beispiel zeigt, wie Text von allen Seiten des PDF-Dokuments extrahiert wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf den extrahierten Text bereit. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> Initialisiert eine neue Instanz des {@code TextAbsorber}. </p> <hr> <pre> Das Beispiel zeigt, wie Text von allen Seiten des PDF-Dokuments extrahiert wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf den extrahierten Text bereit. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> Initialisiert eine neue Instanz des {@code TextAbsorber}. </p> <hr> <pre> Das Beispiel zeigt, wie Text von allen Seiten des PDF-Dokuments extrahiert wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf den extrahierten Text bereit. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Initialisiert eine neue Instanz des {@code TextAbsorber}. </p> <hr> <pre> Das Beispiel zeigt, wie Text von allen Seiten des PDF-Dokuments extrahiert wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf den extrahierten Text bereit. </p> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getErrors](#getErrors--) | Liste von {@code TextExtractionError}-Objekten. Sie enthält Informationen über Fehler, die bei der Textextraktion gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Ruft Textextraktionsoptionen ab. </p> <hr> <pre> Das Beispiel zeigt, wie der reine Textformatierungsmodus gesetzt und Textextraktion durchgeführt wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text mit Formatierung zu extrahieren TextAbsorber absorber = new TextAbsorber(); // reinen Textformatierungsmodus setzen absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Ermöglicht die Definition des Textformatierungsmodus {@code TextExtractionOptions} während der Extraktion. Der Standardmodus ist {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> Ruft den extrahierten Text ab, den der {@code TextAbsorber} aus dem PDF-Dokument oder einer Seite extrahiert. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Ruft Textsuchoptionen ab. Ermöglicht die Definition eines Rechtecks, das den extrahierten Text begrenzt. Standardmäßig ist das Rechteck leer. Das bedeutet, dass nur die Seitenränder die Textextraktionsregion festlegen. |
| [hasErrors](#hasErrors--) | Der Wert gibt an, ob bei der Textextraktion Fehler gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Setzt Optionen für die Textextraktion. </p> <hr> <pre> Das Beispiel zeigt, wie man den reinen Textformatierungsmodus einstellt und die Textextraktion durchführt. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Ermöglicht die Definition des Textformatierungsmodus {@code TextExtractionOptions} während der Extraktion. Der Standardmodus ist {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Setzt Optionen für die Textsuche. Ermöglicht die Definition eines Rechtecks, das den extrahierten Text begrenzt. Standardmäßig ist das Rechteck leer. Das bedeutet, dass nur die Seitenränder den Textextraktionsbereich definieren. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extrahiert Text im angegebenen Dokument </p> <hr> <pre> Das Beispiel zeigt, wie man Text in einem PDF-Dokument extrahiert. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extrahiert Text auf der angegebenen Seite </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments extrahiert. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Extrahiert Text im angegebenen XForm. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments extrahiert. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> Initialisiert eine neue Instanz des {@code TextAbsorber}. </p> <hr> <pre> Das Beispiel zeigt, wie Text von allen Seiten des PDF-Dokuments extrahiert wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf den extrahierten Text bereit. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> Initialisiert eine neue Instanz des {@code TextAbsorber}. </p> <hr> <pre> Das Beispiel zeigt, wie Text von allen Seiten des PDF-Dokuments extrahiert wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf den extrahierten Text bereit. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> Initialisiert eine neue Instanz des {@code TextAbsorber}. </p> <hr> <pre> Das Beispiel zeigt, wie Text von allen Seiten des PDF-Dokuments extrahiert wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf den extrahierten Text bereit. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Initialisiert eine neue Instanz des {@code TextAbsorber}. </p> <hr> <pre> Das Beispiel zeigt, wie Text von allen Seiten des PDF-Dokuments extrahiert wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Führt Textextraktion durch und stellt über das {@code TextAbsorber.Text}-Objekt Zugriff auf den extrahierten Text bereit. </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Liste von {@code TextExtractionError}-Objekten. Sie enthält Informationen über Fehler, die bei der Textextraktion gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern.

**Returns:**
Liste von TextExtractionError-Objekten

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Ruft Textextraktionsoptionen ab. </p> <hr> <pre> Das Beispiel zeigt, wie der reine Textformatierungsmodus gesetzt und Textextraktion durchgeführt wird. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text mit Formatierung zu extrahieren TextAbsorber absorber = new TextAbsorber(); // reinen Textformatierungsmodus setzen absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // extrahierten Text abrufen String extractedText = absorber.getText(); </pre> <hr> <p> Ermöglicht die Definition des Textformatierungsmodus {@code TextExtractionOptions} während der Extraktion. Der Standardmodus ist {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
TextExtractionOptions Wert

### getText {#getText--}
```
public String getText()
```

<p> Ruft den extrahierten Text ab, den der {@code TextAbsorber} aus dem PDF-Dokument oder einer Seite extrahiert. </p>

**Returns:**
String Wert <hr> <pre> Das Beispiel zeigt, wie man Text aus allen Seiten des PDF-Dokuments extrahiert. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Ruft Textsuchoptionen ab. Ermöglicht die Definition eines Rechtecks, das den extrahierten Text begrenzt. Standardmäßig ist das Rechteck leer. Das bedeutet, dass nur die Seitenränder die Textextraktionsregion festlegen.

**Returns:**
TextSearchOptions Wert

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

Der Wert gibt an, ob bei der Textextraktion Fehler gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern.

**Returns:**
boolescher Wert

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Setzt Optionen für die Textextraktion. </p> <hr> <pre> Das Beispiel zeigt, wie man den reinen Textformatierungsmodus einstellt und die Textextraktion durchführt. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Ermöglicht die Definition des Textformatierungsmodus {@code TextExtractionOptions} während der Extraktion. Der Standardmodus ist {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Setzt Optionen für die Textsuche. Ermöglicht die Definition eines Rechtecks, das den extrahierten Text begrenzt. Standardmäßig ist das Rechteck leer. Das bedeutet, dass nur die Seitenränder den Textextraktionsbereich definieren.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extrahiert Text im angegebenen Dokument </p> <hr> <pre> Das Beispiel zeigt, wie man Text in einem PDF-Dokument extrahiert. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extrahiert Text auf der angegebenen Seite </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments extrahiert. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Extrahiert Text im angegebenen XForm. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments extrahiert. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre>
