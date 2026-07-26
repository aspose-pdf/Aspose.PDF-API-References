---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Speicheroptionen für den Export in das SVG‑Format"
type: docs
weight: 3950
url: /de/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Speicheroptionen für den Export in das SVG‑Format

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Dieser Handler kann verwendet werden, um Fortschrittsereignisse der Konvertierung zu behandeln, z. B. um eine Fortschrittsanzeige oder Meldungen über die aktuelle Anzahl verarbeiteter Seiten anzuzeigen. Ein Beispiel für den Code des Handlers, das den Fortschritt in der Konsole anzeigt, ist : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Liest oder setzt die Bildauflösung (dpi). Standardwert ist 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | Wenn auf true gesetzt, werden Bilder von allen anderen Grafiken getrennt. |
| [getSlidesAsImages](#getSlidesAsImages--) | Wenn auf true gesetzt, wird der gesamte Inhalt als Bilder erkannt (ein Bild pro Seite). |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Schaltet die Erkennung von Textspalten um. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Dieser Handler kann verwendet werden, um Konvertierungs‑Fortschrittsereignisse zu behandeln, z. b. |
| [setImageResolution](#setImageResolution-int-) | Liest oder setzt die Bildauflösung (dpi). Standardwert ist 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Schaltet die Erkennung von Textspalten um. |
| [setSeparateImages](#setSeparateImages-boolean-) | Wenn auf true gesetzt, werden Bilder von allen anderen Grafiken getrennt. |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | Wenn auf true gesetzt, wird der gesamte Inhalt als Bilder erkannt (ein Bild pro Seite). |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Konstruktor

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Dieser Handler kann verwendet werden, um Fortschrittsereignisse der Konvertierung zu behandeln, z. B. um eine Fortschrittsanzeige oder Meldungen über die aktuelle Anzahl verarbeiteter Seiten anzuzeigen. Ein Beispiel für den Code des Handlers, das den Fortschritt in der Konsole anzeigt, ist : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler‑Instanz

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Liest oder setzt die Bildauflösung (dpi). Standardwert ist 192 dpi.

**Returns:**
int-Wert

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

Wenn auf true gesetzt, werden Bilder von allen anderen Grafiken getrennt.

**Returns:**
boolescher Wert

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

Wenn auf true gesetzt, wird der gesamte Inhalt als Bilder erkannt (ein Bild pro Seite).

**Returns:**
boolescher Wert

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Schaltet die Erkennung von Textspalten um.

**Returns:**
boolescher Wert

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Dieser Handler kann verwendet werden, um Konvertierungs‑Fortschrittsereignisse zu behandeln, z. b.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Liest oder setzt die Bildauflösung (dpi). Standardwert ist 192 dpi.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Schaltet die Erkennung von Textspalten um.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

Wenn auf true gesetzt, werden Bilder von allen anderen Grafiken getrennt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

Wenn auf true gesetzt, wird der gesamte Inhalt als Bilder erkannt (ein Bild pro Seite).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
