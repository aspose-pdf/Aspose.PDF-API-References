---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta il campo pulsante radio."
type: docs
weight: 4080
url: /it/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Classe che rappresenta il campo pulsante radio.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | Costruttore per RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | Costruttore per RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Imposta il campo del pulsante radio |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | Aggiunge un nuovo campo opzione al campo RadioButton |
| [addOption](#addOption-java.lang.String-) | Aggiungi opzione al pulsante radion. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Aggiungi all'opzione del pulsante radio un rettangolo specificato. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Ottiene o imposta il flag che consente al pulsante radio di non avere alcun valore selezionato. Se {@code }, esattamente un pulsante radio deve essere selezionato in ogni momento; selezionare il pulsante attualmente selezionato non ha effetto. Se {@code }, fare clic sul pulsante selezionato lo deseleziona, lasciando nessun pulsante selezionato. </p> <hr> Alcuni lettori PDF (incluso Adobe Acrobat) potrebbero ignorare lo stato del flag. |
| [getOptions](#getOptions--) | Ottiene la collezione di opzioni del pulsante radio. |
| [getPageIndex](#getPageIndex--) | Ottiene l'indice della pagina che contiene questo campo RadioButton. |
| [getSelected](#getSelected--) | Ottiene l'indice dell'elemento selezionato. La numerazione degli elementi inizia da 1. |
| [getStyle](#getStyle--) | Stile della casella del campo. |
| [getValue](#getValue--) | Ottiene il valore del campo. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Ottiene o imposta il flag che consente al pulsante radio di non avere alcun valore selezionato. Se {@code }, esattamente un pulsante radio deve essere selezionato in ogni momento; selezionare il pulsante attualmente selezionato non ha effetto. Se {@code }, fare clic sul pulsante selezionato lo deseleziona, lasciando nessun pulsante selezionato. </p> <hr> Alcuni lettori PDF (incluso Adobe Acrobat) potrebbero ignorare lo stato del flag. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Sposta tutti i sottoelementi del pulsante radio nelle posizioni specificate sulla pagina. |
| [setSelected](#setSelected-int-) | Imposta l'indice dell'elemento selezionato. La numerazione degli elementi inizia da 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Stile della casella del campo. |
| [setValue](#setValue-java.lang.String-) | Imposta il valore del campo. |
| [updateAppearances](#updateAppearances--) | Aggiorna il valore delle apparenze. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
Costruttore per RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
Costruttore per RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Imposta il campo del pulsante radio

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
Aggiunge un nuovo campo opzione al campo RadioButton

### addOption {#addOption-java.lang.String-}
Aggiungi opzione al pulsante radion.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Aggiungi all'opzione del pulsante radio un rettangolo specificato.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Ottiene o imposta il flag che consente al pulsante radio di non avere alcun valore selezionato. Se {@code }, esattamente un pulsante radio deve essere selezionato in ogni momento; selezionare il pulsante attualmente selezionato non ha effetto. Se {@code }, fare clic sul pulsante selezionato lo deseleziona, lasciando nessun pulsante selezionato. </p> <hr> Alcuni lettori PDF (incluso Adobe Acrobat) potrebbero ignorare lo stato del flag.

**Returns:**
valore booleano

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Ottiene la collezione di opzioni del pulsante radio.

**Returns:**
Oggetto OptionCollection

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Ottiene l'indice della pagina che contiene questo campo RadioButton.

**Returns:**
valore int

### getSelected {#getSelected--}
```
public int getSelected()
```

Ottiene l'indice dell'elemento selezionato. La numerazione degli elementi inizia da 1.

**Returns:**
valore int

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Stile della casella del campo.

**Returns:**
Valore BoxStyle @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Ottiene il valore del campo.

**Returns:**
valore String

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Ottiene o imposta il flag che consente al pulsante radio di non avere alcun valore selezionato. Se {@code }, esattamente un pulsante radio deve essere selezionato in ogni momento; selezionare il pulsante attualmente selezionato non ha effetto. Se {@code }, fare clic sul pulsante selezionato lo deseleziona, lasciando nessun pulsante selezionato. </p> <hr> Alcuni lettori PDF (incluso Adobe Acrobat) potrebbero ignorare lo stato del flag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Sposta tutti i sottoelementi del pulsante radio nelle posizioni specificate sulla pagina.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Imposta l'indice dell'elemento selezionato. La numerazione degli elementi inizia da 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Stile della casella del campo.

### setValue {#setValue-java.lang.String-}
Imposta il valore del campo.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Aggiorna il valore delle apparenze.
