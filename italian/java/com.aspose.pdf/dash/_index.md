---
title: "Trattino"
linktitle: "Trattino"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta il modello di tratteggio della linea."
type: docs
weight: 910
url: /it/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Classe che rappresenta il modello di tratteggio della linea.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Dash](#Dash-int:A-) | Costruttore per Dash. Definisce un modello di trattini e spazi che deve essere usato per disegnare un bordo tratteggiato. |
| [Dash](#Dash-int-int-) | Costruttore per Dash. Definisce un bordo tratteggiato con il trattino e lo spazio specificati, che rimangono invariati per l'intero bordo tratteggiato. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOff](#getOff--) | Ottiene o imposta la lunghezza del primo spazio tra i trattini. |
| [getOn](#getOn--) | Ottiene o imposta la lunghezza del primo trattino. |
| [getPattern](#getPattern--) | Ottiene l'array di trattini che definisce un modello di trattini e spazi da utilizzare per disegnare un bordo tratteggiato. |
| [setOff](#setOff-int-) | Ottiene o imposta la lunghezza del primo spazio tra i trattini. |
| [setOn](#setOn-int-) | Ottiene o imposta la lunghezza del primo trattino. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Costruttore per Dash. Definisce un modello di trattini e spazi che deve essere usato per disegnare un bordo tratteggiato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modello |  | Un array di trattini (di almeno due valori) che definisce un modello di trattini e spazi da utilizzare per disegnare un bordo tratteggiato. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Costruttore per Dash. Definisce un bordo tratteggiato con il trattino e lo spazio specificati, che rimangono invariati per l'intero bordo tratteggiato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| acceso |  | Lunghezza del trattino. |
| spento |  | Lunghezza dello spazio. |

### getOff {#getOff--}
```
public final int getOff()
```

Ottiene o imposta la lunghezza del primo spazio tra i trattini.

**Returns:**
valore int

### getOn {#getOn--}
```
public final int getOn()
```

Ottiene o imposta la lunghezza del primo trattino.

**Returns:**
valore int

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Ottiene l'array di trattini che definisce un modello di trattini e spazi da utilizzare per disegnare un bordo tratteggiato.

**Returns:**
array di int

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Ottiene o imposta la lunghezza del primo spazio tra i trattini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

Ottiene o imposta la lunghezza del primo trattino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
