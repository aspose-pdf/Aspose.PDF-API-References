---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar dokumentets sparalternativsklass i markdown-format."
type: docs
weight: 60
url: /sv/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Representerar dokumentets sparalternativsklass i markdown-format.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Skapar ett instansalternativ för att spara ett dokument i markdown‑format. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Hämta eller ange ett rektangelområde för att extrahera innehåll till markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | Hämtar eller anger stil för betoning för genererat dokument. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Hämtar och anger en egenskap som indikerar om vektorgrafik ska extraheras. |
| [getHeadingLevels](#getHeadingLevels--) | Definierar förväntade rubriknivåer att använda i FontSize‑igenkänningsstrategi för rubriker. Om detta egenskapsvärde är satt, kommer rubrikigenkänningsstrategin {@link HeadingRecognitionStrategy#Heuristic} att väljas när {@link HeadingRecognitionStrategy#Auto}‑strategier är satta, även om dokumentet innehåller bokmärken. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Hämtar eller anger rubrikigenkänningsstrategin. |
| [getHeadingStyle](#getHeadingStyle--) | Hämtar eller anger rubrikstilen för genererat dokument. |
| [getLineBreakStyle](#getLineBreakStyle--) | Hämtar eller anger radbrytningstilen för genererat dokument. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Om värdet inte anges kommer bilderna att skrivas till samma katalog som markdown‑filen själv. Detta är inte en sökväg, det är bara ett namn! Denna katalog skapas automatiskt i katalogen med den sparade markdown‑filen. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Denna katalog skapas automatiskt i katalogen med den sparade markdown‑filen. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Hämtar och anger tillåtelse att konvertera nedsänkt och upphöjt. Detta värde är sant som standard. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Hämtar och anger tillåtelse att använda en img‑tagg för att infoga bilder till vänster och höger om texten. I så fall kommer texten i markdown‑visaren att flöda runt bilden. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Hämta eller ange ett rektangelområde för att extrahera innehåll till markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Hämtar eller anger stil för betoning för genererat dokument. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Hämtar och anger en egenskap som indikerar om vektorgrafik ska extraheras. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Definierar förväntade rubriknivåer att använda i FontSize‑igenkänningsstrategi för rubriker. Om detta egenskapsvärde är satt, kommer rubrikigenkänningsstrategin {@link HeadingRecognitionStrategy#Heuristic} att väljas när {@link HeadingRecognitionStrategy#Auto}‑strategier är satta, även om dokumentet innehåller bokmärken. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Hämtar eller anger rubrikigenkänningsstrategin. |
| [setHeadingStyle](#setHeadingStyle-int-) | Hämtar eller anger rubrikstilen för genererat dokument. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Hämtar eller anger radbrytningstilen för genererat dokument. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Om värdet inte anges kommer bilderna att skrivas till samma katalog som markdown‑filen själv. Detta är inte en sökväg, det är bara ett namn! Denna katalog skapas automatiskt i katalogen med den sparade markdown‑filen. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Denna katalog skapas automatiskt i katalogen med den sparade markdown‑filen. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Hämtar och anger tillåtelse att konvertera nedsänkt och upphöjt. Detta värde är sant som standard. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Hämtar och anger tillåtelse att använda en img‑tagg för att infoga bilder till vänster och höger om texten. I så fall kommer texten i markdown‑visaren att flöda runt bilden. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Skapar ett instansalternativ för att spara ett dokument i markdown‑format.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Hämta eller ange ett rektangelområde för att extrahera innehåll till markdown.

**Returns:**
Rektangelinstans

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Hämtar eller anger stil för betoning för genererat dokument.

**Returns:**
EmphasisStyle‑element

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Hämtar och anger en egenskap som indikerar om vektorgrafik ska extraheras.

**Returns:**
booleskt värde

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Definierar förväntade rubriknivåer att använda i FontSize‑igenkänningsstrategi för rubriker. Om detta egenskapsvärde är satt, kommer rubrikigenkänningsstrategin {@link HeadingRecognitionStrategy#Heuristic} att väljas när {@link HeadingRecognitionStrategy#Auto}‑strategier är satta, även om dokumentet innehåller bokmärken.

**Returns:**
HeadingLevels‑instans

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Hämtar eller anger rubrikigenkänningsstrategin.

**Returns:**
HeadingRecognitionStrategy‑element

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Hämtar eller anger rubrikstilen för genererat dokument.

**Returns:**
HeadingStyle element

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Hämtar eller anger radbrytningstilen för genererat dokument.

**Returns:**
LineBreakStyle element

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Om värdet inte anges kommer bilderna att skrivas till samma katalog som markdown‑filen själv. Detta är inte en sökväg, det är bara ett namn! Denna katalog skapas automatiskt i katalogen med den sparade markdown‑filen.

**Returns:**
String värde

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Denna katalog skapas automatiskt i katalogen med den sparade markdown‑filen.

**Returns:**
String värde

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Hämtar och anger tillåtelse att konvertera nedsänkt och upphöjt. Detta värde är sant som standard.

**Returns:**
booleskt värde

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Hämtar och anger tillåtelse att använda en img‑tagg för att infoga bilder till vänster och höger om texten. I så fall kommer texten i markdown‑visaren att flöda runt bilden.

**Returns:**
booleskt värde

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Hämta eller ange ett rektangelområde för att extrahera innehåll till markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Hämtar eller anger stil för betoning för genererat dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | EmphasisStyle‑element |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Hämtar och anger en egenskap som indikerar om vektorgrafik ska extraheras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Definierar förväntade rubriknivåer att använda i FontSize‑igenkänningsstrategi för rubriker. Om detta egenskapsvärde är satt, kommer rubrikigenkänningsstrategin {@link HeadingRecognitionStrategy#Heuristic} att väljas när {@link HeadingRecognitionStrategy#Auto}‑strategier är satta, även om dokumentet innehåller bokmärken.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Hämtar eller anger rubrikigenkänningsstrategin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | HeadingRecognitionStrategy‑element |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Hämtar eller anger rubrikstilen för genererat dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | HeadingStyle element |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Hämtar eller anger radbrytningstilen för genererat dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | LineBreakStyle element |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Om värdet inte anges kommer bilderna att skrivas till samma katalog som markdown‑filen själv. Detta är inte en sökväg, det är bara ett namn! Denna katalog skapas automatiskt i katalogen med den sparade markdown‑filen.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Denna katalog skapas automatiskt i katalogen med den sparade markdown‑filen.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Hämtar och anger tillåtelse att konvertera nedsänkt och upphöjt. Detta värde är sant som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Hämtar och anger tillåtelse att använda en img‑tagg för att infoga bilder till vänster och höger om texten. I så fall kommer texten i markdown‑visaren att flöda runt bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
