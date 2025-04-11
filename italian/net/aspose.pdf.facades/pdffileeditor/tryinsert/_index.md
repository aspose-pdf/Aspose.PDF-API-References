---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Inserisce pagine da un altro file nel file Pdf di input
type: docs
weight: 420
url: /it/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Inserisce pagine da un altro file nel file Pdf di input.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf di input. |
| insertLocation | Int32 | Posizione di inserimento nel file di input. |
| portFile | String | Pagine dal file Pdf. |
| pageNumber | Int32[] | Il numero di pagina del file portato in portFile. |
| outputFile | String | File Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Il metodo TryInsert è simile al metodo Insert, tranne per il fatto che il metodo TryInsert non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Inserisce pagine da un altro file nel file Pdf di input.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream di input del file Pdf. |
| insertLocation | Int32 | Posizione di inserimento nel file di input. |
| portStream | Stream | Stream del file Pdf per le pagine. |
| pageNumber | Int32[] | Il numero di pagina del file portato in portFile. |
| outputStream | Stream | Stream di output. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryInsert è simile al metodo Insert, tranne per il fatto che il metodo TryInsert non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Inserisce il contenuto del file nel file sorgente e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Nome del file sorgente. |
| insertLocation | Int32 | Numero di pagina in cui verrà inserito il secondo file. |
| portFile | String | Percorso del file che verrà inserito. |
| pageNumber | Int32[] | Array di numeri di pagina nel file sorgente che verranno inseriti. |
| response | HttpResponse | Oggetto di risposta in cui verrà memorizzato il risultato. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryInsert è simile al metodo Insert, tranne per il fatto che il metodo TryInsert non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Inserisce il documento in un altro documento e memorizza il risultato nell'oggetto di risposta.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream con il documento sorgente |
| insertLocation | Int32 | Posizione in cui verrà inserito l'altro documento. |
| portStream | Stream | Documento da inserire. |
| pageNumber | Int32[] | Array di numeri di pagina nel secondo documento che verranno inseriti. |
| response | HttpResponse | Oggetto di risposta in cui verrà memorizzato il risultato. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryInsert è simile al metodo Insert, tranne per il fatto che il metodo TryInsert non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)