---
title: "Form"
linktitle: "Form"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'oggetto modulo."
type: docs
weight: 1740
url: /it/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Classe che rappresenta l'oggetto modulo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Aggiunge un campo al modulo. |
| [add](#add-com.aspose.pdf.Field-int-) | Aggiunge un campo al modulo. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Aggiunge un nuovo campo al modulo; se questo campo è già posizionato su un altro o su questo modulo, viene creata una copia del campo. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Aggiunge un campo al modulo. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Aggiunge un aspetto aggiuntivo del campo alla pagina specificata del documento nella posizione specificata. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Aggiunge un aspetto aggiuntivo del campo alla pagina specificata del documento. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Imposta XFA del modulo al valore specificato. |
| [clear](#clear--) | Elimina tutti i campi dal modulo. Non supportato. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Determina se il campo è presente nel modulo.. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copia i campi posizionati sul modulo in un array. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Copia i campi del modulo in un array. |
| [delete](#delete-com.aspose.pdf.Field-) | Elimina il campo dal modulo. |
| [delete](#delete-java.lang.String-) | Elimina il campo dal modulo per nome. |
| [flatten](#flatten--) | Rimuove tutti i campi statici del modulo e posiziona i loro valori direttamente sulla pagina. |
| [get_Item](#get_Item-int-) | Ottiene il campo del modulo per indice del campo. |
| [get_Item](#get_Item-java.lang.String-) | Ottiene il campo del modulo per nome del campo. Lancia un'eccezione se il campo non è stato trovato. |
| [get_xfa](#get_xfa--) | Solo per uso interno |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Cerca il campo per nome del campo. Restituisce null se il campo non è stato trovato. |
| [getAutoRecalculate](#getAutoRecalculate--) | Se impostato, tutti i campi del modulo verranno ricalcolati quando qualsiasi campo viene modificato. Il valore predefinito è true. Impostare a false per aumentare le prestazioni durante la compilazione del modulo con un gran numero di campi calcolati. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | Se impostato, i campi del modulo assenti verranno creati automaticamente se presenti nelle annotazioni. |
| [getDefaultAppearance](#getDefaultAppearance--) | Ottiene l'aspetto predefinito del modulo (oggetto che descrive il carattere predefinito, la dimensione del testo e il colore per i campi del modulo). |
| [getDefaultResources](#getDefaultResources--) | Ottiene le risorse predefinite posizionate su questo modulo. |
| [getDocument](#getDocument--) | Solo per uso interno |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Se questa proprietà è true allora verranno disegnati rettangoli rossi aggiuntivi per i contenitori degli elementi Xfa exclGroup richiesti. Questa proprietà è stata introdotta a causa dell'assenza di analoghi per exclGroup durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita. |
| [getFields](#getFields--) | Ottiene l'elenco di tutti i campi al livello più basso del modulo gerarchico. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Restituisce i campi all'interno del rettangolo specificato. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | Se questa proprietà è true il valore della chiave NeedsRendering verrà ignorato durante la conversione del modulo XFA in modulo Standard. È false per impostazione predefinita. |
| [getNeedsRendering](#getNeedsRendering--) | Ottiene un valore che indica se il documento richiede la rimozione del modulo XFA dinamico. Questa proprietà è stata introdotta per determinare se {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) debba essere usata per rimuovere il modulo XFA nei casi in cui il modulo XFA è presente e {@code NeedsRendering}({@link #getNeedsRendering}) è false. |
| [getRemovePermission](#getRemovePermission--) | Se questa proprietà è true il dizionario "Perms" verrà rimosso dal documento PDF dopo la conversione dei documenti dinamici allo standard. Il dizionario "Perms" può contenere regole che disturbano la visualizzazione della selezione dei campi obbligatori in Adobe Acrobat Reader. È false per impostazione predefinita. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | Se impostato, il documento contiene firme che potrebbero essere invalidate se il file viene salvato (scritto) in un modo che ne altera il contenuto precedente, anziché con un aggiornamento incrementale. |
| [getSignaturesExist](#getSignaturesExist--) | Se impostato, il documento contiene almeno un campo firma. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | I moduli possono contenere informazioni di firma, cioè possono essere firmati o non firmati. E la visualizzazione del modulo a volte deve dipendere dal fatto che il modulo sia firmato o meno. Questa proprietà indica al convertitore del modulo (ad es. durante la conversione del modulo XFA in modulo Standard) se il modulo risultante deve essere renderizzato come firmato o come non firmato. |
| [getSyncRoot](#getSyncRoot--) | Restituisce l'oggetto di sincronizzazione. |
| [getType](#getType--) | Ottiene il tipo del modulo. I valori possibili sono: Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Ottiene i dati XFA del modulo (se presenti). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Verifica se il modulo possiede già il campo specificato. |
| [hasField](#hasField-java.lang.String-) | Determina se il campo con il nome specificato è già stato aggiunto al Modulo. |
| [hasField](#hasField-java.lang.String-boolean-) | Determina se il campo con il nome specificato è già stato aggiunto al Modulo, con la possibilità di esaminare la gerarchia dei campi figli. |
| [hasXfa](#hasXfa--) | Ottiene un valore che indica se il documento contiene un modulo XFA. Questa proprietà è stata introdotta per determinare se {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) debba essere usata per rimuovere il modulo XFA nei casi in cui il modulo XFA è presente e {@code NeedsRendering}({@link #getNeedsRendering}) è false. |
| [isReadOnly](#isReadOnly--) | Determina se la collezione è in sola lettura. Restituisce sempre false. |
| [isSynchronized](#isSynchronized--) | Restituisce true se l'oggetto è thread-safe. |
| [iterator](#iterator--) | Ottiene l'enumerazione dei campi del modulo. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * Esporta i campi del modulo PDF in formato JSON e scrive il risultato nello stream fornito. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Elimina il campo dal modulo. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Rimuove l'aspetto del campo all'indice specificato. Se rimane un solo aspetto figlio, il metodo lo incorpora nel campo. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | Se impostato, tutti i campi del modulo verranno ricalcolati quando qualsiasi campo viene modificato. Il valore predefinito è true. Impostare a false per aumentare le prestazioni durante la compilazione del modulo con un gran numero di campi calcolati. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | Se impostato, i campi del modulo assenti verranno creati automaticamente se presenti nelle annotazioni. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Consente di impostare l'ordine di calcolo dei campi. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Imposta l'aspetto predefinito del modulo (oggetto che descrive il carattere predefinito, la dimensione del testo e il colore per i campi del modulo). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Se questa proprietà è true allora verranno disegnati rettangoli rossi aggiuntivi per i contenitori degli elementi Xfa exclGroup richiesti. Questa proprietà è stata introdotta a causa dell'assenza di analoghi per exclGroup durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | Se questa proprietà è true il valore della chiave NeedsRendering verrà ignorato durante la conversione del modulo XFA in modulo Standard. È false per impostazione predefinita. |
| [setRemovePermission](#setRemovePermission-boolean-) | Se questa proprietà è true il dizionario "Perms" verrà rimosso dal documento PDF dopo la conversione dei documenti dinamici allo standard. Il dizionario "Perms" può contenere regole che disturbano la visualizzazione della selezione dei campi obbligatori in Adobe Acrobat Reader. È false per impostazione predefinita. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | Se impostato, il documento contiene firme che potrebbero essere invalidate se il file viene salvato (scritto) in un modo che ne altera il contenuto precedente, anziché con un aggiornamento incrementale. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | Se impostato, il documento contiene almeno un campo firma. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | I moduli possono contenere informazioni di firma, cioè possono essere firmati o non firmati. E la visualizzazione del modulo a volte deve dipendere dal fatto che il modulo sia firmato o meno. Questa proprietà indica al convertitore del modulo (ad es. durante la conversione del modulo XFA in modulo Standard) se il modulo risultante deve essere renderizzato come firmato o come non firmato. |
| [setType](#setType-com.aspose.pdf.FormType-) | Ottiene il tipo del modulo. I valori possibili sono: Standard, Static, Dynamic. |
| [size](#size--) | Ottiene il numero dei campi in questo modulo. |

### Form {#Form-com.aspose.pdf.IDocument-}
Costruttore

### add {#add-com.aspose.pdf.Field-}
Aggiunge un campo al modulo.

### add {#add-com.aspose.pdf.Field-int-}
Aggiunge un campo al modulo.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Aggiunge un nuovo campo al modulo; se questo campo è già posizionato su un altro o su questo modulo, viene creata una copia del campo.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Aggiunge un campo al modulo.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Aggiunge un aspetto aggiuntivo del campo alla pagina specificata del documento nella posizione specificata.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Aggiunge un aspetto aggiuntivo del campo alla pagina specificata del documento.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Imposta XFA del modulo al valore specificato.

### clear {#clear--}
```
public void clear()
```

Elimina tutti i campi dal modulo. Non supportato.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Determina se il campo è presente nel modulo..

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copia i campi posizionati sul modulo in un array.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Copia i campi del modulo in un array.

### delete {#delete-com.aspose.pdf.Field-}
Elimina il campo dal modulo.

### delete {#delete-java.lang.String-}
Elimina il campo dal modulo per nome.

### flatten {#flatten--}
```
public void flatten()
```

Rimuove tutti i campi statici del modulo e posiziona i loro valori direttamente sulla pagina.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Ottiene il campo del modulo per indice del campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice del campo. |

**Returns:**
Campo recuperato.

### get_Item {#get_Item-java.lang.String-}
Ottiene il campo del modulo per nome del campo. Lancia un'eccezione se il campo non è stato trovato.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

Solo per uso interno

**Returns:**
Oggetto XFA

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
Cerca il campo per nome del campo. Restituisce null se il campo non è stato trovato.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

Se impostato, tutti i campi del modulo verranno ricalcolati quando qualsiasi campo viene modificato. Il valore predefinito è true. Impostare a false per aumentare le prestazioni durante la compilazione del modulo con un gran numero di campi calcolati.

**Returns:**
valore booleano

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

Se impostato, i campi del modulo assenti verranno creati automaticamente se presenti nelle annotazioni.

**Returns:**
valore booleano

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Ottiene l'aspetto predefinito del modulo (oggetto che descrive il carattere predefinito, la dimensione del testo e il colore per i campi del modulo).

**Returns:**
oggetto DefaultAppearance

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Ottiene le risorse predefinite posizionate su questo modulo.

**Returns:**
Valore delle risorse

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Solo per uso interno

**Returns:**
Oggetto IDocument

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Se questa proprietà è true allora verranno disegnati rettangoli rossi aggiuntivi per i contenitori degli elementi Xfa exclGroup richiesti. Questa proprietà è stata introdotta a causa dell'assenza di analoghi per exclGroup durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita.

**Returns:**
valore booleano

### getFields {#getFields--}
```
public Field [] getFields()
```

Ottiene l'elenco di tutti i campi al livello più basso del modulo gerarchico.

**Returns:**
Array con i campi trovati.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Restituisce i campi all'interno del rettangolo specificato.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

Se questa proprietà è true il valore della chiave NeedsRendering verrà ignorato durante la conversione del modulo XFA in modulo Standard. È false per impostazione predefinita.

**Returns:**
valore booleano

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Ottiene un valore che indica se il documento richiede la rimozione del modulo XFA dinamico. Questa proprietà è stata introdotta per determinare se {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) debba essere usata per rimuovere il modulo XFA nei casi in cui il modulo XFA è presente e {@code NeedsRendering}({@link #getNeedsRendering}) è false.

**Returns:**
valore booleano

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

Se questa proprietà è true il dizionario "Perms" verrà rimosso dal documento PDF dopo la conversione dei documenti dinamici allo standard. Il dizionario "Perms" può contenere regole che disturbano la visualizzazione della selezione dei campi obbligatori in Adobe Acrobat Reader. È false per impostazione predefinita.

**Returns:**
valore booleano

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

Se impostato, il documento contiene firme che potrebbero essere invalidate se il file viene salvato (scritto) in un modo che ne altera il contenuto precedente, anziché con un aggiornamento incrementale.

**Returns:**
valore booleano

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

Se impostato, il documento contiene almeno un campo firma.

**Returns:**
valore booleano

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

I moduli possono contenere informazioni di firma, cioè possono essere firmati o non firmati. E la visualizzazione del modulo a volte deve dipendere dal fatto che il modulo sia firmato o meno. Questa proprietà indica al convertitore del modulo (ad es. durante la conversione del modulo XFA in modulo Standard) se il modulo risultante deve essere renderizzato come firmato o come non firmato.

**Returns:**
Elemento SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Restituisce l'oggetto di sincronizzazione.

**Returns:**
Oggetto per la sincronizzazione

### getType {#getType--}
```
public FormType getType()
```

Ottiene il tipo del modulo. I valori possibili sono: Standard, Static, Dynamic.

**Returns:**
Valore FormType @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Ottiene i dati XFA del modulo (se presenti).

**Returns:**
Valore XFA

### hasField {#hasField-com.aspose.pdf.Field-}
Verifica se il modulo possiede già il campo specificato.

### hasField {#hasField-java.lang.String-}
Determina se il campo con il nome specificato è già stato aggiunto al Modulo.

### hasField {#hasField-java.lang.String-boolean-}
Determina se il campo con il nome specificato è già stato aggiunto al Modulo, con la possibilità di esaminare la gerarchia dei campi figli.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Ottiene un valore che indica se il documento contiene un modulo XFA. Questa proprietà è stata introdotta per determinare se {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) debba essere usata per rimuovere il modulo XFA nei casi in cui il modulo XFA è presente e {@code NeedsRendering}({@link #getNeedsRendering}) è false.

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Determina se la collezione è in sola lettura. Restituisce sempre false.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Restituisce true se l'oggetto è thread-safe.

**Returns:**
valore booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Ottiene l'enumerazione dei campi del modulo.

**Returns:**
Enumeratore di campo.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * Esporta i campi del modulo PDF in formato JSON e scrive il risultato nello stream fornito. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Elimina il campo dal modulo.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Rimuove l'aspetto del campo all'indice specificato. Se rimane un solo aspetto figlio, il metodo lo incorpora nel campo.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

Se impostato, tutti i campi del modulo verranno ricalcolati quando qualsiasi campo viene modificato. Il valore predefinito è true. Impostare a false per aumentare le prestazioni durante la compilazione del modulo con un gran numero di campi calcolati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

Se impostato, i campi del modulo assenti verranno creati automaticamente se presenti nelle annotazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Consente di impostare l'ordine di calcolo dei campi.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Imposta l'aspetto predefinito del modulo (oggetto che descrive il carattere predefinito, la dimensione del testo e il colore per i campi del modulo).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Se questa proprietà è true allora verranno disegnati rettangoli rossi aggiuntivi per i contenitori degli elementi Xfa exclGroup richiesti. Questa proprietà è stata introdotta a causa dell'assenza di analoghi per exclGroup durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

Se questa proprietà è true il valore della chiave NeedsRendering verrà ignorato durante la conversione del modulo XFA in modulo Standard. È false per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

Se questa proprietà è true il dizionario "Perms" verrà rimosso dal documento PDF dopo la conversione dei documenti dinamici allo standard. Il dizionario "Perms" può contenere regole che disturbano la visualizzazione della selezione dei campi obbligatori in Adobe Acrobat Reader. È false per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

Se impostato, il documento contiene firme che potrebbero essere invalidate se il file viene salvato (scritto) in un modo che ne altera il contenuto precedente, anziché con un aggiornamento incrementale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

Se impostato, il documento contiene almeno un campo firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

I moduli possono contenere informazioni di firma, cioè possono essere firmati o non firmati. E la visualizzazione del modulo a volte deve dipendere dal fatto che il modulo sia firmato o meno. Questa proprietà indica al convertitore del modulo (ad es. durante la conversione del modulo XFA in modulo Standard) se il modulo risultante deve essere renderizzato come firmato o come non firmato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | Elemento SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Ottiene il tipo del modulo. I valori possibili sono: Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Ottiene il numero dei campi in questo modulo.

**Returns:**
valore int
