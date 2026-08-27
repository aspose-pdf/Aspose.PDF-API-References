---
title: "TabStop"
linktitle: "TabStop"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una posizione di tabulazione personalizzata in un paragrafo."
type: docs
weight: 4840
url: /it/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Rappresenta una posizione di tabulazione personalizzata in un paragrafo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TabStop](#TabStop--) | Inizializza una nuova istanza della classe {@code TabStop}. |
| [TabStop](#TabStop-float-) | Inizializza una nuova istanza della classe {@code TabStop} con la posizione specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Ottiene o imposta un enum {@code AlignmentType} che indica il tipo di allineamento della tabulazione. |
| [getLeaderType](#getLeaderType--) | Ottiene o imposta un enum {@code TabLeaderType} che indica il tipo di leader della tabulazione. |
| [getPosition](#getPosition--) | Ottiene o imposta un valore float che indica la posizione della tabulazione. |
| [isReadOnly](#isReadOnly--) | Ottiene il valore che indica che questa istanza {@code TabStop} è già collegata a {@code TextFragment} ed è diventata di sola lettura |
| [setAlignmentType](#setAlignmentType-int-) | Ottiene o imposta un enum {@code AlignmentType} che indica il tipo di allineamento della tabulazione. |
| [setLeaderType](#setLeaderType-int-) | Ottiene o imposta un enum {@code TabLeaderType} che indica il tipo di leader della tabulazione. |
| [setPosition](#setPosition-float-) | Imposta un valore float che indica la posizione della tabulazione. |

### TabStop {#TabStop--}
```
public TabStop()
```

Inizializza una nuova istanza della classe {@code TabStop}.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Inizializza una nuova istanza della classe {@code TabStop} con la posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| posizione |  | La posizione del tab stop. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Ottiene o imposta un enum {@code AlignmentType} che indica il tipo di allineamento della tabulazione.

**Returns:**
TabAlignmentType elemento @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Ottiene o imposta un enum {@code TabLeaderType} che indica il tipo di leader della tabulazione.

**Returns:**
Elemento TabLeaderType @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Ottiene o imposta un valore float che indica la posizione della tabulazione.

**Returns:**
valore float

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ottiene il valore che indica che questa istanza {@code TabStop} è già collegata a {@code TextFragment} ed è diventata di sola lettura

**Returns:**
valore booleano

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Ottiene o imposta un enum {@code AlignmentType} che indica il tipo di allineamento della tabulazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | TabAlignmentType elemento @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Ottiene o imposta un enum {@code TabLeaderType} che indica il tipo di leader della tabulazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento TabLeaderType @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Imposta un valore float che indica la posizione della tabulazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |
