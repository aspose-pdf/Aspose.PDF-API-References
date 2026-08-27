---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Fornisce metodi per i client COM per caricare un documento in Aspose.PDF. </p> <hr> <p> Utilizza la classe ComHelper per caricare un documento da un file o stream in un oggetto Document. </p>"
type: docs
weight: 760
url: /it/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> Fornisce metodi per i client COM per caricare un documento in Aspose.PDF. </p> <hr> <p> Utilizzare la classe ComHelper per caricare un documento da un file o stream in un oggetto Document in un'applicazione COM. La classe Document fornisce un costruttore predefinito per creare un nuovo documento e fornisce anche costruttori sovraccaricati per caricare un documento da un file o stream. Se si utilizza Aspose.Words da un'applicazione .NET, è possibile usare direttamente tutti i costruttori di Document, ma se si utilizza Aspose.PDF da un'applicazione COM, è disponibile solo il costruttore predefinito di Document. </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | Basta creare e restituire Document usando {@code filename}. Lo stesso di {@code Document(Stream)}. |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Apri un documento esistente da un file fornendo le opzioni di conversione necessarie per ottenere un documento pdf. |
| [openFile](#openFile-java.lang.String-java.lang.String-) | Inizializza e restituisce una nuova istanza della classe {@code Document} per lavorare con un documento crittografato. |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | Inizializza una nuova istanza della classe {@code Document} per lavorare con un documento crittografato. |
| [openStream](#openStream-java.io.InputStream-) | Inizializza e restituisce una nuova istanza di Document dal flusso {@code input}. |
| [openStream](#openStream-java.io.InputStream-boolean-) | Inizializza e restituisce una nuova istanza di Document dal flusso {@code input}. |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Apri e restituisci un documento esistente da un flusso fornendo la conversione necessaria per ottenere un documento pdf. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | Inizializza e restituisce una nuova istanza di Document dal flusso {@code input}. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | Inizializza e restituisce una nuova istanza di Document dal flusso {@code input}. |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
Basta creare e restituire Document usando {@code filename}. Lo stesso di {@code Document(Stream)}.

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
Apri un documento esistente da un file fornendo le opzioni di conversione necessarie per ottenere un documento pdf.

### openFile {#openFile-java.lang.String-java.lang.String-}
Inizializza e restituisce una nuova istanza della classe {@code Document} per lavorare con un documento crittografato.

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
Inizializza una nuova istanza della classe {@code Document} per lavorare con un documento crittografato.

### openStream {#openStream-java.io.InputStream-}
Inizializza e restituisce una nuova istanza di Document dal flusso {@code input}.

### openStream {#openStream-java.io.InputStream-boolean-}
Inizializza e restituisce una nuova istanza di Document dal flusso {@code input}.

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Apri e restituisci un documento esistente da un flusso fornendo la conversione necessaria per ottenere un documento pdf.

### openStream {#openStream-java.io.InputStream-java.lang.String-}
Inizializza e restituisce una nuova istanza di Document dal flusso {@code input}.

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
Inizializza e restituisce una nuova istanza di Document dal flusso {@code input}.
