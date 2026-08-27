---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen som representerar kryssrutfält."
type: docs
weight: 580
url: /sv/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Klassen som representerar kryssrutfält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CheckboxField](#CheckboxField--) | Skapa en instans av CheckboxField. @deprecated För full funktionalitet av fältet krävs en bindning till dokumentet – använd CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | Skapa en instans av CheckboxField. @deprecated För full funktionalitet av fältet krävs en bindning till dokumentet – använd CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Skapa en instans av CheckboxField. @deprecated För full funktionalitet av fältet krävs en bindning till dokumentet – använd CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Skapa en instans av CheckboxField. @deprecated För full funktionalitet av fältet krävs en bindning till dokumentet – använd CheckboxField(Document doc) |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Lägger till en ny kryssruta i en kryssrutesgrupp, där högst en av kryssrutorna kan vara markerad åt gången. Den nya kryssrutan läggs till längst ner i gruppen. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Lägger till en ny kryssruta i en kryssrutesgrupp, där högst en av kryssrutorna kan vara markerad åt gången. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Lägger till en ny kryssruta i en kryssrutesgrupp, där högst en av kryssrutorna kan vara markerad åt gången. |
| [deepClone](#deepClone--) | Klona kryssrutan. |
| [getActiveState](#getActiveState--) | Hämtar aktuellt annoteringsutseende. |
| [getAllowedStates](#getAllowedStates--) | Returnerar en lista med tillåtna tillstånd. |
| [getChecked](#getChecked--) | Hämtar tillståndet för kryssrutan. |
| [getExportValue](#getExportValue--) | Hämtar eller anger exportvärdet för CheckBox-fältet. |
| [getNormalCaption](#getNormalCaption--) | Hämtar normal rubrik för fältet. |
| [getOnState](#getOnState--) | Returnerar namnet på tillståndet som är "Checked"-tillståndet för kryssrutan. Detta är "Yes" om det finns eller något annat värde än "Off" och "No"; |
| [getStyle](#getStyle--) | Hämtar stil för kryssruta. |
| [getValue](#getValue--) | Hämtar värdet för kryssrutan. |
| [setActiveState](#setActiveState-java.lang.String-) | Ställer in aktuellt annoteringsutseende. |
| [setChecked](#setChecked-boolean-) | Anger tillståndet för kryssrutan. |
| [setExportValue](#setExportValue-java.lang.String-) | Hämtar eller anger exportvärdet för CheckBox-fältet. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Ställer in stil för kryssruta. |
| [setValue](#setValue-java.lang.String-) | Anger värdet för kryssrutan. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

Skapa en instans av CheckboxField. @deprecated För full funktionalitet av fältet krävs en bindning till dokumentet – använd CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
Skapa en instans av CheckboxField. @deprecated För full funktionalitet av fältet krävs en bindning till dokumentet – använd CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Skapa en instans av CheckboxField. @deprecated För full funktionalitet av fältet krävs en bindning till dokumentet – använd CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Skapa en instans av CheckboxField. @deprecated För full funktionalitet av fältet krävs en bindning till dokumentet – använd CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
Lägger till en ny kryssruta i en kryssrutesgrupp, där högst en av kryssrutorna kan vara markerad åt gången. Den nya kryssrutan läggs till längst ner i gruppen.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Lägger till en ny kryssruta i en kryssrutesgrupp, där högst en av kryssrutorna kan vara markerad åt gången.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Lägger till en ny kryssruta i en kryssrutesgrupp, där högst en av kryssrutorna kan vara markerad åt gången.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klona kryssrutan.

**Returns:**
Det klonade objektet

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Hämtar aktuellt annoteringsutseende.

**Returns:**
String värde

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

Returnerar en lista med tillåtna tillstånd.

**Returns:**
lista med String-värde

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Hämtar tillståndet för kryssrutan.

**Returns:**
booleskt värde

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

Hämtar eller anger exportvärdet för CheckBox-fältet.

**Returns:**
String värde

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Hämtar normal rubrik för fältet.

**Returns:**
String värde

### getOnState {#getOnState--}
```
public String getOnState()
```

Returnerar namnet på tillståndet som är "Checked"-tillståndet för kryssrutan. Detta är "Yes" om det finns eller något annat värde än "Off" och "No";

**Returns:**
String värde

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Hämtar stil för kryssruta.

**Returns:**
stil för kryssrutan. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Hämtar värdet för kryssrutan.

**Returns:**
String värde

### setActiveState {#setActiveState-java.lang.String-}
Ställer in aktuellt annoteringsutseende.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Anger tillståndet för kryssrutan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setExportValue {#setExportValue-java.lang.String-}
Hämtar eller anger exportvärdet för CheckBox-fältet.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Ställer in stil för kryssruta.

### setValue {#setValue-java.lang.String-}
Anger värdet för kryssrutan.
