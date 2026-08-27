---
title: "PdfFileEditor.TryInsert"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Inserisce pagine da un altro file nel file Pdf di input"
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
| insertLocation | Int32 | Inserisci la posizione nel file di input. |
| portFile | String | Pagine dal file Pdf. |
| pageNumber | Int32[] | Il numero di pagina del file portato in portFile. |
| outputFile | String | File Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Il metodo TryInsert è simile al metodo Insert, tranne che il metodo TryInsert non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
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
| insertLocation | Int32 | Inserisci la posizione nel file di input. |
| portStream | Stream | Flusso del file Pdf per le pagine. |
| pageNumber | Int32[] | Il numero di pagina del file portato in portFile. |
| outputStream | Stream | Flusso di output. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryInsert è simile al metodo Insert, tranne che il metodo TryInsert non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


