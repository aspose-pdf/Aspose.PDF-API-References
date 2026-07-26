---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe base per i campi di scelta."
type: docs
weight: 590
url: /it/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Rappresenta la classe base per i campi di scelta.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Crea un campo di scelta (per Generator) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Costruttore per ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Costruttore per ChoiceField. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Aggiunge una nuova opzione con il nome specificato. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Aggiunge una nuova opzione con il valore di esportazione e il nome specificati. |
| [deleteOption](#deleteOption-java.lang.String-) | Elimina l'opzione per nome. |
| [getCommitImmediately](#getCommitImmediately--) | Ottiene il flag di commit al cambiamento della selezione. |
| [getMultiSelect](#getMultiSelect--) | Ottiene il flag di selezione multipla. |
| [getOptions](#getOptions--) | Ottiene la raccolta delle opzioni di scelta. |
| [getSelected](#getSelected--) | Ottiene l'indice dell'opzione selezionata. Questa proprietà consente di modificare la selezione. |
| [getSelectedItems](#getSelectedItems--) | Imposta l'array degli elementi selezionati. Per un elenco a selezione multipla l'array contiene più di un elemento. Per un elenco a selezione singola contiene un solo elemento. |
| [getValue](#getValue--) | Restituisce il valore del campo. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Imposta il flag di commit al cambiamento della selezione. |
| [setMultiSelect](#setMultiSelect-boolean-) | Imposta il flag di selezione multipla. |
| [setOptions](#setOptions-java.util.List-) | Sostituisce le opzioni disponibili con quelle i cui nomi sono forniti nel parametro options. |
| [setSelected](#setSelected-int-) | Imposta l'indice dell'opzione selezionata. Questa proprietà consente di modificare la selezione. |
| [setSelectedItems](#setSelectedItems-int:A-) | Imposta l'array degli elementi selezionati. Per un elenco a selezione multipla l'array contiene più di un elemento. Per un elenco a selezione singola contiene un solo elemento. |
| [setValue](#setValue-java.lang.String-) | Imposta il valore del campo. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Crea un campo di scelta (per Generator)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Costruttore per ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Costruttore per ChoiceField.

### addOption {#addOption-java.lang.String-}
Aggiunge una nuova opzione con il nome specificato.

### addOption {#addOption-java.lang.String-java.lang.String-}
Aggiunge una nuova opzione con il valore di esportazione e il nome specificati.

### deleteOption {#deleteOption-java.lang.String-}
Elimina l'opzione per nome.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Ottiene il flag di commit al cambiamento della selezione.

**Returns:**
valore booleano

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Ottiene il flag di selezione multipla.

**Returns:**
valore booleano

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Ottiene la raccolta delle opzioni di scelta.

**Returns:**
Oggetto OptionCollection

### getSelected {#getSelected--}
```
public int getSelected()
```

Ottiene l'indice dell'opzione selezionata. Questa proprietà consente di modificare la selezione.

**Returns:**
valore int

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Imposta l'array degli elementi selezionati. Per un elenco a selezione multipla l'array contiene più di un elemento. Per un elenco a selezione singola contiene un solo elemento.

**Returns:**
array di valori int

### getValue {#getValue--}
```
public String getValue()
```

Restituisce il valore del campo.

**Returns:**
valore String

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Imposta il flag di commit al cambiamento della selezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Imposta il flag di selezione multipla.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOptions {#setOptions-java.util.List-}
Sostituisce le opzioni disponibili con quelle i cui nomi sono forniti nel parametro options.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Imposta l'indice dell'opzione selezionata. Questa proprietà consente di modificare la selezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Imposta l'array degli elementi selezionati. Per un elenco a selezione multipla l'array contiene più di un elemento. Per un elenco a selezione singola contiene un solo elemento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | array di valori int |

### setValue {#setValue-java.lang.String-}
Imposta il valore del campo.
