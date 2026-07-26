---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe di campo dello schema di una raccolta di documenti."
type: docs
weight: 620
url: /it/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Rappresenta una classe di campo dello schema di una raccolta di documenti.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getE](#getE--) | Restituisce un flag che indica se il processore PDF interattivo deve fornire supporto per la modifica del valore del campo. Valore predefinito: false |
| [getFiledType](#getFiledType--) | Restituisce il tipo di un valore di campo in una raccolta di schema. Questo campo descrive il tipo di valore corrispondente a {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}). |
| [getN](#getN--) | Restituisce il nome testuale del campo che deve essere presentato all'utente dal processore PDF interattivo |
| [getO](#getO--) | Restituisce l'ordine relativo del nome del campo nell'interfaccia utente. I campi devono essere ordinati dal processore PDF interattivo in ordine crescente. |
| [getSubtype](#getSubtype--) | Restituisce il sottotipo di un valore di campo in una raccolta di schema. Il sottotipo del campo di raccolta o del campo relativo a file che questo dizionario descrive. Questa voce identifica il tipo di dati che deve essere memorizzato nel campo. |
| [getV](#getV--) | Restituisce la visibilità iniziale del campo nell'interfaccia utente. Valore predefinito: true. |

### getE {#getE--}
```
public final boolean getE()
```

Restituisce un flag che indica se il processore PDF interattivo deve fornire supporto per la modifica del valore del campo. Valore predefinito: false

**Returns:**
valore booleano

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Restituisce il tipo di un valore di campo in una raccolta di schema. Questo campo descrive il tipo di valore corrispondente a {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}).

**Returns:**
Elemento FieldValueType

### getN {#getN--}
```
public final String getN()
```

Restituisce il nome testuale del campo che deve essere presentato all'utente dal processore PDF interattivo

**Returns:**
valore String

### getO {#getO--}
```
public final Integer [] getO()
```

Restituisce l'ordine relativo del nome del campo nell'interfaccia utente. I campi devono essere ordinati dal processore PDF interattivo in ordine crescente.

**Returns:**
array di Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Restituisce il sottotipo di un valore di campo in una raccolta di schema. Il sottotipo del campo di raccolta o del campo relativo a file che questo dizionario descrive. Questa voce identifica il tipo di dati che deve essere memorizzato nel campo.

**Returns:**
Elemento CollectionFieldSubtype

### getV {#getV--}
```
public final boolean getV()
```

Restituisce la visibilità iniziale del campo nell'interfaccia utente. Valore predefinito: true.

**Returns:**
valore booleano
