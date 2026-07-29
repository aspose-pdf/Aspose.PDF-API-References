---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en alternativklass för att jämföra dokument med sida‑vid‑sida‑utdata."
type: docs
weight: 60
url: /sv/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Representerar en alternativklass för att jämföra dokument med sida‑vid‑sida‑utdata.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Skapar en instans av {@link SideBySideComparisonOptions} klass. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Hämta och ange egenskapen som bestämmer om ytterligare förändringsmarkörer visas. Om den är satt visas förändringsmarkeringar som inte finns på den aktuella sidan men finns på en annan sida. Om förändringen ligger mellan ord kan markeringen kanske inte placeras exakt i förhållande till blankstegstecknet. Standardvärdet är {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Hämta och ange jämförelseområdet. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) och {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) alternativ. |
| [getComparisonArea2](#getComparisonArea2--) | Hämta och ange jämförelseområdet. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) och {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) alternativ. |
| [getComparisonMode](#getComparisonMode--) | Hämtar och anger ett jämförelsesätt. Standardvärdet är {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Hämtar färgen som används för att markera raderat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för borttagningar i jämförelsesresultatet. |
| [getExcludeAreas1](#getExcludeAreas1--) | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) alternativet. |
| [getExcludeAreas2](#getExcludeAreas2--) | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) alternativet. |
| [getExcludeTables](#getExcludeTables--) | Hämta och ställ in alternativet som bestämmer om tabeller exkluderas från jämförelse. Detta alternativ kan inte sättas tillsammans med {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) och {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Standardvärdet är {@code false}. |
| [getInsertColor](#getInsertColor--) | Hämtar färgen som används för att markera infogat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för införande i jämförelsesresultatet. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Hämta och ange egenskapen som bestämmer om ytterligare förändringsmarkörer visas. Om den är satt visas förändringsmarkeringar som inte finns på den aktuella sidan men finns på en annan sida. Om förändringen ligger mellan ord kan markeringen kanske inte placeras exakt i förhållande till blankstegstecknet. Standardvärdet är {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Hämta och ange jämförelseområdet. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) och {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) alternativ. |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Hämta och ange jämförelseområdet. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) och {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) alternativ. |
| [setComparisonMode](#setComparisonMode-int-) | Hämtar och anger ett jämförelsesätt. Standardvärdet är {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Ställer in färgen som används för att markera raderat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för raderingar i jämförelsesresultatet. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) alternativet. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) alternativet. |
| [setExcludeTables](#setExcludeTables-boolean-) | Hämta och ställ in alternativet som bestämmer om tabeller exkluderas från jämförelse. Detta alternativ kan inte sättas tillsammans med {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) och {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Standardvärdet är {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Ställer in färgen som används för att markera infogat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för införande i jämförelsesresultatet. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Skapar en instans av {@link SideBySideComparisonOptions} klass.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Hämta och ange egenskapen som bestämmer om ytterligare förändringsmarkörer visas. Om den är satt visas förändringsmarkeringar som inte finns på den aktuella sidan men finns på en annan sida. Om förändringen ligger mellan ord kan markeringen kanske inte placeras exakt i förhållande till blankstegstecknet. Standardvärdet är {@code false}.

**Returns:**
booleskt värde

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Hämta och ange jämförelseområdet. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) och {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) alternativ.

**Returns:**
Rektangelinstans

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Hämta och ange jämförelseområdet. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) och {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) alternativ.

**Returns:**
Rektangelinstans

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Hämtar och anger ett jämförelsesätt. Standardvärdet är {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
ComparisonMode-element

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Hämtar färgen som används för att markera raderat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för borttagningar i jämförelsesresultatet.

**Returns:**
färgen som används för att markera raderat innehåll under en sida‑vid‑sida‑jämförelse.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) alternativet.

**Returns:**
array av Rectangle‑instanser

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) alternativet.

**Returns:**
array av Rectangle‑instanser

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Hämta och ställ in alternativet som bestämmer om tabeller exkluderas från jämförelse. Detta alternativ kan inte sättas tillsammans med {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) och {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Standardvärdet är {@code false}.

**Returns:**
booleskt värde

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Hämtar färgen som används för att markera infogat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för införande i jämförelsesresultatet.

**Returns:**
färgen som används för att markera infogat innehåll under en sida‑vid‑sida‑jämförelse.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Hämta och ange egenskapen som bestämmer om ytterligare förändringsmarkörer visas. Om den är satt visas förändringsmarkeringar som inte finns på den aktuella sidan men finns på en annan sida. Om förändringen ligger mellan ord kan markeringen kanske inte placeras exakt i förhållande till blankstegstecknet. Standardvärdet är {@code false}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Hämta och ange jämförelseområdet. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) och {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) alternativ.

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Hämta och ange jämförelseområdet. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) och {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) alternativ.

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Hämtar och anger ett jämförelsesätt. Standardvärdet är {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ComparisonMode-element |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Ställer in färgen som används för att markera raderat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för raderingar i jämförelsesresultatet.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) alternativet.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Detta alternativ kan inte ställas in tillsammans med {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) alternativet.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Hämta och ställ in alternativet som bestämmer om tabeller exkluderas från jämförelse. Detta alternativ kan inte sättas tillsammans med {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) och {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Standardvärdet är {@code false}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Ställer in färgen som används för att markera infogat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för införande i jämförelsesresultatet.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
