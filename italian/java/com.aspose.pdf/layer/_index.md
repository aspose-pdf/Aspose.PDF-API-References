---
title: "Layer"
linktitle: "Layer"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un livello all'interno di una pagina PDF."
type: docs
weight: 2640
url: /it/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

Rappresenta un livello all'interno di una pagina PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe {@code Layer}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [delete](#delete--) | Elimina lo strato corrente dal documento PDF. |
| [flatten](#flatten-boolean-) | Appiattisce lo strato specificato. |
| [getContents](#getContents--) | <p> Ottiene il contenuto dello strato. </p> |
| [getDefaultState](#getDefaultState--) | Ottiene lo stato predefinito dello strato PDF. |
| [getId](#getId--) | Ottiene l'ID dello strato. |
| [getLocked](#getLocked--) | Ottiene un valore che indica se lo strato è bloccato. |
| [getName](#getName--) | Ottiene il nome dello strato. |
| [lock](#lock--) | Blocca lo strato. |
| [save](#save-java.io.OutputStream-) | Salva lo strato corrente in un documento PDF. |
| [save](#save-java.lang.String-) | Salva lo strato corrente in un documento PDF. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | Imposta lo stato predefinito dello strato PDF. |
| [unlock](#unlock--) | Sblocca lo strato. |

### Layer {#Layer-java.lang.String-java.lang.String-}
Inizializza una nuova istanza della classe {@code Layer}.

### delete {#delete--}
```
public final void delete()
```

Elimina lo strato corrente dal documento PDF.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Appiattisce lo strato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cleanupContentStream |  | Specifica se rimuovere i marcatori del gruppo di contenuto opzionale dal flusso di contenuto. Impostare il parametro {@code cleanupContentStream} su false velocizza il processo di appiattimento. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Ottiene il contenuto dello strato. </p>

**Returns:**
oggetto {@code List<Operator>}

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

Ottiene lo stato predefinito dello strato PDF.

**Returns:**
lo stato predefinito dello strato PDF.

### getId {#getId--}
```
public String getId()
```

Ottiene l'ID dello strato.

**Returns:**
valore String

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Ottiene un valore che indica se lo strato è bloccato.

**Returns:**
valore booleano

### getName {#getName--}
```
public String getName()
```

Ottiene il nome dello strato.

**Returns:**
valore String

### lock {#lock--}
```
public final void lock()
```

Blocca lo strato.

### save {#save-java.io.OutputStream-}
Salva lo strato corrente in un documento PDF.

### save {#save-java.lang.String-}
Salva lo strato corrente in un documento PDF.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
Imposta lo stato predefinito dello strato PDF.

### unlock {#unlock--}
```
public final void unlock()
```

Sblocca lo strato.
