---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Basisklasse von Optionen für den Export von Formularfeldern dar."
type: docs
weight: 1310
url: /de/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Stellt die Basisklasse von Optionen für den Export von Formularfeldern dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Liest oder setzt einen Wert, der angibt, ob der Passwortwert exportiert werden soll. Wert: {@code true}, wenn der Passwortwert exportiert werden soll; andernfalls {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Liefert einen Delegaten, der bestimmt, ob ein bestimmtes Feld exportiert werden soll. Wenn der Delegat {@code null} ist, werden alle Felder exportiert (Standardverhalten). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Liest oder setzt einen Wert, der angibt, ob der Passwortwert exportiert werden soll. Wert: {@code true}, wenn der Passwortwert exportiert werden soll; andernfalls {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Setzt einen Delegaten, der bestimmt, ob ein bestimmtes Feld exportiert werden soll. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Liest oder setzt einen Wert, der angibt, ob der Passwortwert exportiert werden soll. Wert: {@code true}, wenn der Passwortwert exportiert werden soll; andernfalls {@code false}.

**Returns:**
boolescher Wert

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Liefert einen Delegaten, der bestimmt, ob ein bestimmtes Feld exportiert werden soll. Wenn der Delegat {@code null} ist, werden alle Felder exportiert (Standardverhalten).

**Returns:**
ein Delegat, der bestimmt, ob ein bestimmtes Feld exportiert werden soll.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob der Passwortwert exportiert werden soll. Wert: {@code true}, wenn der Passwortwert exportiert werden soll; andernfalls {@code false}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Setzt einen Delegaten, der bestimmt, ob ein bestimmtes Feld exportiert werden soll.
