---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Implementa il recupero di uno stream di output dalla memoria. Puoi usarlo, ad esempio, quando non vuoi che l'output associato (come un file di log) venga scritto su disco ma desideri comunque."
type: docs
weight: 4880
url: /it/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Implementa il recupero di uno stream di output dalla memoria. Puoi usarlo, ad esempio, quando non vuoi che l'output associato (come un file di log) venga scritto su disco ma desideri leggerlo successivamente dalla memoria.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Crea una nuova istanza. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close](#close--) | Elimina l'istanza. @throws IOException L'eccezione IOException può essere sollevata se si verifica un errore di I/O. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Restituisce lo stream da cui leggere. Senza cercare un file nelle sottodirectory. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Restituisce lo stream da cui leggere. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Restituisce lo stream su cui scrivere. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Crea una nuova istanza.

### close {#close--}
```
public void close() throws IOException
```

Elimina l'istanza. @throws IOException L'eccezione IOException può essere sollevata se si verifica un errore di I/O.

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Restituisce lo stream da cui leggere. Senza cercare un file nelle sottodirectory.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Restituisce lo stream da cui leggere.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Restituisce lo stream su cui scrivere.
