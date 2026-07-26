---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Opzioni di salvataggio per l'esportazione in formato SVG"
type: docs
weight: 3950
url: /it/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Opzioni di salvataggio per l'esportazione in formato SVG

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, ad es. può essere usato per mostrare una barra di avanzamento o messaggi sul numero corrente di pagine elaborate, esempio di codice del gestore che mostra l'avanzamento sulla console è : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Ottiene o imposta la risoluzione dell'immagine (dpi). Il valore predefinito è 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | Se impostato su true, le immagini vengono separate da tutte le altre grafiche. |
| [getSlidesAsImages](#getSlidesAsImages--) | Se impostato su true, tutto il contenuto viene riconosciuto come immagini (una per pagina). |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Attiva/disattiva il riconoscimento delle colonne di testo. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, per esempio. |
| [setImageResolution](#setImageResolution-int-) | Ottiene o imposta la risoluzione dell'immagine (dpi). Il valore predefinito è 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Attiva/disattiva il riconoscimento delle colonne di testo. |
| [setSeparateImages](#setSeparateImages-boolean-) | Se impostato su true, le immagini vengono separate da tutte le altre grafiche. |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | Se impostato su true, tutto il contenuto viene riconosciuto come immagini (una per pagina). |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Costruttore

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, ad es. può essere usato per mostrare una barra di avanzamento o messaggi sul numero corrente di pagine elaborate, esempio di codice del gestore che mostra l'avanzamento sulla console è : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
istanza ConversionProgressEventHandler

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Ottiene o imposta la risoluzione dell'immagine (dpi). Il valore predefinito è 192 dpi.

**Returns:**
valore int

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

Se impostato su true, le immagini vengono separate da tutte le altre grafiche.

**Returns:**
valore booleano

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

Se impostato su true, tutto il contenuto viene riconosciuto come immagini (una per pagina).

**Returns:**
valore booleano

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Attiva/disattiva il riconoscimento delle colonne di testo.

**Returns:**
valore booleano

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, per esempio.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Ottiene o imposta la risoluzione dell'immagine (dpi). Il valore predefinito è 192 dpi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Attiva/disattiva il riconoscimento delle colonne di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

Se impostato su true, le immagini vengono separate da tutte le altre grafiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

Se impostato su true, tutto il contenuto viene riconosciuto come immagini (una per pagina).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
