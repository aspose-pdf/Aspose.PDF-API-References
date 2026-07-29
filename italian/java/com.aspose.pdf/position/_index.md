---
title: "Position"
linktitle: "Position"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un oggetto posizione"
type: docs
weight: 3940
url: /it/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Rappresenta un oggetto posizione

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Position](#Position-double-double-) | Inizializza una nuova istanza della classe {@code Position} |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Determina se l'oggetto specificato è uguale all'oggetto {@code Position} corrente. |
| [getXIndent](#getXIndent--) | Ottiene la coordinata X dell'oggetto |
| [getYIndent](#getYIndent--) | Ottiene la coordinata Y dell'oggetto |
| [hashCode](#hashCode--) | Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [setXIndent](#setXIndent-double-) | Imposta la coordinata X dell'oggetto |
| [setYIndent](#setYIndent-double-) | Imposta la coordinata Y dell'oggetto |
| [toString](#toString--) | Ottiene la rappresentazione stringa per l'oggetto {@code Position} corrente. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Inizializza una nuova istanza della classe {@code Position}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xIndent |  | Valore della coordinata X. |
| yIndent |  | Valore della coordinata Y. |

### equals {#equals-java.lang.Object-}
Determina se l'oggetto specificato è uguale all'oggetto {@code Position} corrente.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Ottiene la coordinata X dell'oggetto

**Returns:**
valore double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Ottiene la coordinata Y dell'oggetto

**Returns:**
valore double

### hashCode {#hashCode--}
```
public int hashCode()
```

Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valore di hash code per questo oggetto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Imposta la coordinata X dell'oggetto

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Imposta la coordinata Y dell'oggetto

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### toString {#toString--}
```
public String toString()
```

Ottiene la rappresentazione stringa per l'oggetto {@code Position} corrente.

**Returns:**
Rappresentazione stringa dell'oggetto Position.
