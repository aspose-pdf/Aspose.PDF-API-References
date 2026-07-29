---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta un rettangolo."
type: docs
weight: 4100
url: /it/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Classe che rappresenta un rettangolo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Costruttore di Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Costruttore di Rectangle. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Interseca i rettangoli. Metodo obsoleto. Si prega di usare Intersect invece. |
| [center](#center--) | Restituisce le coordinate del centro del rettangolo. |
| [clone](#clone--) | Clona l'oggetto Rectangle. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Determina se il punto dato è all'interno del rettangolo. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Determina se il punto dato è all'interno del rettangolo. |
| [containsLine](#containsLine-double-double-double-double-) | Determina se il rettangolo contiene una linea rappresentata da due punti. |
| [containsPoint](#containsPoint-double-double-) | Determina se il punto dato è contenuto all'interno del rettangolo. |
| [deepClone](#deepClone--) | Clona l'oggetto Rectangle. |
| [equals](#equals-java.lang.Object-) | Verifica se i rettangoli sono uguali, cioè hanno la stessa posizione e dimensioni. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Inizializza un nuovo rettangolo dall'istanza fornita di System.Drawing.Rectangle. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Inizializza un nuovo rettangolo dall'istanza fornita di System.Drawing.Rectangle. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Calcola l'area del rettangolo. |
| [getEmpty](#getEmpty--) | Restituisce un rettangolo vuoto |
| [getHeight](#getHeight--) | Ottieni l'altezza del rettangolo. |
| [getLLX](#getLLX--) | Ottiene la coordinata X dell'angolo inferiore sinistro. |
| [getLLY](#getLLY--) | Ottiene la coordinata Y dell'angolo inferiore sinistro. |
| [getTrivial](#getTrivial--) | Inizializza un rettangolo banale, cioè un rettangolo con posizione e dimensione zero. |
| [getURX](#getURX--) | Ottiene la coordinata X dell'angolo superiore destro. |
| [getURY](#getURY--) | Ottiene la coordinata Y dell'angolo superiore destro. |
| [getWidth](#getWidth--) | Ottiene la larghezza del rettangolo. |
| [hashCode](#hashCode--) | Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Interseca due rettangoli. |
| [isEmpty](#isEmpty--) | Verifica se il rettangolo è vuoto. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Verifica che questo rettangolo includa un altro rettangolo intero. Cioè, l'altro rettangolo intero è all'interno di questo rettangolo. La differenza con il metodo IsIntersect è che IsIntersect sarà vero per rettangoli parzialmente intersecati, ma IsInclude sarà falso. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Determina se questo rettangolo interseca con un altro rettangolo. |
| [isPoint](#isPoint--) | Verifica se il rettangolo è un punto, cioè LLX è uguale a URX e LLY è uguale a URY. |
| [isTrivial](#isTrivial--) | Verifica se il rettangolo è triviale, cioè ha dimensioni e posizione zero. |
| [join](#join-com.aspose.pdf.Rectangle-) | Unisce i rettangoli. |
| [moveBy](#moveBy-double-double-) | Sposta il rettangolo dei delta specificati. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Verifica se i rettangoli sono quasi uguali, cioè hanno posizione e dimensioni quasi identiche (entro il delta). |
| [parse](#parse-java.lang.String-) | Prova a analizzare la stringa ed estrarre da essa i componenti del rettangolo llx, lly, urx, ury. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Ruota il rettangolo dell'angolo specificato. |
| [rotateAngle](#rotateAngle-int-) | Ruota il rettangolo dell'angolo specificato. |
| [setLLX](#setLLX-double-) | Imposta la coordinata X dell'angolo inferiore sinistro. |
| [setLLY](#setLLY-double-) | Imposta la coordinata Y dell'angolo inferiore sinistro. |
| [setURX](#setURX-double-) | Imposta la coordinata X dell'angolo superiore destro. |
| [setURY](#setURY-double-) | Imposta la coordinata Y dell'angolo superiore destro. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Converte il rettangolo in un array di punti ("QuadPoints"). |
| [toRect](#toRect--) | Converte il rettangolo in un'istanza di System.Drawing.Rectangle. Le posizioni e le dimensioni in virgola mobile vengono troncate. |
| [toString](#toString--) | Ottiene la rappresentazione stringa del rettangolo. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Costruttore di Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| llx |  | X dell'angolo inferiore sinistro. |
| lly |  | Y dell'angolo inferiore sinistro. |
| urx |  | X dell'angolo superiore destro. |
| ury |  | Y dell'angolo superiore destro. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Costruttore di Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| llx |  | X dell'angolo inferiore sinistro. |
| lly |  | Y dell'angolo inferiore sinistro. |
| urx |  | X dell'angolo superiore destro. |
| ury |  | Y dell'angolo superiore destro. |
| normalizeCoordinates |  | Normalizza le coordinate del rettangolo. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Interseca i rettangoli. Metodo obsoleto. Si prega di usare Intersect invece.

### center {#center--}
```
public Point center()
```

Restituisce le coordinate del centro del rettangolo.

**Returns:**
Punto che è il centro del rettangolo.

### clone {#clone--}
```
public Rectangle clone()
```

Clona l'oggetto Rectangle.

**Returns:**
Clona oggetto.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Determina se il punto dato è all'interno del rettangolo.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Determina se il punto dato è all'interno del rettangolo.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Determina se il rettangolo contiene una linea rappresentata da due punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 |  | La coordinata X del punto di partenza della linea. |
| y1 |  | La coordinata Y del punto di partenza della linea. |
| x2 |  | La coordinata X del punto finale della linea. |
| y2 |  | La coordinata Y del punto finale della linea. |

**Returns:**
{@code true} se il rettangolo contiene la linea; altrimenti, {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Determina se il punto dato è contenuto all'interno del rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | Coordinata X del punto. |
| y |  | Coordinata Y del punto. |

**Returns:**
{@code true} se il punto è contenuto nel rettangolo; altrimenti, {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Clona l'oggetto Rectangle.

**Returns:**
Clona oggetto.

### equals {#equals-java.lang.Object-}
Verifica se i rettangoli sono uguali, cioè hanno la stessa posizione e dimensioni.

### fromRect {#fromRect-java.awt.Rectangle-}
Inizializza un nuovo rettangolo dall'istanza fornita di System.Drawing.Rectangle.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Inizializza un nuovo rettangolo dall'istanza fornita di System.Drawing.Rectangle.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Calcola l'area del rettangolo.

**Returns:**
L'area del rettangolo come double, calcolata moltiplicando larghezza e altezza.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Restituisce un rettangolo vuoto

**Returns:**
nuovo oggetto Rectangle

### getHeight {#getHeight--}
```
public double getHeight()
```

Ottieni l'altezza del rettangolo.

**Returns:**
valore double

### getLLX {#getLLX--}
```
public double getLLX()
```

Ottiene la coordinata X dell'angolo inferiore sinistro.

**Returns:**
valore double

### getLLY {#getLLY--}
```
public double getLLY()
```

Ottiene la coordinata Y dell'angolo inferiore sinistro.

**Returns:**
valore double

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Inizializza un rettangolo banale, cioè un rettangolo con posizione e dimensione zero.

**Returns:**
nuovo oggetto Rectangle

### getURX {#getURX--}
```
public double getURX()
```

Ottiene la coordinata X dell'angolo superiore destro.

**Returns:**
valore double

### getURY {#getURY--}
```
public double getURY()
```

Ottiene la coordinata Y dell'angolo superiore destro.

**Returns:**
valore double

### getWidth {#getWidth--}
```
public double getWidth()
```

Ottiene la larghezza del rettangolo.

**Returns:**
valore double

### hashCode {#hashCode--}
```
public int hashCode()
```

Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valore di hash code per questo oggetto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Interseca due rettangoli.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Verifica se il rettangolo è vuoto.

**Returns:**
valore booleano

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Verifica che questo rettangolo includa un altro rettangolo intero. Cioè, l'altro rettangolo intero è all'interno di questo rettangolo. La differenza con il metodo IsIntersect è che IsIntersect sarà vero per rettangoli parzialmente intersecati, ma IsInclude sarà falso.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Determina se questo rettangolo interseca con un altro rettangolo.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Verifica se il rettangolo è un punto, cioè LLX è uguale a URX e LLY è uguale a URY.

**Returns:**
valore booleano

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Verifica se il rettangolo è triviale, cioè ha dimensioni e posizione zero.

**Returns:**
valore booleano

### join {#join-com.aspose.pdf.Rectangle-}
Unisce i rettangoli.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Sposta il rettangolo dei delta specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx |  | Valore dello spostamento lungo l'asse X. |
| dy |  | Valore dello spostamento lungo l'asse Y. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Verifica se i rettangoli sono quasi uguali, cioè hanno posizione e dimensioni quasi identiche (entro il delta).

### parse {#parse-java.lang.String-}
Prova a analizzare la stringa ed estrarre da essa i componenti del rettangolo llx, lly, urx, ury.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Ruota il rettangolo dell'angolo specificato.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Ruota il rettangolo dell'angolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle |  | Angolo di rotazione in gradi compreso tra 0 e 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Imposta la coordinata X dell'angolo inferiore sinistro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Imposta la coordinata Y dell'angolo inferiore sinistro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Imposta la coordinata X dell'angolo superiore destro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Imposta la coordinata Y dell'angolo superiore destro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Converte il rettangolo in un array di punti ("QuadPoints").

**Returns:**
Array di punti.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Converte il rettangolo in un'istanza di System.Drawing.Rectangle. Le posizioni e le dimensioni in virgola mobile vengono troncate.

**Returns:**
Risultato della conversione.

### toString {#toString--}
```
public String toString()
```

Ottiene la rappresentazione stringa del rettangolo.

**Returns:**
La stringa ha il formato llx,lly,urx,ury.
