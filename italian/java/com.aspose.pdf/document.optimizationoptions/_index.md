---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources(). @deprecated Questa classe è obsoleta. Per favore."
type: docs
weight: 1110
url: /it/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources(). @deprecated Questa classe è obsoleta. Si prega di utilizzare com.aspose.pdf.optimization.OptimizationOptions al suo posto.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Obsoleto. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [all](#all--) | Crea una strategia di ottimizzazione con tutte le opzioni attivate. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Specifica la dimensione massima dell'immagine. Se la larghezza o l'altezza dell'immagine esistente è maggiore di questo valore, la dimensione dell'immagine verrà ridotta proporzionalmente. |
| [getResolution](#getResolution--) | Specifica i nuovi dpi dell'immagine quando viene usata l'opzione CompressIamges. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Specifica la dimensione massima dell'immagine. Se la larghezza o l'altezza dell'immagine esistente è maggiore di questo valore, la dimensione dell'immagine verrà ridotta proporzionalmente. |
| [setResolution](#setResolution-int-) | Specifica i nuovi dpi dell'immagine quando viene usata l'opzione CompressIamges. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Obsoleto.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Crea una strategia di ottimizzazione con tutte le opzioni attivate.

**Returns:**
Oggetto OptimizationOptions.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Specifica la dimensione massima dell'immagine. Se la larghezza o l'altezza dell'immagine esistente è maggiore di questo valore, la dimensione dell'immagine verrà ridotta proporzionalmente.

**Returns:**
dimensione massima dell'immagine

### getResolution {#getResolution--}
```
public int getResolution()
```

Specifica i nuovi dpi dell'immagine quando viene usata l'opzione CompressIamges.

**Returns:**
risoluzione dell'immagine

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Specifica la dimensione massima dell'immagine. Se la larghezza o l'altezza dell'immagine esistente è maggiore di questo valore, la dimensione dell'immagine verrà ridotta proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione |  | dimensione massima dell'immagine |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Specifica i nuovi dpi dell'immagine quando viene usata l'opzione CompressIamges.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpi |  | risoluzione dell'immagine |
