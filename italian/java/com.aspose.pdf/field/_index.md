---
title: "Campo"
linktitle: "Campo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe base per i campi AcroForm."
type: docs
weight: 1380
url: /it/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Classe base per i campi AcroForm.

## Campi

| Campo | Descrizione |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Crea campo per l'uso in Generator. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Copia i sotto‑campi di questo campo in un array a partire dall'indice specificato. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copia i sotto‑campi di questo campo in un array a partire dall'indice specificato. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Esegue un'azione JavaScript specificata per il campo. |
| [flatten](#flatten--) | Rimuove questo campo e posiziona il suo valore direttamente sulla pagina. |
| [get_Item](#get_Item-int-) | Ottiene il sotto‑campo contenuto in questo campo per indice. |
| [get_Item](#get_Item-java.lang.String-) | Ottiene il sotto‑campo contenuto in questo campo per nome del sotto‑campo. |
| [getAlternateName](#getAlternateName--) | Ottiene il nome alternativo del campo (Un nome alternativo del campo che deve essere usato al posto del nome reale del campo ovunque il campo debba essere identificato nell'interfaccia utente). Il nome alternativo è usato come tooltip del campo in Adobe Acrobat. |
| [getAnnotationIndex](#getAnnotationIndex--) | Ottiene l'indice di questa annotazione sulla pagina. |
| [getMappingName](#getMappingName--) | Ottiene il nome di mappatura del campo che deve essere usato durante l'esportazione dei dati dei campi del modulo interattivo dal documento. |
| [getMaxFontSize](#getMaxFontSize--) | Dimensione massima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione. |
| [getMinFontSize](#getMinFontSize--) | Dimensione minima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione. |
| [getPageIndex](#getPageIndex--) | Ottiene l'indice della pagina che contiene questo campo. |
| [getPartialName](#getPartialName--) | Ottiene il nome parziale del campo. |
| [getRect](#getRect--) | Ottiene il rettangolo del campo. |
| [getSyncRoot](#getSyncRoot--) | Oggetto di sincronizzazione. |
| [getTabOrder](#getTabOrder--) | Ottiene o imposta l'ordine di tabulazione del campo. |
| [getValue](#getValue--) | Restituisce il valore del campo. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | Se vero, la dimensione del carattere sarà ridotta per adattare il testo al rettangolo specificato. |
| [isGroup](#isGroup--) | Ottiene il valore booleano che indica se questo campo è un campo non terminale, cioè un gruppo di campi. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Proprietà per il supporto di Generator. Usata quando il campo è aggiunto all'intestazione o al piè di pagina. Se vero, questo campo verrà creato una sola volta e il suo aspetto sarà visibile su tutte le pagine del documento. Se falso, verrà creato un campo separato per ogni pagina del documento. |
| [isSynchronized](#isSynchronized--) | Restituisce vero se il dizionario è sincronizzato. |
| [iterator](#iterator--) | Restituisce l'enumeratore dei campi contenuti. |
| [recalculate](#recalculate--) | Ricalcola tutti i campi calcolati nel modulo. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Imposta il nome alternativo del campo (Un nome alternativo del campo che deve essere usato al posto del nome reale del campo ovunque il campo debba essere identificato nell'interfaccia utente). Il nome alternativo è usato come tooltip del campo in Adobe Acrobat. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Imposta l'indice di questa annotazione nella pagina. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | Se vero, la dimensione del carattere sarà ridotta per adattare il testo al rettangolo specificato. |
| [setMappingName](#setMappingName-java.lang.String-) | Imposta il nome di mappatura del campo che deve essere usato durante l'esportazione dei dati dei campi del modulo interattivo dal documento. |
| [setMaxFontSize](#setMaxFontSize-double-) | Dimensione massima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione. |
| [setMinFontSize](#setMinFontSize-double-) | Dimensione minima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione. |
| [setPartialName](#setPartialName-java.lang.String-) | Imposta il nome parziale del campo. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Imposta la posizione del campo. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Imposta il rettangolo del campo. |
| [setSharedField](#setSharedField-boolean-) | Proprietà per il supporto di Generator. Usata quando il campo è aggiunto all'intestazione o al piè di pagina. Se vero, questo campo verrà creato una sola volta e il suo aspetto sarà visibile su tutte le pagine del documento. Se falso, verrà creato un campo separato per ogni pagina del documento. |
| [setTabOrder](#setTabOrder-int-) | Ottiene o imposta l'ordine di tabulazione del campo. |
| [setValue](#setValue-java.lang.String-) | Imposta il valore. |
| [size](#size--) | Ottiene il numero di sotto‑campi in questo campo. (Ad esempio il numero di elementi in un campo di pulsante radio). |
| [updateAppearances](#updateAppearances--) | Aggiorna il valore delle apparenze. |

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
Crea campo per l'uso in Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Copia i sotto‑campi di questo campo in un array a partire dall'indice specificato.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copia i sotto‑campi di questo campo in un array a partire dall'indice specificato.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Esegue un'azione JavaScript specificata per il campo.

### flatten {#flatten--}
```
public void flatten()
```

Rimuove questo campo e posiziona il suo valore direttamente sulla pagina.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Ottiene il sotto‑campo contenuto in questo campo per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice del sotto‑campo richiesto. |

**Returns:**
Istanza del campo.

### get_Item {#get_Item-java.lang.String-}
Ottiene il sotto‑campo contenuto in questo campo per nome del sotto‑campo.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Ottiene il nome alternativo del campo (Un nome alternativo del campo che deve essere usato al posto del nome reale del campo ovunque il campo debba essere identificato nell'interfaccia utente). Il nome alternativo è usato come tooltip del campo in Adobe Acrobat.

**Returns:**
valore String

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Ottiene l'indice di questa annotazione sulla pagina.

**Returns:**
valore int

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Ottiene il nome di mappatura del campo che deve essere usato durante l'esportazione dei dati dei campi del modulo interattivo dal documento.

**Returns:**
valore String

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Dimensione massima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione.

**Returns:**
valore double

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Dimensione minima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione.

**Returns:**
valore double

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Ottiene l'indice della pagina che contiene questo campo.

**Returns:**
valore int

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Ottiene il nome parziale del campo.

**Returns:**
valore String

### getRect {#getRect--}
```
public Rectangle getRect()
```

Ottiene il rettangolo del campo.

**Returns:**
il rettangolo del campo.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Oggetto di sincronizzazione.

**Returns:**
valore dell'oggetto

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Ottiene o imposta l'ordine di tabulazione del campo.

**Returns:**
valore int

### getValue {#getValue--}
```
public String getValue()
```

Restituisce il valore del campo.

**Returns:**
valore String

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

Se vero, la dimensione del carattere sarà ridotta per adattare il testo al rettangolo specificato.

**Returns:**
valore booleano

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Ottiene il valore booleano che indica se questo campo è un campo non terminale, cioè un gruppo di campi.

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Proprietà per il supporto di Generator. Usata quando il campo è aggiunto all'intestazione o al piè di pagina. Se vero, questo campo verrà creato una sola volta e il suo aspetto sarà visibile su tutte le pagine del documento. Se falso, verrà creato un campo separato per ogni pagina del documento.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Restituisce vero se il dizionario è sincronizzato.

**Returns:**
valore booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Restituisce l'enumeratore dei campi contenuti.

**Returns:**
Oggetto enumeratore.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Ricalcola tutti i campi calcolati nel modulo.

**Returns:**
vero se il valore del campo è stato modificato durante il ricalcolo.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Imposta il nome alternativo del campo (Un nome alternativo del campo che deve essere usato al posto del nome reale del campo ovunque il campo debba essere identificato nell'interfaccia utente). Il nome alternativo è usato come tooltip del campo in Adobe Acrobat.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Imposta l'indice di questa annotazione nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

Se vero, la dimensione del carattere sarà ridotta per adattare il testo al rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMappingName {#setMappingName-java.lang.String-}
Imposta il nome di mappatura del campo che deve essere usato durante l'esportazione dei dati dei campi del modulo interattivo dal documento.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Dimensione massima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Dimensione minima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setPartialName {#setPartialName-java.lang.String-}
Imposta il nome parziale del campo.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Imposta la posizione del campo.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Imposta il rettangolo del campo.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Proprietà per il supporto di Generator. Usata quando il campo è aggiunto all'intestazione o al piè di pagina. Se vero, questo campo verrà creato una sola volta e il suo aspetto sarà visibile su tutte le pagine del documento. Se falso, verrà creato un campo separato per ogni pagina del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Ottiene o imposta l'ordine di tabulazione del campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setValue {#setValue-java.lang.String-}
Imposta il valore.

### size {#size--}
```
public int size()
```

Ottiene il numero di sotto‑campi in questo campo. (Ad esempio il numero di elementi in un campo di pulsante radio).

**Returns:**
valore int

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Aggiorna il valore delle apparenze.
