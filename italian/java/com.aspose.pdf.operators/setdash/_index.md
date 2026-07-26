---
title: "SetDash"
linktitle: "SetDash"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore d (imposta il modello di tratteggio della linea)."
type: docs
weight: 610
url: /it/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

Classe che rappresenta l'operatore d (imposta il modello di tratteggio della linea).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Crea l'operatore di impostazione del modello di trattini. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getPattern](#getPattern--) | Modello di trattini. Gli elementi dell'array devono essere numeri che specificano le lunghezze dei trattini e degli spazi alternati. Nel caso di un array a un solo elemento, le lunghezze di trattino e spazio sono uguali. |
| [getPhase](#getPhase--) | Fase dash. Prima di iniziare a tracciare un percorso, l'array dash deve essere ciclicamente attraversato, sommando le lunghezze dei tratti e degli spazi. Quando la lunghezza accumulata è uguale al valore specificato dalla fase dash, l'operazione di tracciatura del percorso inizia, e l'array dash viene usato ciclicamente da quel punto in poi. |
| [setPattern](#setPattern-int:A-) | Modello di trattini. Gli elementi dell'array devono essere numeri che specificano le lunghezze dei trattini e degli spazi alternati. Nel caso di un array a un solo elemento, le lunghezze di trattino e spazio sono uguali. |
| [setPhase](#setPhase-int-) | Fase dash. Prima di iniziare a tracciare un percorso, l'array dash deve essere ciclicamente attraversato, sommando le lunghezze dei tratti e degli spazi. Quando la lunghezza accumulata è uguale al valore specificato dalla fase dash, l'operazione di tracciatura del percorso inizia, e l'array dash viene usato ciclicamente da quel punto in poi. |
| [toCommand](#toCommand--) | Solo per uso interno! |
| [toString](#toString--) | Restituisce la rappresentazione stringa dell'operatore. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Crea l'operatore di impostazione del modello di trattini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modello |  | Array che definisce il modello dash. |
| fase |  | Fase dash. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Modello di trattini. Gli elementi dell'array devono essere numeri che specificano le lunghezze dei trattini e degli spazi alternati. Nel caso di un array a un solo elemento, le lunghezze di trattino e spazio sono uguali.

**Returns:**
array di int

### getPhase {#getPhase--}
```
public int getPhase()
```

Fase dash. Prima di iniziare a tracciare un percorso, l'array dash deve essere ciclicamente attraversato, sommando le lunghezze dei tratti e degli spazi. Quando la lunghezza accumulata è uguale al valore specificato dalla fase dash, l'operazione di tracciatura del percorso inizia, e l'array dash viene usato ciclicamente da quel punto in poi.

**Returns:**
valore int

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Modello di trattini. Gli elementi dell'array devono essere numeri che specificano le lunghezze dei trattini e degli spazi alternati. Nel caso di un array a un solo elemento, le lunghezze di trattino e spazio sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | array di int |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Fase dash. Prima di iniziare a tracciare un percorso, l'array dash deve essere ciclicamente attraversato, sommando le lunghezze dei tratti e degli spazi. Quando la lunghezza accumulata è uguale al valore specificato dalla fase dash, l'operazione di tracciatura del percorso inizia, e l'array dash viene usato ciclicamente da quel punto in poi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Solo per uso interno!

**Returns:**
ICommand valore oggetto ICommand

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione stringa dell'operatore.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
