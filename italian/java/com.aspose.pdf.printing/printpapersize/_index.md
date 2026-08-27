---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Specifica le dimensioni di un foglio di carta."
type: docs
weight: 100
url: /it/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

Specifica le dimensioni di un foglio di carta.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | Inizializza una nuova istanza della classe PaperSize. |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | Inizializza una nuova istanza della classe PaperSize. |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | Inizializza una nuova istanza della classe PaperSize. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeight](#getHeight--) | Ottiene o imposta l'altezza della carta, in centesimi di pollice. |
| [getKind](#getKind--) | Restituisce il tipo di carta. |
| [getPaperName](#getPaperName--) | Ottiene o imposta il nome del tipo di carta. |
| [getRawKind](#getRawKind--) | Ottiene o imposta un intero che rappresenta uno dei valori di PaperSize o un valore personalizzato. |
| [getWidth](#getWidth--) | Ottiene o imposta la larghezza della carta, in centesimi di pollice. |
| [setHeight](#setHeight-int-) | Ottiene o imposta l'altezza della carta, in centesimi di pollice. |
| [setPaperName](#setPaperName-java.lang.String-) | Restituisce il nome del tipo di carta. |
| [setWidth](#setWidth-int-) | Imposta la larghezza della carta, in centesimi di pollice. |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Converte {@link PaperSize} in System.Drawing.Printing.PaperSize specifico per Windows. |
| [toString](#toString--) | Restituisce il nome di questa istanza. |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

Inizializza una nuova istanza della classe PaperSize.

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
Inizializza una nuova istanza della classe PaperSize.

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
Inizializza una nuova istanza della classe PaperSize.

### getHeight {#getHeight--}
```
public int getHeight()
```

Ottiene o imposta l'altezza della carta, in centesimi di pollice.

**Returns:**
valore int

### getKind {#getKind--}
```
public int getKind()
```

Restituisce il tipo di carta.

**Returns:**
int value @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

Ottiene o imposta il nome del tipo di carta.

**Returns:**
valore String

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

Ottiene o imposta un intero che rappresenta uno dei valori di PaperSize o un valore personalizzato.

**Returns:**
valore int

### getWidth {#getWidth--}
```
public int getWidth()
```

Ottiene o imposta la larghezza della carta, in centesimi di pollice.

**Returns:**
valore int

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

Ottiene o imposta l'altezza della carta, in centesimi di pollice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPaperName {#setPaperName-java.lang.String-}
Restituisce il nome del tipo di carta.

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

Imposta la larghezza della carta, in centesimi di pollice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Converte {@link PaperSize} in System.Drawing.Printing.PaperSize specifico per Windows.

### toString {#toString--}
```
public String toString()
```

Restituisce il nome di questa istanza.

**Returns:**
valore String
