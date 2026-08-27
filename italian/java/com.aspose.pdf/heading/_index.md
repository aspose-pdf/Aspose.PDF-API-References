---
title: "Intestazione"
linktitle: "Intestazione"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'intestazione."
type: docs
weight: 1890
url: /it/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Rappresenta l'intestazione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Heading](#Heading--) | Solo per uso interno |
| [Heading](#Heading-int-) | Inizializza una nuova istanza della classe Cell. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clona l'intestazione con tutti i segmenti. |
| [deepClone](#deepClone--) | Clona l'intestazione. |
| [getDestinationPage](#getDestinationPage--) | Restituisce la pagina di destinazione. |
| [getLevel](#getLevel--) | Restituisce il livello. |
| [getStartNumber](#getStartNumber--) | Restituisce il numero iniziale dell'intestazione. |
| [getStyle](#getStyle--) | Restituisce o imposta lo stile. |
| [getTocPage](#getTocPage--) | Restituisce la pagina che contiene questa intestazione. |
| [getTop](#getTop--) | Restituisce il valore Y superiore di queste intestazioni (per uso interno). |
| [getUserLabel](#getUserLabel--) | Restituisce o imposta l'etichetta utente. |
| [isAutoSequence](#isAutoSequence--) | Restituisce se l'intestazione deve essere numerata automaticamente. |
| [isInList](#isInList--) | Restituisce se l'intestazione deve essere nella lista TOC. |
| [setAutoSequence](#setAutoSequence-boolean-) | Imposta se l'intestazione deve essere numerata automaticamente. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | Imposta la pagina di destinazione. |
| [setInList](#setInList-boolean-) | Imposta se l'intestazione deve essere nella lista TOC. |
| [setLevel](#setLevel-int-) | imposta il livello. |
| [setStartNumber](#setStartNumber-int-) | Ottiene il numero di avvio dell'intestazione. Valore: The startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | imposta o imposta lo stile. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Imposta la pagina che contiene questa intestazione. |
| [setTop](#setTop-double-) | imposta il valore Y superiore di queste intestazioni (per uso interno). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Restituisce o imposta l'etichetta utente. |

### Heading {#Heading--}
```
public Heading()
```

Solo per uso interno

### Heading {#Heading-int-}
```
public Heading(int level)
```

Inizializza una nuova istanza della classe Cell.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| level |  | Il livello delle intestazioni. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clona l'intestazione con tutti i segmenti.

**Returns:**
L'oggetto clonato

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona l'intestazione.

**Returns:**
L'oggetto clonato

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Restituisce la pagina di destinazione.

**Returns:**
La pagina di destinazione.

### getLevel {#getLevel--}
```
public int getLevel()
```

Restituisce il livello.

**Returns:**
Il livello dell'intestazione.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Restituisce il numero iniziale dell'intestazione.

**Returns:**
Valore: The startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Restituisce o imposta lo stile.

**Returns:**
Lo stile dell'intestazione.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Restituisce la pagina che contiene questa intestazione.

**Returns:**
La pagina.

### getTop {#getTop--}
```
public double getTop()
```

Restituisce il valore Y superiore di queste intestazioni (per uso interno).

**Returns:**
Il valore Y superiore

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Restituisce o imposta l'etichetta utente.

**Returns:**
Oggetto TextSegment

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Restituisce se l'intestazione deve essere numerata automaticamente.

**Returns:**
Il IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Restituisce se l'intestazione deve essere nella lista TOC.

**Returns:**
Il IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

Imposta se l'intestazione deve essere numerata automaticamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Il IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
Imposta la pagina di destinazione.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

Imposta se l'intestazione deve essere nella lista TOC.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Il IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

imposta il livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Il livello dell'intestazione. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Ottiene il numero di avvio dell'intestazione. Valore: The startNumber.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Il startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
imposta o imposta lo stile.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Imposta la pagina che contiene questa intestazione.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

imposta il valore Y superiore di queste intestazioni (per uso interno).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Il valore Y superiore |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Restituisce o imposta l'etichetta utente.
