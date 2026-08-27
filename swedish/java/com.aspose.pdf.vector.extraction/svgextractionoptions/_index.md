---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en alternativklass för att extrahera vektorgrafik från PDF‑dokumentets sida."
type: docs
weight: 30
url: /sv/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Representerar en alternativklass för att extrahera vektorgrafik från PDF‑dokumentets sida.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Skapar en instans av SvgExtractionOptions-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Hämtar och anger alternativet för att automatiskt gruppera subpaths till bilder. Detta alternativ utesluter {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) alternativet. |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Hämtar och anger alternativet för att extrahera varje subpath från ett PDF-dokument till separata SVG‑bilder. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Hämtar och anger den omgivande rektangeln som definierar extraktionsområdet för SVG‑extraktion. |
| [getGroupStrength](#getGroupStrength--) | Hämtar och anger ett alternativ Styrkan för gruppering av delvägar till bilder. Gör det möjligt att konfigurera graden av gruppering av delvägar. Värdeintervallet är från 0 till 1. Ett värde på 0 motsvarar att {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) alternativet är aktiverat. Ett värde på 1 skapar en enda bild för alla vektorvägar på sidan. Alternativet har effekt när {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) är falskt. Standardvärdet är {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Hämtar eller anger den minsta linjebredden som ska användas i den resulterande SVG:n. Om PDF-filen använder en tunnare linjebredd ersätts den med denna bredd. Standardvärdet är 0,5. Värdet uttrycks i transformerade enheter i användarutrymmet för den konverterade PDF-sidan. Som standard är 1 enhet i användarutrymmet 1/72 tum (0,35 mm), men detta kan åsidosättas av PDF-dokumentet. Transformationer kan påverka den faktiska minsta bredden i den genererade SVG:n. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Hämtar och anger ett alternativ för att strikt kontrollera om delvägar ligger inom den angivna rektangeln i {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Om den är falsk kommer delvägar som inte är helt inkluderade i {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) att extraheras. Standardvärdet är {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Hämtar och anger en flagga som bestämmer om XFrom som hittas på sidor ska packas upp eller inte. XFrom-element kan hamna i olika SVG-filer. Endast XForms som renderas av Do‑satser från sidans innehåll packas upp. Nästlade XForms packas inte upp. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Hämtar och anger alternativet för att packa upp endast den XForm som motsvarar det angivna predikatet. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Hämtar och anger alternativet för att automatiskt gruppera subpaths till bilder. Detta alternativ utesluter {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) alternativet. |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Hämtar och anger alternativet för att extrahera varje subpath från ett PDF-dokument till separata SVG‑bilder. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Hämtar och anger den omgivande rektangeln som definierar extraktionsområdet för SVG‑extraktion. |
| [setGroupStrength](#setGroupStrength-double-) | Hämtar och anger ett alternativ Styrkan för gruppering av delvägar till bilder. Gör det möjligt att konfigurera graden av gruppering av delvägar. Värdeintervallet är från 0 till 1. Ett värde på 0 motsvarar att {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) alternativet är aktiverat. Ett värde på 1 skapar en enda bild för alla vektorvägar på sidan. Alternativet har effekt när {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) är falskt. Standardvärdet är {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Hämtar eller anger den minsta linjebredden som ska användas i den resulterande SVG:n. Om PDF-filen använder en tunnare linjebredd ersätts den med denna bredd. Standardvärdet är 0,5. Värdet uttrycks i transformerade enheter i användarutrymmet för den konverterade PDF-sidan. Som standard är 1 enhet i användarutrymmet 1/72 tum (0,35 mm), men detta kan åsidosättas av PDF-dokumentet. Transformationer kan påverka den faktiska minsta bredden i den genererade SVG:n. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Hämtar och anger ett alternativ för att strikt kontrollera om delvägar ligger inom den angivna rektangeln i {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Om den är falsk kommer delvägar som inte är helt inkluderade i {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) att extraheras. Standardvärdet är {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Hämtar och anger en flagga som bestämmer om XFrom som hittas på sidor ska packas upp eller inte. XFrom-element kan hamna i olika SVG-filer. Endast XForms som renderas av Do‑satser från sidans innehåll packas upp. Nästlade XForms packas inte upp. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Hämtar och anger alternativet för att packa upp endast den XForm som motsvarar det angivna predikatet. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Skapar en instans av SvgExtractionOptions-klassen.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Hämtar och anger alternativet för att automatiskt gruppera subpaths till bilder. Detta alternativ utesluter {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) alternativet.

**Returns:**
booleskt värde

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Hämtar och anger alternativet för att extrahera varje subpath från ett PDF-dokument till separata SVG‑bilder.

**Returns:**
booleskt värde

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Hämtar och anger den omgivande rektangeln som definierar extraktionsområdet för SVG‑extraktion.

**Returns:**
Rektangelinstans

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Hämtar och anger ett alternativ Styrkan för gruppering av delvägar till bilder. Gör det möjligt att konfigurera graden av gruppering av delvägar. Värdeintervallet är från 0 till 1. Ett värde på 0 motsvarar att {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) alternativet är aktiverat. Ett värde på 1 skapar en enda bild för alla vektorvägar på sidan. Alternativet har effekt när {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) är falskt. Standardvärdet är {@code 0.8}.

**Returns:**
double-värde

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Hämtar eller anger den minsta linjebredden som ska användas i den resulterande SVG:n. Om PDF-filen använder en tunnare linjebredd ersätts den med denna bredd. Standardvärdet är 0,5. Värdet uttrycks i transformerade enheter i användarutrymmet för den konverterade PDF-sidan. Som standard är 1 enhet i användarutrymmet 1/72 tum (0,35 mm), men detta kan åsidosättas av PDF-dokumentet. Transformationer kan påverka den faktiska minsta bredden i den genererade SVG:n.

**Returns:**
double-värde

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Hämtar och anger ett alternativ för att strikt kontrollera om delvägar ligger inom den angivna rektangeln i {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Om den är falsk kommer delvägar som inte är helt inkluderade i {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) att extraheras. Standardvärdet är {@code True}.

**Returns:**
booleskt värde

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Hämtar och anger en flagga som bestämmer om XFrom som hittas på sidor ska packas upp eller inte. XFrom-element kan hamna i olika SVG-filer. Endast XForms som renderas av Do‑satser från sidans innehåll packas upp. Nästlade XForms packas inte upp.

**Returns:**
booleskt värde

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Hämtar och anger alternativet för att packa upp endast den XForm som motsvarar det angivna predikatet.

**Returns:**
intern Predicate‑instans av XFormPlacement‑instans

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Hämtar och anger alternativet för att automatiskt gruppera subpaths till bilder. Detta alternativ utesluter {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) alternativet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Hämtar och anger alternativet för att extrahera varje subpath från ett PDF-dokument till separata SVG‑bilder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Hämtar och anger den omgivande rektangeln som definierar extraktionsområdet för SVG‑extraktion.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Hämtar och anger ett alternativ Styrkan för gruppering av delvägar till bilder. Gör det möjligt att konfigurera graden av gruppering av delvägar. Värdeintervallet är från 0 till 1. Ett värde på 0 motsvarar att {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) alternativet är aktiverat. Ett värde på 1 skapar en enda bild för alla vektorvägar på sidan. Alternativet har effekt när {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) är falskt. Standardvärdet är {@code 0.8}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Hämtar eller anger den minsta linjebredden som ska användas i den resulterande SVG:n. Om PDF-filen använder en tunnare linjebredd ersätts den med denna bredd. Standardvärdet är 0,5. Värdet uttrycks i transformerade enheter i användarutrymmet för den konverterade PDF-sidan. Som standard är 1 enhet i användarutrymmet 1/72 tum (0,35 mm), men detta kan åsidosättas av PDF-dokumentet. Transformationer kan påverka den faktiska minsta bredden i den genererade SVG:n.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Hämtar och anger ett alternativ för att strikt kontrollera om delvägar ligger inom den angivna rektangeln i {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Om den är falsk kommer delvägar som inte är helt inkluderade i {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) att extraheras. Standardvärdet är {@code True}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Hämtar och anger en flagga som bestämmer om XFrom som hittas på sidor ska packas upp eller inte. XFrom-element kan hamna i olika SVG-filer. Endast XForms som renderas av Do‑satser från sidans innehåll packas upp. Nästlade XForms packas inte upp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Hämtar och anger alternativet för att packa upp endast den XForm som motsvarar det angivna predikatet.
