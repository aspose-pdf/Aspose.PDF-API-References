---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en alternativklass för jämförelse av PDF‑dokument."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Representerar en alternativklass för jämförelse av PDF‑dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Skapar en {@link ComparisonOptions} klassinstans. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Hämtar och anger ordningen för redigeringsoperationer. |
| [getExcludeAreas1](#getExcludeAreas1--) | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet. |
| [getExcludeAreas2](#getExcludeAreas2--) | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet. |
| [getExtractionArea](#getExtractionArea--) | Hämta och ange det rektangulära området där sidornas text kommer att jämföras. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) och { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) alternativ. |
| [isExcludeTables](#isExcludeTables--) | Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet. Standardvärdet är {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Hämtar och anger ordningen för redigeringsoperationer. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet. |
| [setExcludeTables](#setExcludeTables-boolean-) | Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet. Standardvärdet är {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Hämta och ange det rektangulära området där sidornas text kommer att jämföras. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) och { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) alternativ. |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Skapar en {@link ComparisonOptions} klassinstans.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Hämtar och anger ordningen för redigeringsoperationer.

**Returns:**
EditOperationsOrder-element

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet.

**Returns:**
array av Rectangle‑instanser

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet.

**Returns:**
array av Rectangle‑instanser

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Hämta och ange det rektangulära området där sidornas text kommer att jämföras. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) och { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) alternativ.

**Returns:**
Rektangelinstans

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet. Standardvärdet är {@code false}.

**Returns:**
booleskt värde

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Hämtar och anger ordningen för redigeringsoperationer.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte ställas in tillsammans med {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) alternativet. Standardvärdet är {@code false}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Hämta och ange det rektangulära området där sidornas text kommer att jämföras. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) och { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) alternativ.
