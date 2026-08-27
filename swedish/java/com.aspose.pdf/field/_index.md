---
title: "Fält"
linktitle: "Fält"
second_title: "Aspose.PDF för Java API-referens"
description: "Basklass för acro-formulärfält."
type: docs
weight: 1380
url: /sv/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Basklass för acro-formulärfält.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Skapar fält för användning i Generator. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Kopierar underfält för detta fält till en array med start från angivet index. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Kopierar underfält för detta fält till en array med start från angivet index. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Utför en specificerad JavaScript-åtgärd för fältet. |
| [flatten](#flatten--) | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [get_Item](#get_Item-int-) | Hämtar underfält som finns i detta fält enligt index. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar underfält som finns i detta fält enligt underfältets namn. |
| [getAlternateName](#getAlternateName--) | Hämtar alternativt namn för fältet (Ett alternativt fältnamn som ska användas i stället för det faktiska fältnamnet där fältet identifieras i användargränssnittet). Alternativt namn används som verktygstips för fältet i Adobe Acrobat. |
| [getAnnotationIndex](#getAnnotationIndex--) | Hämtar index för denna anotation på sidan. |
| [getMappingName](#getMappingName--) | Hämtar mappningsnamn för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet. |
| [getMaxFontSize](#getMaxFontSize--) | Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| [getMinFontSize](#getMinFontSize--) | Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| [getPageIndex](#getPageIndex--) | Hämtar sidindex för sidan som innehåller detta fält. |
| [getPartialName](#getPartialName--) | Hämtar delnamn för fältet. |
| [getRect](#getRect--) | Hämtar fältets rektangel. |
| [getSyncRoot](#getSyncRoot--) | Synkroniseringsobjekt. |
| [getTabOrder](#getTabOrder--) | Hämtar eller anger tabbordning för fältet. |
| [getValue](#getValue--) | Hämtar värdet för fältet. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | Om true så minskas teckenstorleken för att anpassa texten till den angivna rektangeln. |
| [isGroup](#isGroup--) | Hämtar booleskt värde som indikerar om detta fält är ett icke-terminalt fält, dvs. en grupp av fält. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Egenskap för Generator-stöd. Används när fältet läggs till i sidhuvud eller sidfot. Om true skapas detta fält en gång och dess utseende är synligt på alla dokumentets sidor. Om false skapas ett separat fält för varje dokumentsida. |
| [isSynchronized](#isSynchronized--) | Returnerar true om ordboken är synkroniserad. |
| [iterator](#iterator--) | Returnerar enumerator för innehållna fält. |
| [recalculate](#recalculate--) | Beräknar om alla beräknade fält i formuläret. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Ställer in alternativt namn för fältet (Ett alternativt fältnamn som ska användas i stället för det faktiska fältnamnet där fältet identifieras i användargränssnittet). Alternativt namn används som verktygstips för fältet i Adobe Acrobat. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Ställer in index för denna anotation på sidan. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | Om true så minskas teckenstorleken för att anpassa texten till den angivna rektangeln. |
| [setMappingName](#setMappingName-java.lang.String-) | Ställer in mappningsnamn för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet. |
| [setMaxFontSize](#setMaxFontSize-double-) | Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| [setMinFontSize](#setMinFontSize-double-) | Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| [setPartialName](#setPartialName-java.lang.String-) | Ställer in delnamn för fältet. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Ställ in position för fältet. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Ställer in fältrektangeln. |
| [setSharedField](#setSharedField-boolean-) | Egenskap för Generator-stöd. Används när fältet läggs till i sidhuvud eller sidfot. Om true skapas detta fält en gång och dess utseende är synligt på alla dokumentets sidor. Om false skapas ett separat fält för varje dokumentsida. |
| [setTabOrder](#setTabOrder-int-) | Hämtar eller anger tabbordning för fältet. |
| [setValue](#setValue-java.lang.String-) | Ställ in värde. |
| [size](#size--) | Hämtar antalet underfält i detta fält. (Till exempel antalet objekt i ett radioknappsfält). |
| [updateAppearances](#updateAppearances--) | Uppdatera utseendets värde. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Skapar fält för användning i Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Kopierar underfält för detta fält till en array med start från angivet index.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Kopierar underfält för detta fält till en array med start från angivet index.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Utför en specificerad JavaScript-åtgärd för fältet.

### flatten {#flatten--}
```
public void flatten()
```

Tar bort detta fält och placerar dess värde direkt på sidan.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Hämtar underfält som finns i detta fält enligt index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för det begärda underfältet. |

**Returns:**
Fältinstans.

### get_Item {#get_Item-java.lang.String-}
Hämtar underfält som finns i detta fält enligt underfältets namn.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Hämtar alternativt namn för fältet (Ett alternativt fältnamn som ska användas i stället för det faktiska fältnamnet där fältet identifieras i användargränssnittet). Alternativt namn används som verktygstips för fältet i Adobe Acrobat.

**Returns:**
String värde

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Hämtar index för denna anotation på sidan.

**Returns:**
int‑värde

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Hämtar mappningsnamn för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet.

**Returns:**
String värde

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek.

**Returns:**
double-värde

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek.

**Returns:**
double-värde

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Hämtar sidindex för sidan som innehåller detta fält.

**Returns:**
int‑värde

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Hämtar delnamn för fältet.

**Returns:**
String värde

### getRect {#getRect--}
```
public Rectangle getRect()
```

Hämtar fältets rektangel.

**Returns:**
fältrektangeln.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Synkroniseringsobjekt.

**Returns:**
objektvärde

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Hämtar eller anger tabbordning för fältet.

**Returns:**
int‑värde

### getValue {#getValue--}
```
public String getValue()
```

Hämtar värdet för fältet.

**Returns:**
String värde

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

Om true så minskas teckenstorleken för att anpassa texten till den angivna rektangeln.

**Returns:**
booleskt värde

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Hämtar booleskt värde som indikerar om detta fält är ett icke-terminalt fält, dvs. en grupp av fält.

**Returns:**
booleskt värde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Egenskap för Generator-stöd. Används när fältet läggs till i sidhuvud eller sidfot. Om true skapas detta fält en gång och dess utseende är synligt på alla dokumentets sidor. Om false skapas ett separat fält för varje dokumentsida.

**Returns:**
booleskt värde

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returnerar true om ordboken är synkroniserad.

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Returnerar enumerator för innehållna fält.

**Returns:**
Enumerator‑objekt.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Beräknar om alla beräknade fält i formuläret.

**Returns:**
sant om fältvärdet ändrades under omberäkning.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Ställer in alternativt namn för fältet (Ett alternativt fältnamn som ska användas i stället för det faktiska fältnamnet där fältet identifieras i användargränssnittet). Alternativt namn används som verktygstips för fältet i Adobe Acrobat.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Ställer in index för denna anotation på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

Om true så minskas teckenstorleken för att anpassa texten till den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMappingName {#setMappingName-java.lang.String-}
Ställer in mappningsnamn för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setPartialName {#setPartialName-java.lang.String-}
Ställer in delnamn för fältet.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Ställ in position för fältet.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Ställer in fältrektangeln.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Egenskap för Generator-stöd. Används när fältet läggs till i sidhuvud eller sidfot. Om true skapas detta fält en gång och dess utseende är synligt på alla dokumentets sidor. Om false skapas ett separat fält för varje dokumentsida.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Hämtar eller anger tabbordning för fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setValue {#setValue-java.lang.String-}
Ställ in värde.

### size {#size--}
```
public int size()
```

Hämtar antalet underfält i detta fält. (Till exempel antalet objekt i ett radioknappsfält).

**Returns:**
int‑värde

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Uppdatera utseendets värde.
