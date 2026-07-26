---
title: "XForm"
linktitle: "XForm"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta XForm"
type: docs
weight: 5590
url: /it/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

Classe che rappresenta XForm

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close](#close--) | Libera la memoria |
| [containsOwnResources](#containsOwnResources--) | Restituisce True se contiene Risorse proprie |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Crea un nuovo XForm nel documento. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Crea un XForm che duplica il contenuto della pagina. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Libera la memoria |
| [freeMemory](#freeMemory--) | Cancella i dati memorizzati nella cache |
| [getBBox](#getBBox--) | Ottiene il riquadro delimitatore del modulo. |
| [getContents](#getContents--) | Ottiene gli operatori del modulo. |
| [getEngineObj](#getEngineObj--) | Solo interno |
| [getIT](#getIT--) | Ottiene il Form IT. Form IT è un nome che descrive l'intento dell'XObject. |
| [getMatrix](#getMatrix--) | Ottiene la matrice del modulo. |
| [getName](#getName--) | Ottiene il nome del modulo. Il nome del modulo è il nome usato per fare riferimento al modulo nel dizionario XObejct nelle risorse della pagina. |
| [getOpi](#getOpi--) | Ottiene l'Open Prepress Interface (OPI). |
| [getRectangle](#getRectangle--) | Ottiene il rettangolo del modulo. |
| [getResources](#getResources--) | Restituisce le risorse del Form X-Object. Se il For non ha risorse e allowCreate è true, le Resources saranno create automaticamente per il modulo. |
| [getResources](#getResources-boolean-) | Restituisce le risorse del Form X-Object |
| [getResourcesField](#getResourcesField--) | Ottiene le risorse del Form XObject. |
| [getSubtype](#getSubtype--) | Ottiene il Subtype del modulo. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Imposta il riquadro delimitatore del modulo. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Imposta la matrice del modulo. |
| [setName](#setName-java.lang.String-) | Imposta il nome del modulo. Il nome del modulo è il nome usato per fare riferimento al modulo nel dizionario XObejct nelle risorse della pagina. |

### close {#close--}
```
public final void close()
```

Libera la memoria

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Restituisce True se contiene Risorse proprie

**Returns:**
valore booleano

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Crea un nuovo XForm nel documento.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Crea un XForm che duplica il contenuto della pagina.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Libera la memoria

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Cancella i dati memorizzati nella cache

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Ottiene il riquadro delimitatore del modulo.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Ottiene gli operatori del modulo.

**Returns:**
Oggetto OperatorCollection

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Solo interno

**Returns:**
Oggetto IPdfObject

### getIT {#getIT--}
```
public final String getIT()
```

Ottiene il Form IT. Form IT è un nome che descrive l'intento dell'XObject.

**Returns:**
valore String

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Ottiene la matrice del modulo.

**Returns:**
Matrice

### getName {#getName--}
```
public String getName()
```

Ottiene il nome del modulo. Il nome del modulo è il nome usato per fare riferimento al modulo nel dizionario XObejct nelle risorse della pagina.

**Returns:**
Stringa

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Ottiene l'Open Prepress Interface (OPI).

**Returns:**
Istanza Opi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ottiene il rettangolo del modulo.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Restituisce le risorse del Form X-Object. Se il For non ha risorse e allowCreate è true, le Resources saranno create automaticamente per il modulo.

**Returns:**
Istanza Resources

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Restituisce le risorse del Form X-Object

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| allowCreate |  | Se il For non ha risorse e allowCreate è true, le Resources saranno create automaticamente per il modulo. |

**Returns:**
Istanza Resources

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Ottiene le risorse del Form XObject.

**Returns:**
Istanza Resources. Se il For non ha risorse, le Resources saranno create automaticamente per il modulo.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Ottiene il Subtype del modulo.

**Returns:**
valore String

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Imposta il riquadro delimitatore del modulo.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Imposta la matrice del modulo.

### setName {#setName-java.lang.String-}
Imposta il nome del modulo. Il nome del modulo è il nome usato per fare riferimento al modulo nel dizionario XObejct nelle risorse della pagina.
