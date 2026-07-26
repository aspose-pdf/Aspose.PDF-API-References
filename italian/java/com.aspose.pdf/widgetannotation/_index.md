---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'annotazione widget."
type: docs
weight: 5540
url: /it/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Classe che rappresenta l'annotazione widget.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Crea annotazione (usato per Generator) |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta visitatore. |
| [getAnnotationActions](#getAnnotationActions--) | Ottiene le azioni dell'annotazione. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getCheckedStateName](#getCheckedStateName--) | Restituisce il nome dello stato "checked" in base ai nomi degli stati esistenti. |
| [getDefaultAppearance](#getDefaultAppearance--) | Ottiene l'aspetto predefinito del campo. |
| [getExportable](#getExportable--) | Ottiene il flag esportabile del campo. |
| [getHighlighting](#getHighlighting--) | Modalità di evidenziazione dell'annotazione. |
| [getOnActivated](#getOnActivated--) | Ottieni un'azione da eseguire quando l'annotazione è attivata. |
| [getParent](#getParent--) | Ottiene il genitore dell'annotazione. |
| [getReadOnly](#getReadOnly--) | Ottiene lo stato di sola lettura del campo. |
| [getRequired](#getRequired--) | Ottiene lo stato obbligatorio del campo. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Imposta l'aspetto predefinito del campo. |
| [setExportable](#setExportable-boolean-) | Imposta lo stato di sola lettura del campo. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Modalità di evidenziazione dell'annotazione. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Imposta un'azione da eseguire quando l'annotazione è attivata. |
| [setReadOnly](#setReadOnly-boolean-) | Imposta lo stato di sola lettura del campo. |
| [setRequired](#setRequired-boolean-) | Imposta lo stato di sola lettura del campo. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Crea annotazione (usato per Generator)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta visitatore.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Ottiene le azioni dell'annotazione.

**Returns:**
Oggetto AnnotationActionCollection

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Restituisce il nome dello stato "checked" in base ai nomi degli stati esistenti.

**Returns:**
Il nome dello stato "checked" per questa annotazione.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Ottiene l'aspetto predefinito del campo.

**Returns:**
oggetto DefaultAppearance

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Ottiene il flag esportabile del campo.

**Returns:**
valore booleano

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Modalità di evidenziazione dell'annotazione.

**Returns:**
Valore HighlightingMode @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Ottieni un'azione da eseguire quando l'annotazione è attivata.

**Returns:**
oggetto PdfAction

### getParent {#getParent--}
```
public Field getParent()
```

Ottiene il genitore dell'annotazione.

**Returns:**
Oggetto Field

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Ottiene lo stato di sola lettura del campo.

**Returns:**
valore booleano

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Ottiene lo stato obbligatorio del campo.

**Returns:**
valore booleano

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Imposta l'aspetto predefinito del campo.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Imposta lo stato di sola lettura del campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Modalità di evidenziazione dell'annotazione.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Imposta un'azione da eseguire quando l'annotazione è attivata.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Imposta lo stato di sola lettura del campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Imposta lo stato di sola lettura del campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
