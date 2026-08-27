---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta il timbro del numero di pagina ed è usato per numerare le pagine."
type: docs
weight: 3440
url: /it/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Rappresenta il timbro del numero di pagina ed è usato per numerare le pagine.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | Inizializza una nuova istanza della classe {@code PageNumberStamp}. Il formato è impostato su "#". |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Inizializza una nuova istanza della classe {@code PageNumberStamp}. Il formato è impostato su "#". |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | Inizializza una nuova istanza della classe {@code PageNumberStamp}. Il formato è impostato su "#". |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat](#getFormat--) | Ottiene il valore String per la marcatura dei numeri di pagina. Il valore deve includere il carattere '#' che viene sostituito con il numero di pagina durante la marcatura. |
| [getNumberingStyle](#getNumberingStyle--) | Stile di numerazione utilizzato da questo timbro. |
| [getStartingNumber](#getStartingNumber--) | Ottiene il valore del numero della pagina iniziale. Le altre pagine saranno numerate a partire da questo valore. |
| [put](#put-com.aspose.pdf.Page-) | Aggiunge il numero di pagina. |
| [setFormat](#setFormat-java.lang.String-) | Imposta il valore String per la marcatura dei numeri di pagina. Il valore deve includere il carattere '#' che viene sostituito con il numero di pagina durante il processo di marcatura. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Stile di numerazione utilizzato da questo timbro. |
| [setStartingNumber](#setStartingNumber-int-) | Imposta il valore del numero della pagina iniziale. Le altre pagine saranno numerate a partire da questo valore. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

Inizializza una nuova istanza della classe {@code PageNumberStamp}. Il formato è impostato su "#".

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
Inizializza una nuova istanza della classe {@code PageNumberStamp}. Il formato è impostato su "#".

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
Inizializza una nuova istanza della classe {@code PageNumberStamp}. Il formato è impostato su "#".

### getFormat {#getFormat--}
```
public String getFormat()
```

Ottiene il valore String per la marcatura dei numeri di pagina. Il valore deve includere il carattere '#' che viene sostituito con il numero di pagina durante la marcatura.

**Returns:**
valore String

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Stile di numerazione utilizzato da questo timbro.

**Returns:**
Valore NumberingStyle @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Ottiene il valore del numero della pagina iniziale. Le altre pagine saranno numerate a partire da questo valore.

**Returns:**
valore int

### put {#put-com.aspose.pdf.Page-}
Aggiunge il numero di pagina.

### setFormat {#setFormat-java.lang.String-}
Imposta il valore String per la marcatura dei numeri di pagina. Il valore deve includere il carattere '#' che viene sostituito con il numero di pagina durante il processo di marcatura.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Stile di numerazione utilizzato da questo timbro.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Imposta il valore del numero della pagina iniziale. Le altre pagine saranno numerate a partire da questo valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
