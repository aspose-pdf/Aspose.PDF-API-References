---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att generera HTML-representation av textskillnader. Borttagna radbrytningar indikeras med - stycketecken."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Representerar en klass för att generera HTML-representation av textskillnader. Borttagna radbrytningar indikeras med - stycketecken.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Skapar en instans av {@link HtmlDiffOutputGenerator} klass. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Skapar en instans av {@link HtmlDiffOutputGenerator} klass. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [generateOutput1](#generateOutput1-java.util.List-) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Intern metod |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Hämtar och anger CSS-stilssträngen för Delete-operationen. Exempel: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Hämtar och anger CSS-stilssträngen för Equal-operationen. Exempel: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Hämtar och anger CSS-stilssträngen för Insert-operationen. Exempel: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Hämta eller ange text-decoration: line-through-stilen för delete-operationen. Standardvärdet är {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Hämtar och anger CSS-stilssträngen för Delete-operationen. Exempel: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Hämtar och anger CSS-stilssträngen för Equal-operationen. Exempel: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Hämtar och anger CSS-stilssträngen för Insert-operationen. Exempel: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Hämta eller ange text-decoration: line-through-stilen för delete-operationen. Standardvärdet är {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Skapar en instans av {@link HtmlDiffOutputGenerator} klass.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Skapar en instans av {@link HtmlDiffOutputGenerator} klass.

### generateOutput {#generateOutput-java.util.List-}
Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil.

### generateOutput1 {#generateOutput1-java.util.List-}
Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Intern metod

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Hämtar och anger CSS-stilssträngen för Delete-operationen. Exempel: color: #003300; background-color: #ccff66;

**Returns:**
String värde

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Hämtar och anger CSS-stilssträngen för Equal-operationen. Exempel: color: #003300; background-color: #ccff66;

**Returns:**
String värde

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Hämtar och anger CSS-stilssträngen för Insert-operationen. Exempel: color: #003300; background-color: #ccff66;

**Returns:**
String värde

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Hämta eller ange text-decoration: line-through-stilen för delete-operationen. Standardvärdet är {@code False}.

**Returns:**
booleskt värde

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Hämtar och anger CSS-stilssträngen för Delete-operationen. Exempel: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Hämtar och anger CSS-stilssträngen för Equal-operationen. Exempel: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Hämtar och anger CSS-stilssträngen för Insert-operationen. Exempel: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Hämta eller ange text-decoration: line-through-stilen för delete-operationen. Standardvärdet är {@code False}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
