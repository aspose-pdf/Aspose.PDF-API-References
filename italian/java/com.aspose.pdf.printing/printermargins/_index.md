---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Specifica le dimensioni dei margini di una pagina stampata."
type: docs
weight: 70
url: /it/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

Specifica le dimensioni dei margini di una pagina stampata.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | Inizializza una nuova istanza della classe Margins con margini di larghezza di 1 pollice. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | Inizializza una nuova istanza della classe Margins con i margini sinistro, destro, superiore e inferiore specificati. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Recupera un duplicato di questo oggetto, membro per membro. |
| [equals](#equals-java.lang.Object-) | Confronta questi Margins con l'Object specificato per determinare se hanno le stesse dimensioni. (Sovrascrive Object.Equals(Object).) |
| [getBottom](#getBottom--) | Ottiene o imposta il margine inferiore, in centesimi di pollice. |
| [getLeft](#getLeft--) | Ottiene o imposta la larghezza del margine sinistro, in centesimi di pollice. |
| [getRight](#getRight--) | Ottiene o imposta la larghezza del margine destro, in centesimi di pollice. |
| [getTop](#getTop--) | Ottiene o imposta la larghezza del margine superiore, in centesimi di pollice. |
| [hashCode](#hashCode--) | Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Confronta due Margins per determinare se hanno le stesse dimensioni. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Confronta due Margins per determinare se hanno larghezze diverse. |
| [setBottom](#setBottom-int-) | Ottiene o imposta il margine inferiore, in centesimi di pollice. |
| [setLeft](#setLeft-int-) | Ottiene o imposta la larghezza del margine sinistro, in centesimi di pollice. |
| [setRight](#setRight-int-) | Ottiene o imposta la larghezza del margine destro, in centesimi di pollice. |
| [setTop](#setTop-int-) | Ottiene o imposta la larghezza del margine superiore, in centesimi di pollice. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

Inizializza una nuova istanza della classe Margins con margini di larghezza di 1 pollice.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

Inizializza una nuova istanza della classe Margins con i margini sinistro, destro, superiore e inferiore specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra |  | valore int |
| destro |  | valore int |
| alto |  | valore int |
| inferiore |  | valore int |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

Recupera un duplicato di questo oggetto, membro per membro.

**Returns:**
Oggetto PrinterMargins

### equals {#equals-java.lang.Object-}
Confronta questi Margins con l'Object specificato per determinare se hanno le stesse dimensioni. (Sovrascrive Object.Equals(Object).)

### getBottom {#getBottom--}
```
public int getBottom()
```

Ottiene o imposta il margine inferiore, in centesimi di pollice.

**Returns:**
valore int

### getLeft {#getLeft--}
```
public int getLeft()
```

Ottiene o imposta la larghezza del margine sinistro, in centesimi di pollice.

**Returns:**
valore int

### getRight {#getRight--}
```
public int getRight()
```

Ottiene o imposta la larghezza del margine destro, in centesimi di pollice.

**Returns:**
valore int

### getTop {#getTop--}
```
public int getTop()
```

Ottiene o imposta la larghezza del margine superiore, in centesimi di pollice.

**Returns:**
valore int

### hashCode {#hashCode--}
```
public int hashCode()
```

Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valore di hash code per questo oggetto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Confronta due Margins per determinare se hanno le stesse dimensioni.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Confronta due Margins per determinare se hanno larghezze diverse.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

Ottiene o imposta il margine inferiore, in centesimi di pollice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

Ottiene o imposta la larghezza del margine sinistro, in centesimi di pollice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

Ottiene o imposta la larghezza del margine destro, in centesimi di pollice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

Ottiene o imposta la larghezza del margine superiore, in centesimi di pollice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
