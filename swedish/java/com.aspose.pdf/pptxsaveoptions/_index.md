---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Spara alternativ för export till SVG-format"
type: docs
weight: 3950
url: /sv/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Spara alternativ för export till SVG-format

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Denna hanterare kan användas för att hantera konverteringsförloppshändelser, t.ex. kan den användas för att visa en förloppsindikator eller meddelanden om det aktuella antalet bearbetade sidor, exempel på hanterarens kod som visar förloppet i konsolen är : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Hämtar eller anger bildens upplösning (dpi). Standard är 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | Om den sätts till true separeras bilder från all annan grafik. |
| [getSlidesAsImages](#getSlidesAsImages--) | Om den sätts till true känns allt innehåll igen som bilder (en per sida). |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Växlar igenkänning av textkolumner. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex. |
| [setImageResolution](#setImageResolution-int-) | Hämtar eller anger bildens upplösning (dpi). Standard är 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Växlar igenkänning av textkolumner. |
| [setSeparateImages](#setSeparateImages-boolean-) | Om den sätts till true separeras bilder från all annan grafik. |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | Om den sätts till true känns allt innehåll igen som bilder (en per sida). |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Konstruktör

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Denna hanterare kan användas för att hantera konverteringsförloppshändelser, t.ex. kan den användas för att visa en förloppsindikator eller meddelanden om det aktuella antalet bearbetade sidor, exempel på hanterarens kod som visar förloppet i konsolen är : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler instans

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Hämtar eller anger bildens upplösning (dpi). Standard är 192 dpi.

**Returns:**
int‑värde

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

Om den sätts till true separeras bilder från all annan grafik.

**Returns:**
booleskt värde

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

Om den sätts till true känns allt innehåll igen som bilder (en per sida).

**Returns:**
booleskt värde

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Växlar igenkänning av textkolumner.

**Returns:**
booleskt värde

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Hämtar eller anger bildens upplösning (dpi). Standard är 192 dpi.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Växlar igenkänning av textkolumner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

Om den sätts till true separeras bilder från all annan grafik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

Om den sätts till true känns allt innehåll igen som bilder (en per sida).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
