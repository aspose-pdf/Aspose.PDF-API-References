---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta il campo checkbox."
type: docs
weight: 580
url: /it/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Classe che rappresenta il campo checkbox.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CheckboxField](#CheckboxField--) | Crea un'istanza di CheckboxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | Crea un'istanza di CheckboxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Crea un'istanza di CheckboxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea un'istanza di CheckboxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa CheckboxField(Document doc) |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle può essere selezionata in qualsiasi momento. La nuova casella di controllo viene aggiunta in fondo al gruppo. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle può essere selezionata in qualsiasi momento. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle può essere selezionata in qualsiasi momento. |
| [deepClone](#deepClone--) | Clona la casella di controllo. |
| [getActiveState](#getActiveState--) | Ottiene lo stato di aspetto corrente dell'annotazione. |
| [getAllowedStates](#getAllowedStates--) | Restituisce l'elenco degli stati consentiti. |
| [getChecked](#getChecked--) | Ottiene lo stato della casella di controllo. |
| [getExportValue](#getExportValue--) | Ottiene o imposta il valore di esportazione del campo CheckBox. |
| [getNormalCaption](#getNormalCaption--) | Ottiene la didascalia normale del campo. |
| [getOnState](#getOnState--) | Restituisce il nome dello stato che è lo stato "Checked" della casella di controllo. Questo è "Yes" se presente o qualsiasi altro valore diverso da "Off" e "No"; |
| [getStyle](#getStyle--) | Ottiene lo stile della casella di controllo. |
| [getValue](#getValue--) | Ottiene il valore del campo casella di controllo. |
| [setActiveState](#setActiveState-java.lang.String-) | Imposta lo stato attuale dell'aspetto dell'annotazione. |
| [setChecked](#setChecked-boolean-) | Imposta lo stato della casella di controllo. |
| [setExportValue](#setExportValue-java.lang.String-) | Ottiene o imposta il valore di esportazione del campo CheckBox. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Imposta lo stile della casella di controllo. |
| [setValue](#setValue-java.lang.String-) | Imposta il valore del campo casella di controllo. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

Crea un'istanza di CheckboxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
Crea un'istanza di CheckboxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Crea un'istanza di CheckboxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea un'istanza di CheckboxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle può essere selezionata in qualsiasi momento. La nuova casella di controllo viene aggiunta in fondo al gruppo.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle può essere selezionata in qualsiasi momento.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle può essere selezionata in qualsiasi momento.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona la casella di controllo.

**Returns:**
L'oggetto clonato

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Ottiene lo stato di aspetto corrente dell'annotazione.

**Returns:**
valore String

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

Restituisce l'elenco degli stati consentiti.

**Returns:**
elenco di valori String

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Ottiene lo stato della casella di controllo.

**Returns:**
valore booleano

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

Ottiene o imposta il valore di esportazione del campo CheckBox.

**Returns:**
valore String

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Ottiene la didascalia normale del campo.

**Returns:**
valore String

### getOnState {#getOnState--}
```
public String getOnState()
```

Restituisce il nome dello stato che è lo stato "Checked" della casella di controllo. Questo è "Yes" se presente o qualsiasi altro valore diverso da "Off" e "No";

**Returns:**
valore String

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Ottiene lo stile della casella di controllo.

**Returns:**
stile della casella di controllo. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Ottiene il valore del campo casella di controllo.

**Returns:**
valore String

### setActiveState {#setActiveState-java.lang.String-}
Imposta lo stato attuale dell'aspetto dell'annotazione.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Imposta lo stato della casella di controllo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setExportValue {#setExportValue-java.lang.String-}
Ottiene o imposta il valore di esportazione del campo CheckBox.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Imposta lo stile della casella di controllo.

### setValue {#setValue-java.lang.String-}
Imposta il valore del campo casella di controllo.
