---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La classe descrive l'artefatto di numerazione Bates."
type: docs
weight: 290
url: /it/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

La classe descrive l'artefatto di numerazione Bates.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Inizializza una nuova istanza della classe {@link BatesNArtifact}. Questo costruttore è interno e crea un'istanza di artefatto header con valori predefiniti. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Ottiene o imposta il numero di cifre per la numerazione Bates. Il valore deve essere compreso tra 3 e 15 inclusi. Se viene impostato un valore inferiore a 3, verrà regolato a 3. Se viene impostato un valore superiore a 15, verrà regolato a 15. Il valore predefinito è 6. |
| [getPrefix](#getPrefix--) | Ottiene o imposta il prefisso da aggiungere al numero Bates. |
| [getStartNumber](#getStartNumber--) | Ottiene o imposta il numero iniziale per la numerazione Bates. Il valore deve essere maggiore o uguale a 1. Se viene impostato un valore inferiore a 1, verrà regolato a 1. |
| [getSuffix](#getSuffix--) | Ottiene o imposta il suffisso da aggiungere al numero Bates. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Ottiene o imposta il numero di cifre per la numerazione Bates. Il valore deve essere compreso tra 3 e 15 inclusi. Se viene impostato un valore inferiore a 3, verrà regolato a 3. Se viene impostato un valore superiore a 15, verrà regolato a 15. Il valore predefinito è 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Ottiene o imposta il prefisso da aggiungere al numero Bates. |
| [setStartNumber](#setStartNumber-int-) | Ottiene o imposta il numero iniziale per la numerazione Bates. Il valore deve essere maggiore o uguale a 1. Se viene impostato un valore inferiore a 1, verrà regolato a 1. |
| [setSuffix](#setSuffix-java.lang.String-) | Ottiene o imposta il suffisso da aggiungere al numero Bates. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Inizializza una nuova istanza della classe {@link BatesNArtifact}. Questo costruttore è interno e crea un'istanza di artefatto header con valori predefiniti.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Ottiene o imposta il numero di cifre per la numerazione Bates. Il valore deve essere compreso tra 3 e 15 inclusi. Se viene impostato un valore inferiore a 3, verrà regolato a 3. Se viene impostato un valore superiore a 15, verrà regolato a 15. Il valore predefinito è 6.

**Returns:**
valore int

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Ottiene o imposta il prefisso da aggiungere al numero Bates.

**Returns:**
valore String

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Ottiene o imposta il numero iniziale per la numerazione Bates. Il valore deve essere maggiore o uguale a 1. Se viene impostato un valore inferiore a 1, verrà regolato a 1.

**Returns:**
valore int

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Ottiene o imposta il suffisso da aggiungere al numero Bates.

**Returns:**
valore String

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Ottiene o imposta il numero di cifre per la numerazione Bates. Il valore deve essere compreso tra 3 e 15 inclusi. Se viene impostato un valore inferiore a 3, verrà regolato a 3. Se viene impostato un valore superiore a 15, verrà regolato a 15. Il valore predefinito è 6.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPrefix {#setPrefix-java.lang.String-}
Ottiene o imposta il prefisso da aggiungere al numero Bates.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Ottiene o imposta il numero iniziale per la numerazione Bates. Il valore deve essere maggiore o uguale a 1. Se viene impostato un valore inferiore a 1, verrà regolato a 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setSuffix {#setSuffix-java.lang.String-}
Ottiene o imposta il suffisso da aggiungere al numero Bates.
