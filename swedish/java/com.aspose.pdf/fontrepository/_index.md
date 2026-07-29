---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Utför fontsökning. Söker i systeminstallerade fonter och standard‑Pdf‑fonter. Tillhandahåller också funktionalitet för att öppna anpassade fonter. </p> <hr> <pre> Exemplet demonstrerar."
type: docs
weight: 1690
url: /sv/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Utför fontsökning. Söker i systeminstallerade fonter och standard‑Pdf‑fonter. Tillhandahåller också funktionalitet för att öppna anpassade fonter. </p> <hr> <pre> Exemplet demonstrerar hur man hittar en font och ersätter fonten i texten på första sidan. // Find font Font font = FontRepository.findFont(\"Arial\"); // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> @see TextFragmentAbsorber @see IDocument

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Lägg till ytterligare en sökväg till fonter. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Lägg till systemfont med angiven font. </p> <hr> <pre> Exemplet demonstrerar hur man lägger till en systemfont. InputStream fontStream = new FileInputStream(\"C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf\")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Söker och returnerar font med angivet fonternamn. </p> <hr> <pre> Exemplet demonstrerar hur man hittar en font och ersätter fonten i texten på första sidan. // Find font Font font = FontRepository.findFont(\"Arial\"); // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Söker och returnerar teckensnitt med angivet teckensnittsnamn, ignorerar eller respekterar skiftlägeskänslighet. </p> <hr> <pre> Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för text på första sidan. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil. </p> <hr> <pre> Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för text på första sidan. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil, ignorerar eller respekterar skiftlägeskänslighet. </p> <hr> <pre> Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för text på första sidan. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Kopia av listan med faktiska teckensnittskataloger. |
| [getSources](#getSources--) | Hämtar samling av teckensnittskällor. |
| [getSubstitutions](#getSubstitutions--) | Hämtar samling av teckensnittssubstitutionsstrategier. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | Om teckensnitt inte hittas kommer de att ersättas med standardteckensnitt. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Returnerar status för konfiguration av lagring av teckensnittskällor. <br> Om true används ThreadStatic och varje tråd har egna teckensnittskällor. <br> Om false används global statisk konfiguration för alla trådar. </p> <hr> Standardvärdet är True. |
| [loadFonts](#loadFonts--) | Laddar systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt. Denna metod är utformad för att snabba upp teckensnittsladdningsprocessen. Som standard laddas teckensnitt vid första begäran för ett teckensnitt. Användning av denna metod laddar system‑ och standard‑Pdf‑teckensnitt omedelbart innan något Pdf‑dokument öppnas. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Öppnar teckensnitt med angiven teckensnittström. </p> <hr> <pre> Exemplet visar hur man öppnar teckensnitt och ersätter teckensnittet för text på den första sidan. // Open font InputStream fontStream = new FileInputStream(\"C:\\\\\\WINDOWS\\\\\\\Fonts\\\\\\\arial.ttf\")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\output.pdf\"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Öppnar teckensnitt med angiven teckensnittssökväg. </p> <hr> <pre> Exemplet visar hur man öppnar teckensnitt och ersätter teckensnittet för text på den första sidan. // Open font Font font = FontRepository.openFont(\"C:\\\\\\WINDOWS\\\\\\\Fonts\\\\\\\arial.ttf\"); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\output.pdf\"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Öppnar teckensnitt med angiven teckensnittssökväg och metrisökväg. </p> <hr> <pre> Exemplet visar hur man öppnar Type1-teckensnitt med metriska data och ersätter teckensnittet för text på den första sidan. // Open font Font font = FontRepository.openFont(\"courier.pfb\", \"courier.afm\"); // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\output.pdf\"); </pre> |
| [reloadFonts](#reloadFonts--) | Laddar om alla teckensnitt som anges av egenskapen {@code Sources}({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Återställer listan för standardteckensnittskataloger som standard. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Ställer in användarlistan med teckensnittssökvägar |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Ange SANT om du behöver ersätta ej hittade teckensnitt med standardteckensnittet. Standardvärdet är falskt. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Alternativ för att ställa in lagringskonfiguration för Font Sources. Om sant används ThreadStatic och varje tråd har egna Font Sources. Om falskt används global statisk konfiguration för alla trådar. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Lägg till ytterligare en sökväg till fonter.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Lägg till systemteckensnitt med angivet teckensnitt. </p> <hr> <pre> Exemplet visar hur man lägger till systemteckensnitt. InputStream fontStream = new FileInputStream(\"C:\\WINDOWS\\Fonts\\arial.ttf\")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Söker och returnerar teckensnitt med angivet teckensnittsnamn. </p> <hr> <pre> Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för text på den första sidan. // Hitta teckensnitt Font font = FontRepository.findFont(\"Arial\"); // Öppna dokument Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Skapa TextFragmentAbsorber-objekt för att hitta alla \"hello world\"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // Ändra teckensnitt för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Spara dokument doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Söker och returnerar teckensnitt med angivet teckensnittsnamn, med eller utan hänsyn till skiftlägeskänslighet. </p> <hr> <pre> Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för text på den första sidan. // Hitta teckensnitt Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Öppna dokument Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Skapa TextFragmentAbsorber-objekt för att hitta alla \"hello world\"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // Ändra teckensnitt för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Spara dokument doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil. </p> <hr> <pre> Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för text på den första sidan. // Hitta teckensnitt Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Öppna dokument Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Skapa TextFragmentAbsorber-objekt för att hitta alla \"hello world\"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // Ändra teckensnitt för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Spara dokument doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil, med eller utan hänsyn till skiftlägeskänslighet. </p> <hr> <pre> Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för text på den första sidan. // Hitta teckensnitt Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Öppna dokument Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Skapa TextFragmentAbsorber-objekt för att hitta alla \"hello world\"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // Ändra teckensnitt för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Spara dokument doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Kopia av listan med faktiska teckensnittskataloger.

**Returns:**
lista med String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Hämtar samling av teckensnittskällor.

**Returns:**
FontSourceCollection-objekt

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Hämtar samling av teckensnittssubstitutionsstrategier.

**Returns:**
FontSubstitutionCollection-objekt

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

Om teckensnitt inte hittas kommer de att ersättas med standardteckensnitt.

**Returns:**
booleskt värde

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Returnerar status för konfiguration av lagring av teckensnittskällor. <br> Om true används ThreadStatic och varje tråd har egna teckensnittskällor. <br> Om false används global statisk konfiguration för alla trådar. </p> <hr> Standardvärdet är True.

**Returns:**
booleskt värde

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Laddar systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt. Denna metod är utformad för att snabba upp teckensnittsladdningsprocessen. Som standard laddas teckensnitt vid första begäran för ett teckensnitt. Användning av denna metod laddar system‑ och standard‑Pdf‑teckensnitt omedelbart innan något Pdf‑dokument öppnas.

### openFont {#openFont-java.io.InputStream-int-}
<p> Öppnar teckensnitt med specificerad teckensnittström. </p> <hr> <pre> Exemplet visar hur man öppnar teckensnitt och ersätter teckensnittet för text på första sidan. // Open font InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Öppnar teckensnitt med specificerad teckensnittssökväg. </p> <hr> <pre> Exemplet visar hur man öppnar teckensnitt och ersätter teckensnittet för text på första sidan. // Open font Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Öppnar teckensnitt med specificerad teckensnittssökväg och metrikfilssökväg. </p> <hr> <pre> Exemplet visar hur man öppnar Type1-teckensnitt med metrik och ersätter teckensnittet för text på första sidan. // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

Laddar om alla teckensnitt som anges av egenskapen {@code Sources}({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Återställer listan för standardteckensnittskataloger som standard.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Ställer in användarlistan med teckensnittssökvägar

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Ange SANT om du behöver ersätta ej hittade teckensnitt med standardteckensnittet. Standardvärdet är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Alternativ för att ställa in lagringskonfiguration för Font Sources. Om sant används ThreadStatic och varje tråd har egna Font Sources. Om falskt används global statisk konfiguration för alla trådar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isTheadLocal |  | booleskt värde |
