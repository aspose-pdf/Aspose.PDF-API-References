---
title: "FileParams"
linktitle: "FileParams"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Definisce un dizionario di parametri di file incorporato che deve contenere informazioni aggiuntive specifiche del file."
type: docs
weight: 1490
url: /it/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Definisce un dizionario di parametri di file incorporato che deve contenere informazioni aggiuntive specifiche del file.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | Costruttore per la classe FileParams. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCheckSum](#getCheckSum--) | Una stringa di 16 byte che è il checksum dei byte del file incorporato non compresso. Il checksum è calcolato applicando l'algoritmo standard di digest MD5 ai byte del flusso del file incorporato. |
| [getCreationDate](#getCreationDate--) | Ottieni la data e l'ora in cui il file incorporato è stato creato. |
| [getModDate](#getModDate--) | Ottieni la data e l'ora in cui il file incorporato è stato modificato l'ultima volta. |
| [getSize](#getSize--) | La dimensione del file incorporato non compresso, in byte. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Imposta la data e l'ora in cui il file incorporato è stato creato. |
| [setModDate](#setModDate-java.util.Date-) | Imposta la data e l'ora in cui il file incorporato è stato modificato l'ultima volta. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
Costruttore per la classe FileParams.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

Una stringa di 16 byte che è il checksum dei byte del file incorporato non compresso. Il checksum è calcolato applicando l'algoritmo standard di digest MD5 ai byte del flusso del file incorporato.

**Returns:**
valore String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Ottieni la data e l'ora in cui il file incorporato è stato creato.

**Returns:**
Oggetto Date

### getModDate {#getModDate--}
```
public Date getModDate()
```

Ottieni la data e l'ora in cui il file incorporato è stato modificato l'ultima volta.

**Returns:**
Oggetto Date

### getSize {#getSize--}
```
public int getSize()
```

La dimensione del file incorporato non compresso, in byte.

**Returns:**
valore int

### setCreationDate {#setCreationDate-java.util.Date-}
Imposta la data e l'ora in cui il file incorporato è stato creato.

### setModDate {#setModDate-java.util.Date-}
Imposta la data e l'ora in cui il file incorporato è stato modificato l'ultima volta.
