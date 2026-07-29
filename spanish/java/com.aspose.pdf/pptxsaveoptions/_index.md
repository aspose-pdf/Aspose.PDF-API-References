---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Opciones de guardado para exportar al formato SVG"
type: docs
weight: 3950
url: /es/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Opciones de guardado para exportar al formato SVG

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Este controlador puede usarse para manejar eventos de progreso de conversión, p. ej., puede usarse para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas, ejemplo del código del controlador que muestra el progreso en la consola es : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"input.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save(\"output.html\", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format(\"{0} - Conversion progress : {1}% .\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format(\"{0} - Source page {1} of {2} analyzed.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format(\"{0} - Result page's {1} of {2} layout created.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format(\"{0} - Result page {1} of {2} exported.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Obtiene o establece la resolución de la imagen (dpi). El valor predeterminado es 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | Si se establece en true, las imágenes se separan de todos los demás gráficos |
| [getSlidesAsImages](#getSlidesAsImages--) | Si se establece en true, todo el contenido se reconoce como imágenes (una por página) |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Alterna el reconocimiento de columnas de texto |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Este manejador puede usarse para manejar eventos de progreso de conversión, p. ej. |
| [setImageResolution](#setImageResolution-int-) | Obtiene o establece la resolución de la imagen (dpi). El valor predeterminado es 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Alterna el reconocimiento de columnas de texto |
| [setSeparateImages](#setSeparateImages-boolean-) | Si se establece en true, las imágenes se separan de todos los demás gráficos |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | Si se establece en true, todo el contenido se reconoce como imágenes (una por página) |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Constructor

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Este controlador puede usarse para manejar eventos de progreso de conversión, p. ej., puede usarse para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas, ejemplo del código del controlador que muestra el progreso en la consola es : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"input.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save(\"output.html\", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format(\"{0} - Conversion progress : {1}% .\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format(\"{0} - Source page {1} of {2} analyzed.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format(\"{0} - Result page's {1} of {2} layout created.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format(\"{0} - Result page {1} of {2} exported.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
Instancia ConversionProgressEventHandler

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Obtiene o establece la resolución de la imagen (dpi). El valor predeterminado es 192 dpi.

**Returns:**
valor int

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

Si se establece en true, las imágenes se separan de todos los demás gráficos

**Returns:**
valor booleano

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

Si se establece en true, todo el contenido se reconoce como imágenes (una por página)

**Returns:**
valor booleano

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Alterna el reconocimiento de columnas de texto

**Returns:**
valor booleano

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Este manejador puede usarse para manejar eventos de progreso de conversión, p. ej.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Obtiene o establece la resolución de la imagen (dpi). El valor predeterminado es 192 dpi.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Alterna el reconocimiento de columnas de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

Si se establece en true, las imágenes se separan de todos los demás gráficos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

Si se establece en true, todo el contenido se reconoce como imágenes (una por página)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
