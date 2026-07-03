---
title: PptxSaveOptions
linktitle: PptxSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to SVG format
type: docs
weight: 3950
url: /java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Save options for export to SVG format

## Constructors

| Constructor | Description |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Gets or sets the image resolution (dpi). Default is 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | If set to true then images are separated from all other graphics |
| [getSlidesAsImages](#getSlidesAsImages--) | If set to true then all the content is recognized as images (one per page) |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Toggles text columns recognition |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | This handler can be used to handle conversion progress events f.e. |
| [setImageResolution](#setImageResolution-int-) | Gets or sets the image resolution (dpi). Default is 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Toggles text columns recognition |
| [setSeparateImages](#setSeparateImages-boolean-) | If set to true then images are separated from all other graphics |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | If set to true then all the content is recognized as images (one per page) |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Constructor

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler instance

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Gets or sets the image resolution (dpi). Default is 192 dpi.

**Returns:**
int value

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

If set to true then images are separated from all other graphics

**Returns:**
boolean value

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

If set to true then all the content is recognized as images (one per page)

**Returns:**
boolean value

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Toggles text columns recognition

**Returns:**
boolean value

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
This handler can be used to handle conversion progress events f.e.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Gets or sets the image resolution (dpi). Default is 192 dpi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Toggles text columns recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

If set to true then images are separated from all other graphics

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

If set to true then all the content is recognized as images (one per page)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
