---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Esegue la ricerca dei font. Cerca nei font installati sul sistema e nei font PDF standard. Fornisce anche la funzionalità per aprire font personalizzati. </p> <hr> <pre> L'esempio dimostra."
type: docs
weight: 1690
url: /it/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Esegue la ricerca dei font. Cerca nei font installati sul sistema e nei font PDF standard. Fornisce anche la funzionalità per aprire font personalizzati. </p> <hr> <pre> L'esempio dimostra come trovare un font e sostituire il font del testo della prima pagina. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Aggiungi un percorso in più ai font. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Aggiungi un font di sistema con il font specificato. </p> <hr> <pre> L'esempio dimostra come aggiungere un font di sistema. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Cerca e restituisce il font con il nome specificato. </p> <hr> <pre> L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina. // Find font Font font = FontRepository.findFont(\"Arial\"); // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Cerca e restituisce il font con il nome specificato, ignorando o rispettando la distinzione tra maiuscole e minuscole. </p> <hr> <pre> L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Cerca e restituisce il font con il nome e lo stile specificati. </p> <hr> <pre> L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Cerca e restituisce il font con il nome e lo stile specificati, ignorando o rispettando la distinzione tra maiuscole e minuscole. </p> <hr> <pre> L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina. // Find font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Copia dell'elenco con le directory dei font effettive. |
| [getSources](#getSources--) | Ottiene la raccolta delle font source. |
| [getSubstitutions](#getSubstitutions--) | Ottiene la raccolta delle strategie di sostituzione dei font. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | I font non trovati verranno sostituiti con il font standard. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Restituisce lo stato della configurazione dell'archiviazione delle Font Sources. <br> Se true, viene utilizzato ThreadStatic e ogni thread ha le proprie Font Sources. <br> Se false, viene utilizzata la configurazione statica globale per tutti i thread. </p> <hr> Il valore predefinito è True. |
| [loadFonts](#loadFonts--) | Carica i font installati nel sistema e i font PDF standard. Questo metodo è stato progettato per velocizzare il processo di caricamento dei font. Per impostazione predefinita i font vengono caricati alla prima richiesta di qualsiasi font. L'uso di questo metodo carica i font di sistema e i font PDF standard immediatamente prima che venga aperto qualsiasi documento PDF. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Apre il font con lo stream del font specificato. </p> <hr> <pre> L'esempio dimostra come aprire il font e sostituire il font del testo della prima pagina. // Open font InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Apre il font con il percorso del file font specificato. </p> <hr> <pre> L'esempio dimostra come aprire il font e sostituire il font del testo della prima pagina. // Open font Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Apre il font con il percorso del file font specificato e il percorso del file metriche. </p> <hr> <pre> L'esempio dimostra come aprire un font Type1 con metriche e sostituire il font del testo della prima pagina. // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | Ricarica tutti i font specificati dalla proprietà {@code Sources}({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Ripristina l'elenco delle directory dei font standard per impostazione predefinita. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Imposta l'elenco utente con i percorsi dei font |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Imposta TRUE se è necessario sostituire i font non trovati con il font predefinito. Il valore predefinito è false. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Opzione per impostare la configurazione di archiviazione delle Font Sources. Se true, viene utilizzato ThreadStatic e ogni thread ha le proprie Font Sources. Se false, viene utilizzata la configurazione statica globale per tutti i thread. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Aggiungi un percorso in più ai font.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Aggiunge un font di sistema con il font specificato. </p> <hr> <pre> L'esempio dimostra come aggiungere un font di sistema. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Cerca e restituisce il font con il nome del font specificato. </p> <hr> <pre> L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Cerca e restituisce il font con il nome del font specificato, ignorando o rispettando la distinzione tra maiuscole e minuscole. </p> <hr> <pre> L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina. // Trova il font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Apri il documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Salva il documento doc.save(\"D:\\Tests\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Cerca e restituisce il font con il nome del font e lo stile del font specificati. </p> <hr> <pre> L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina. // Trova il font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Apri il documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Salva il documento doc.save(\"D:\\Tests\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Cerca e restituisce il font con il nome del font e lo stile del font specificati, ignorando o rispettando la distinzione tra maiuscole e minuscole. </p> <hr> <pre> L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina. // Trova il font Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Apri il documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Salva il documento doc.save(\"D:\\Tests\\output.pdf\"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Copia dell'elenco con le directory dei font effettive.

**Returns:**
lista di String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Ottiene la raccolta delle font source.

**Returns:**
oggetto FontSourceCollection

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Ottiene la raccolta delle strategie di sostituzione dei font.

**Returns:**
oggetto FontSubstitutionCollection

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

I font non trovati verranno sostituiti con il font standard.

**Returns:**
valore booleano

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Restituisce lo stato della configurazione dell'archiviazione delle Font Sources. <br> Se true, viene utilizzato ThreadStatic e ogni thread ha le proprie Font Sources. <br> Se false, viene utilizzata la configurazione statica globale per tutti i thread. </p> <hr> Il valore predefinito è True.

**Returns:**
valore booleano

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Carica i font installati nel sistema e i font PDF standard. Questo metodo è stato progettato per velocizzare il processo di caricamento dei font. Per impostazione predefinita i font vengono caricati alla prima richiesta di qualsiasi font. L'uso di questo metodo carica i font di sistema e i font PDF standard immediatamente prima che venga aperto qualsiasi documento PDF.

### openFont {#openFont-java.io.InputStream-int-}
<p> Apre il font con lo stream del font specificato. </p> <hr> <pre> L'esempio dimostra come aprire il font e sostituire il font del testo della prima pagina. // Apri il font InputStream fontStream = new FileInputStream(\"C:\\WINDOWS\\Fonts\\arial.ttf\")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Apri il documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salva il documento doc.save(\"D:\\Tests\\output.pdf\"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Apre il font con il percorso del file del font specificato. </p> <hr> <pre> L'esempio dimostra come aprire il font e sostituire il font del testo della prima pagina. // Apri il font Font font = FontRepository.openFont(\"C:\\WINDOWS\\Fonts\\arial.ttf\"); // Apri il documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salva il documento doc.save(\"D:\\Tests\\output.pdf\"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Apre il font con il percorso del file del font specificato e il percorso del file delle metriche. </p> <hr> <pre> L'esempio dimostra come aprire un font Type1 con metriche e sostituire il font del testo della prima pagina. // Apri font Font font = FontRepository.openFont(\"courier.pfb\", \"courier.afm\"); // Apri documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Salva il documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

Ricarica tutti i font specificati dalla proprietà {@code Sources}({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Ripristina l'elenco delle directory dei font standard per impostazione predefinita.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Imposta l'elenco utente con i percorsi dei font

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Imposta TRUE se è necessario sostituire i font non trovati con il font predefinito. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Opzione per impostare la configurazione di archiviazione delle Font Sources. Se true, viene utilizzato ThreadStatic e ogni thread ha le proprie Font Sources. Se false, viene utilizzata la configurazione statica globale per tutti i thread.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isTheadLocal |  | valore booleano |
