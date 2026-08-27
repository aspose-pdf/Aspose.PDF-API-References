---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Options d'enregistrement pour l'exportation au format SVG"
type: docs
weight: 3950
url: /fr/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Options d'enregistrement pour l'exportation au format SVG

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par exemple il peut être utilisé pour afficher une barre de progression ou des messages concernant le nombre actuel de pages traitées, un exemple de code du gestionnaire qui affiche la progression dans la console est : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Obtient ou définit la résolution de l'image (dpi). La valeur par défaut est de 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | Si défini sur true, les images sont séparées de tous les autres graphiques |
| [getSlidesAsImages](#getSlidesAsImages--) | Si défini sur true, tout le contenu est reconnu comme des images (une par page) |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Active/désactive la reconnaissance des colonnes de texte |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex. |
| [setImageResolution](#setImageResolution-int-) | Obtient ou définit la résolution de l'image (dpi). La valeur par défaut est de 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Active/désactive la reconnaissance des colonnes de texte |
| [setSeparateImages](#setSeparateImages-boolean-) | Si défini sur true, les images sont séparées de tous les autres graphiques |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | Si défini sur true, tout le contenu est reconnu comme des images (une par page) |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Constructeur

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par exemple il peut être utilisé pour afficher une barre de progression ou des messages concernant le nombre actuel de pages traitées, un exemple de code du gestionnaire qui affiche la progression dans la console est : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
Instance ConversionProgressEventHandler

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Obtient ou définit la résolution de l'image (dpi). La valeur par défaut est de 192 dpi.

**Returns:**
valeur int

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

Si défini sur true, les images sont séparées de tous les autres graphiques

**Returns:**
valeur booléenne

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

Si défini sur true, tout le contenu est reconnu comme des images (une par page)

**Returns:**
valeur booléenne

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Active/désactive la reconnaissance des colonnes de texte

**Returns:**
valeur booléenne

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Obtient ou définit la résolution de l'image (dpi). La valeur par défaut est de 192 dpi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Active/désactive la reconnaissance des colonnes de texte

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

Si défini sur true, les images sont séparées de tous les autres graphiques

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

Si défini sur true, tout le contenu est reconnu comme des images (une par page)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
