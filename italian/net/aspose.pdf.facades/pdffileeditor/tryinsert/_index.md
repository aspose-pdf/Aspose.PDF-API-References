---
title: TryInsert
second_title: Aspose.PDF per .NET API Reference
description: Inserisce le pagine da un altro file nel file Pdf di input.
type: docs
weight: 450
url: /it/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_2}

Inserisce le pagine da un altro file nel file Pdf di input.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il file Pdf. |
| insertLocation | Int32 | Inserisci la posizione nel file di input. |
| portFile | String | Pagine dal file Pdf. |
| pageNumber | Int32[] | Il numero di pagina del portFile portato. |
| outputFile | String | Uscita file Pdf. |

### Valore di ritorno

Vero per il successo o falso.

### Osservazioni

Il metodo TryInsert è come il metodo Insert, tranne per il fatto che il metodo TryInsert non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Inserisce le pagine da un altro file nel file Pdf di input.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso di input del file Pdf. |
| insertLocation | Int32 | Inserisci la posizione nel file di input. |
| portStream | Stream | Flusso di file Pdf per le pagine. |
| pageNumber | Int32[] | Il numero di pagina del portFile portato. |
| outputStream | Stream | Flusso di uscita. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryInsert è come il metodo Insert, tranne per il fatto che il metodo TryInsert non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Inserisce il contenuto del file nel file di origine e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Nome del file di origine. |
| insertLocation | Int32 | Numero di pagina in cui verrà inserito il secondo file. |
| portFile | String | Percorso del file che verrà inserito. |
| pageNumber | Int32[] | Matrice di numeri di pagina nel file sorgente che verrà inserita. |
| response | HttpResponse | Oggetto di risposta in cui verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryInsert è come il metodo Insert, tranne per il fatto che il metodo TryInsert non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Inserisce il documento in un altro documento e memorizza il risultato nell'oggetto risposta.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Trasmetti in streaming con il documento di origine |
| insertLocation | Int32 | Posizione in cui verrà inserito l'altro documento. |
| portStream | Stream | Documento da inserire. |
| pageNumber | Int32[] | Matrice di numeri di pagina nel secondo documento che verrà inserito. |
| response | HttpResponse | Oggetto di risposta in cui verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryInsert è come il metodo Insert, tranne per il fatto che il metodo TryInsert non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
