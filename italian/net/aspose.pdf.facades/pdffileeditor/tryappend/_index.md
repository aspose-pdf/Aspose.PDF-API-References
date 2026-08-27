---
title: "PdfFileEditor.TryAppend"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Aggiunge pagine scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo startPage a endPage."
type: docs
weight: 380
url: /it/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Aggiunge le pagine, scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti di portStreams nell'intervallo da startPage a endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso Pdf di input. |
| portStreams | Stream[] | Documenti da cui copiare le pagine. |
| startPage | Int32 | La pagina inizia nei documenti portStreams. |
| endPage | Int32 | La pagina termina nei documenti portStreams. |
| outputStream | Stream | Flusso Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Il metodo TryAppend è simile al metodo Append, tranne che il metodo TryAppend non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Aggiunge le pagine, scelte dai documenti di portFiles. Il documento risultante include firstInputFile e tutte le pagine dei documenti di portFiles nell'intervallo da startPage a endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf di input. |
| portFiles | String[] | Documenti da cui copiare le pagine. |
| startPage | Int32 | La pagina inizia nei documenti portFiles. |
| endPage | Int32 | La pagina termina nei documenti portFiles. |
| outputFile | String | Documento Pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryAppend è simile al metodo Append, tranne che il metodo TryAppend non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


