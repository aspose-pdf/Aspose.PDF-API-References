---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar basklass för valfält."
type: docs
weight: 590
url: /sv/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Representerar basklass för valfält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Skapar valfält (för Generator) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Konstruktor för ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor för ChoiceField. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Lägger till ett nytt alternativ med angivet namn. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Lägger till ett nytt alternativ med angivet exportvärde och namn. |
| [deleteOption](#deleteOption-java.lang.String-) | Tar bort alternativet efter dess namn. |
| [getCommitImmediately](#getCommitImmediately--) | Hämtar flaggan för bekräftelse vid urvalsförändring. |
| [getMultiSelect](#getMultiSelect--) | Hämtar flaggan för multival. |
| [getOptions](#getOptions--) | Hämtar samling av valalternativ. |
| [getSelected](#getSelected--) | Hämtar index för valt alternativ. Denna egenskap tillåter att ändra urvalet. |
| [getSelectedItems](#getSelectedItems--) | Ställer in en array av valda objekt. För multivallista innehåller arrayen mer än ett objekt. För enkelt urvallista innehåller den ett enda objekt. |
| [getValue](#getValue--) | Hämtar värdet för fältet. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Ställer in flaggan för bekräftelse vid urvalsförändring. |
| [setMultiSelect](#setMultiSelect-boolean-) | Ställer in flaggan för multival. |
| [setOptions](#setOptions-java.util.List-) | Ersätter de tillgängliga alternativen med de vars namn anges i options-parameter. |
| [setSelected](#setSelected-int-) | Ställer in index för valt alternativ. Denna egenskap tillåter att ändra urvalet. |
| [setSelectedItems](#setSelectedItems-int:A-) | Ställer in en array av valda objekt. För multivallista innehåller arrayen mer än ett objekt. För enkelt urvallista innehåller den ett enda objekt. |
| [setValue](#setValue-java.lang.String-) | Anger värdet för fältet. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Skapar valfält (för Generator)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Konstruktor för ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor för ChoiceField.

### addOption {#addOption-java.lang.String-}
Lägger till ett nytt alternativ med angivet namn.

### addOption {#addOption-java.lang.String-java.lang.String-}
Lägger till ett nytt alternativ med angivet exportvärde och namn.

### deleteOption {#deleteOption-java.lang.String-}
Tar bort alternativet efter dess namn.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Hämtar flaggan för bekräftelse vid urvalsförändring.

**Returns:**
booleskt värde

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Hämtar flaggan för multival.

**Returns:**
booleskt värde

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Hämtar samling av valalternativ.

**Returns:**
OptionCollection-objekt

### getSelected {#getSelected--}
```
public int getSelected()
```

Hämtar index för valt alternativ. Denna egenskap tillåter att ändra urvalet.

**Returns:**
int‑värde

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Ställer in en array av valda objekt. För multivallista innehåller arrayen mer än ett objekt. För enkelt urvallista innehåller den ett enda objekt.

**Returns:**
array med int‑värden

### getValue {#getValue--}
```
public String getValue()
```

Hämtar värdet för fältet.

**Returns:**
String värde

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Ställer in flaggan för bekräftelse vid urvalsförändring.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Ställer in flaggan för multival.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOptions {#setOptions-java.util.List-}
Ersätter de tillgängliga alternativen med de vars namn anges i options-parameter.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Ställer in index för valt alternativ. Denna egenskap tillåter att ändra urvalet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Ställer in en array av valda objekt. För multivallista innehåller arrayen mer än ett objekt. För enkelt urvallista innehåller den ett enda objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | array med int‑värden |

### setValue {#setValue-java.lang.String-}
Anger värdet för fältet.
