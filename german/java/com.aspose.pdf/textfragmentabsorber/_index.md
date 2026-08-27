---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein Absorber-Objekt für Textfragmente dar. Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p>."
type: docs
weight: 5120
url: /de/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Stellt ein Absorber-Objekt für Textfragmente dar. Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text sowie die Schriftart ersetzt. // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen, um alle "hello world"-Textvorkommen zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text und Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Das {@code TextFragmentAbsorber}-Objekt wird grundsätzlich im Szenario der Textsuche verwendet. Wenn die Suche abgeschlossen ist, werden die Vorkommen durch {@code TextFragment}-Objekte dargestellt, die in der {@code TextFragmentAbsorber.TextFragments}-Sammlung enthalten sind. Das {@code TextFragment}-Objekt bietet Zugriff auf den Text des Suchvorkommens, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.). </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, das die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern des Dokumenttextes verwendet wird Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber so konfigurieren, dass er alle "hello world"-Textvorkommen sucht absorber.setPhrase ( "hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Wendet die Schriftgröße für alle absorbierten Textfragmente an. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Wendet die Schriftart für alle absorbierten Textfragmente an. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Wendet Schriftart und -größe für alle absorbierten Textfragmente an. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| [getErrors](#getErrors--) | Liste von {@code TextExtractionError}-Objekten. Sie enthält Informationen über Fehler, die bei der Textextraktion gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern. |
| [getExtractionOptions](#getExtractionOptions--) | Liefert die Textextraktionsoptionen. |
| [getPhrase](#getPhrase--) | <p> Liefert den Ausdruck, den {@code TextFragmentAbsorber} im PDF-Dokument oder auf der Seite sucht. </p> |
| [getRegexResults](#getRegexResults--) | Liefert ein Wörterbuch der Suchvorkommen, das mit der Klasse System.Text.RegularExpressions.Regex als Schlüssel und {@link TextFragment} als Wert dargestellt wird. Das Beispiel zeigt, wie man Text mit einem Array von regulären Ausdrücken auf der ersten Seite des PDF-Dokuments findet. // Open document Document doc = new Document(\"input.pdf\"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | Liefert den extrahierten Text, den {@code TextAbsorber} im PDF-Dokument oder auf der Seite extrahiert. |
| [getTextEditOptions](#getTextEditOptions--) | Liefert die Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [getTextFragments](#getTextFragments--) | <p> Liefert die Sammlung von Suchvorkommen, die mit {@code TextFragment}-Objekten dargestellt werden. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Ermittelt die Optionen zum Ersetzen von Text. Die Optionen definieren das Verhalten, wenn der Fragmenttext durch einen kürzeren/längeren Text ersetzt wird. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Liefert die Suchoptionen. Die Optionen ermöglichen die Suche mit regulären Ausdrücken. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | Der Wert gibt an, ob bei der Textextraktion Fehler gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Entfernt allen Text aus dem Dokument. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Entfernt allen Text von der angegebenen Seite. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Entfernt Text innerhalb des angegebenen Rechtecks von der angegebenen Seite. |
| [reset](#reset--) | Leert die TextFragments-Sammlung dieses {@code TextFragmentAbsorber}-Objekts. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Setzt die Textextraktionsoptionen. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> Setzt den Ausdruck, den {@code TextFragmentAbsorber} im PDF-Dokument oder auf der Seite sucht. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Setzt die Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> Setzt die Sammlung von Suchvorkommen, die mit {@code TextFragment}-Objekten dargestellt werden. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Setzt die Textersetzungsoptionen. Die Optionen definieren das Verhalten, wenn Fragmenttext durch kürzeren/längeren Text ersetzt wird. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Legt Suchoptionen fest. Die Optionen ermöglichen die Suche mit regulären Ausdrücken. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Führt die Suche im angegebenen Dokument aus. </p> <hr> <pre> Das Beispiel zeigt, wie man Text in einem PDF-Dokument findet und den Text aller Suchvorkommen ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt, um alle "hello world"-Textvorkommen zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiert den Absorber für die erste Seite absorber.visit(doc); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Führt die Suche auf der angegebenen Seite aus. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt, um alle "hello world"-Textvorkommen zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiert den Absorber für die erste Seite absorber.visit(doc.getPages().get(1)); // Ändert den Text aller Suchvorkommen für (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Führt die Suche im angegebenen Form-Objekt aus. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Initialisiert eine neue Instanz des {@code TextFragmentAbsorber}, die die Suche aller Textsegmente des Dokuments oder der Seite ausführt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Konfiguriert den Absorber, um alle "hello world"-Textvorkommen zu suchen absorber.setPhrase ( "hello world"); // Akzeptiert den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Führt die Textsuche aus und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Kollektion. </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Wendet die Schriftgröße für alle absorbierten Textfragmente an. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontSize |  | Schriftgröße des Textes. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Wendet die Schriftart für alle absorbierten Textfragmente an. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Wendet Schriftart und -größe für alle absorbierten Textfragmente an. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen.

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

Liefert die Textextraktionsoptionen.

**Returns:**
TextExtractionOptions-Objekt

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> Liefert den Ausdruck, den {@code TextFragmentAbsorber} im PDF-Dokument oder auf der Seite sucht. </p>

**Returns:**
String-Wert <hr> <pre> Das Beispiel zeigt, wie man die Textsuche mehrmals ausführt und Textersetzungen vornimmt. // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes \"hello\" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // ein weiteres Wort suchen und ersetzen absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Liefert ein Wörterbuch der Suchvorkommen, das mit der Klasse System.Text.RegularExpressions.Regex als Schlüssel und {@link TextFragment} als Wert dargestellt wird. Das Beispiel zeigt, wie man Text mit einem Array von regulären Ausdrücken auf der ersten Seite des PDF-Dokuments findet. // Open document Document doc = new Document(\"input.pdf\"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
Dictionary-Instanz

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

Liefert den extrahierten Text, den {@code TextAbsorber} im PDF-Dokument oder auf der Seite extrahiert.

**Returns:**
String-Wert Das Beispiel zeigt, wie man Text aus allen Seiten des PDF-Dokuments extrahiert. // Dokument öffnen Document doc = new Document(inFile); // TextAbsorber-Objekt erstellen, um Text zu extrahieren TextAbsorber absorber = new TextAbsorber(); // den Absorber für alle Seiten des Dokuments akzeptieren doc.getPages().accept(absorber); // den extrahierten Text abrufen String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Liefert die Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart geschrieben werden kann.

**Returns:**
TextEditOptions-Objekt

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> Liefert die Sammlung von Suchvorkommen, die mit {@code TextFragment}-Objekten dargestellt werden. </p>

**Returns:**
TextFragmentCollection-Objekt <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments findet und alle Suchvorkommen durch neuen Text ersetzt. // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // Schriftart finden, die verwendet wird, um die Dokumentschriftart zu ändern Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes \"hello world\" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text aller Suchvorkommen ändern for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Ermittelt die Optionen zum Ersetzen von Text. Die Optionen definieren das Verhalten, wenn der Fragmenttext durch einen kürzeren/längeren Text ersetzt wird.

**Returns:**
TextReplaceOptions-Wert

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Liefert die Suchoptionen. Die Optionen ermöglichen die Suche mit regulären Ausdrücken. </p>

**Returns:**
TextSearchOptions-Objekt <hr> <pre> Das Beispiel zeigt, wie man die Textsuche mit regulären Ausdrücken durchführt. // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // den Absorber so konfigurieren, dass er alle Wörter, die mit 'h' beginnen und mit 'o' enden, mittels regulärem Ausdruck sucht. absorber.setPhrase ( "h\\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // wir sollten das Wort \"hello\" finden und durch \"Hi\" ersetzen doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

Der Wert gibt an, ob bei der Textextraktion Fehler gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern.

**Returns:**
boolescher Wert

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Entfernt allen Text aus dem Dokument.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Entfernt allen Text von der angegebenen Seite.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Entfernt Text innerhalb des angegebenen Rechtecks von der angegebenen Seite.

### reset {#reset--}
```
public void reset()
```

Leert die TextFragments-Sammlung dieses {@code TextFragmentAbsorber}-Objekts.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Setzt die Textextraktionsoptionen.

### setPhrase {#setPhrase-java.lang.String-}
<p> Setzt den Ausdruck, den {@code TextFragmentAbsorber} im PDF-Dokument oder auf der Seite sucht. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Setzt die Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart geschrieben werden kann.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> Setzt die Sammlung von Suchvorkommen, die mit {@code TextFragment}-Objekten dargestellt werden. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Setzt die Textersetzungsoptionen. Die Optionen definieren das Verhalten, wenn Fragmenttext durch kürzeren/längeren Text ersetzt wird.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Legt Suchoptionen fest. Die Optionen ermöglichen die Suche mit regulären Ausdrücken. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Führt eine Suche im angegebenen Dokument aus. </p> <hr> <pre> Das Beispiel zeigt, wie man Text in einem PDF-Dokument findet und den Text aller Suchvorkommen ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt, um alle \"hello world\"-Textvorkommen zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiert den Absorber für die erste Seite absorber.visit(doc); // Ändert den Text des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Führt eine Suche auf der angegebenen Seite aus. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text ersetzt. // Öffnet das Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Findet die Schriftart, die zum Ändern der Dokument-Textschrift verwendet wird Font font = FontRepository.findFont("Arial"); // Erstellt ein TextFragmentAbsorber-Objekt, um alle \"hello world\"-Textvorkommen zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiert den Absorber für die erste Seite absorber.visit(doc.getPages().get(1)); // Ändert den Text aller Suchvorkommen for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Speichert das Dokument doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Führt die Suche im angegebenen Form-Objekt aus.
