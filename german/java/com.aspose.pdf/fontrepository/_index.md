---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Führt eine Schriftartsuche durch. Durchsucht systeminstallierte Schriftarten und Standard Pdf‑Schriftarten. Bietet außerdem die Möglichkeit, benutzerdefinierte Schriftarten zu öffnen. </p> <hr> <pre> Das Beispiel zeigt."
type: docs
weight: 1690
url: /de/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Führt eine Schriftartsuche durch. Durchsucht systeminstallierte Schriftarten und Standard Pdf‑Schriftarten. Bietet außerdem die Möglichkeit, benutzerdefinierte Schriftarten zu öffnen. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt. // Schriftart finden Font font = FontRepository.findFont("Arial"); // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle "hello world"-Textvorkommen zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Füge einen weiteren Pfad zu Schriftarten hinzu. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Systemschriftart mit angegebener Schrift hinzufügen. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Systemschriftart hinzufügt. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Durchsucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt. // Schriftart finden Font font = FontRepository.findFont("Arial"); // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle "hello world"-Textvorkommen zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück, wobei die Groß‑/Kleinschreibung ignoriert oder berücksichtigt wird. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil zurück. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil zurück, wobei die Groß‑/Kleinschreibung ignoriert oder berücksichtigt wird. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Kopie der Liste mit den tatsächlichen Schriftartverzeichnissen. |
| [getSources](#getSources--) | Liefert die Sammlung der Schriftquellen. |
| [getSubstitutions](#getSubstitutions--) | Liefert die Sammlung der Schriftart‑Ersetzungsstrategien. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | Nicht gefundene Schriftarten werden durch die Standardschriftart ersetzt. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Gibt den Status der Font Sources Speicherkonfiguration zurück. <br> Wenn true, wird ThreadStatic verwendet und jeder Thread hat eigene Font Sources. <br> Wenn false, wird eine globale statische Konfiguration für alle Threads verwendet. </p> <hr> Standardwert ist True. |
| [loadFonts](#loadFonts--) | Lädt systeminstallierte Schriftarten und Standard‑Pdf‑Schriftarten. Diese Methode wurde entwickelt, um den Schriftarten‑Ladevorgang zu beschleunigen. Standardmäßig werden Schriftarten bei der ersten Anforderung einer Schriftart geladen. Die Verwendung dieser Methode lädt system- und Standard‑Pdf‑Schriftarten sofort, bevor ein Pdf‑Dokument geöffnet wird. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Öffnet Schriftart mit angegebenem Schriftstrom. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart öffnet und die Schriftart des Textes der ersten Seite ersetzt. // Schriftart öffnen InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get_Item(1).accept(absorber); // Ändere die Schriftart des ersten Textvorkommens absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Öffnet Schriftart mit angegebenem Schriftdateipfad. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart öffnet und die Schriftart des Textes der ersten Seite ersetzt. // Schriftart öffnen Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get_Item(1).accept(absorber); // Ändere die Schriftart des ersten Textvorkommens absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Öffnet Schriftart mit angegebenem Schriftdateipfad und Metrikdateipfad. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Type1-Schriftart mit Metriken öffnet und die Schriftart des Textes der ersten Seite ersetzt. // Schriftart öffnen Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get_Item(1).accept(absorber); // Ändere die Schriftart des ersten Textvorkommens absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | Lädt alle Schriftarten, die durch die Eigenschaft {@code Sources}({@link #getSources}) angegeben sind, neu. |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Stellt standardmäßig die Liste für Standard‑Schriftverzeichnisse wieder her. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Setzt Benutzerliste mit Schriftartpfaden |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Setze TRUE, wenn nicht gefundene Schriftarten durch die Standardschriftart ersetzt werden sollen. Der Standardwert ist false. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Option für die Einstellung der Font Sources Speicher‑Konfiguration. Wenn true, wird ThreadStatic verwendet und jeder Thread hat eigene Font Sources. Wenn false, wird eine globale statische Konfiguration für alle Threads verwendet. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Füge einen weiteren Pfad zu Schriftarten hinzu.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Systemschriftart mit angegebener Schrift hinzufügen. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Systemschriftart hinzufügt. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart findet und die Schrift des Textes auf der ersten Seite ersetzt. // Schriftart finden Font font = FontRepository.findFont("Arial"); // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schrift der ersten Texteinstanz ändern absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück, wobei die Groß-/Kleinschreibung ignoriert oder berücksichtigt wird. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart findet und die Schrift des Textes auf der ersten Seite ersetzt. // Schriftart finden Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schrift der ersten Texteinstanz ändern absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil zurück. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart findet und die Schrift des Textes auf der ersten Seite ersetzt. // Schriftart finden Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schrift der ersten Texteinstanz ändern absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Sucht und gibt die Schriftart mit angegebenem Schriftartnamen und Schriftstil zurück, wobei die Groß-/Kleinschreibung ignoriert oder beachtet wird. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes auf der ersten Seite ersetzt. // Schriftart finden Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Kopie der Liste mit den tatsächlichen Schriftartverzeichnissen.

**Returns:**
Liste von String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Liefert die Sammlung der Schriftquellen.

**Returns:**
FontSourceCollection-Objekt

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Liefert die Sammlung der Schriftart‑Ersetzungsstrategien.

**Returns:**
FontSubstitutionCollection-Objekt

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

Nicht gefundene Schriftarten werden durch die Standardschriftart ersetzt.

**Returns:**
boolescher Wert

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Gibt den Status der Font Sources Speicherkonfiguration zurück. <br> Wenn true, wird ThreadStatic verwendet und jeder Thread hat eigene Font Sources. <br> Wenn false, wird eine globale statische Konfiguration für alle Threads verwendet. </p> <hr> Standardwert ist True.

**Returns:**
boolescher Wert

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Lädt systeminstallierte Schriftarten und Standard‑Pdf‑Schriftarten. Diese Methode wurde entwickelt, um den Schriftarten‑Ladevorgang zu beschleunigen. Standardmäßig werden Schriftarten bei der ersten Anforderung einer Schriftart geladen. Die Verwendung dieser Methode lädt system- und Standard‑Pdf‑Schriftarten sofort, bevor ein Pdf‑Dokument geöffnet wird.

### openFont {#openFont-java.io.InputStream-int-}
<p> Öffnet eine Schriftart mit dem angegebenen Schriftart-Stream. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Schriftart öffnet und die Schriftart des Textes auf der ersten Seite ersetzt. // Schriftart öffnen InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Öffnet eine Schriftart mit dem angegebenen Schriftart-Dateipfad. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Schriftart öffnet und die Schriftart des Textes auf der ersten Seite ersetzt. // Schriftart öffnen Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Öffnet die Schrift mit dem angegebenen Schriftdateipfad und dem Metrikdateipfad. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Type1‑Schrift mit Metriken öffnet und die Schrift des Textes der ersten Seite ersetzt. // Open font // Schrift öffnen Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences // TextFragmentAbsorber‑Objekt erstellen, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence // Schrift des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

Lädt alle Schriftarten, die durch die Eigenschaft {@code Sources}({@link #getSources}) angegeben sind, neu.

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Stellt standardmäßig die Liste für Standard‑Schriftverzeichnisse wieder her.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Setzt Benutzerliste mit Schriftartpfaden

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Setze TRUE, wenn nicht gefundene Schriftarten durch die Standardschriftart ersetzt werden sollen. Der Standardwert ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Option für die Einstellung der Font Sources Speicher‑Konfiguration. Wenn true, wird ThreadStatic verwendet und jeder Thread hat eigene Font Sources. Wenn false, wird eine globale statische Konfiguration für alle Threads verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isTheadLocal |  | boolescher Wert |
