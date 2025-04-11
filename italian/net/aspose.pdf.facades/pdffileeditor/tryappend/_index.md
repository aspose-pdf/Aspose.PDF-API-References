---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Aggiunge pagine scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo startPage a endPage
type: docs
weight: 380
url: /it/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Aggiunge pagine, che sono scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo startPage a endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream Pdf di input. |
| portStreams | Stream[] | Documenti da cui copiare le pagine. |
| startPage | Int32 | La pagina inizia nei documenti portStreams. |
| endPage | Int32 | La pagina termina nei documenti portStreams. |
| outputStream | Stream | Stream Pdf di output. |

### Return Value

True per successo, o false.

## Remarks

Il metodo TryAppend è simile al metodo Append, tranne per il fatto che il metodo TryAppend non genera un'eccezione se l'operazione fallisce.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Aggiunge pagine, che sono scelte dai documenti portFiles. Il documento risultante include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo startPage a endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | File Pdf di input. |
| portFiles | String[] | Documenti da cui copiare le pagine. |
| startPage | Int32 | La pagina inizia nei documenti portFiles. |
| endPage | Int32 | La pagina termina nei documenti portFiles. |
| outputFile | String | Documento Pdf di output. |

### Return Value

true se l'operazione è completata con successo; altrimenti, false.

## Remarks

Il metodo TryAppend è simile al metodo Append, tranne per il fatto che il metodo TryAppend non genera un'eccezione se l'operazione fallisce.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Aggiunge documenti al documento sorgente e salva il risultato nell'oggetto di risposta.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream che contiene il documento sorgente. |
| portStreams | Stream[] | Array di stream con documenti da aggiungere. |
| startPage | Int32 | Pagina di inizio della pagina aggiunta. |
| endPage | Int32 | Pagina finale delle pagine aggiunte. |
| response | HttpResponse | Oggetto di risposta in cui il documento sarà salvato. |

### Return Value

true se l'operazione è completata con successo; altrimenti, false.

## Remarks

Il metodo TryAppend è simile al metodo Append, tranne per il fatto che il metodo TryAppend non genera un'eccezione se l'operazione fallisce.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Aggiunge documenti al documento sorgente e salva il risultato nell'oggetto HttpResponse.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Nome del file contenente il documento sorgente. |
| portFiles | String[] | Array di nomi di file contenenti documenti aggiunti. |
| startPage | Int32 | Pagina di inizio delle pagine aggiunte. |
| endPage | Int32 | Pagina finale delle pagine aggiunte. |
| response | HttpResponse | Oggetto di risposta in cui il documento sarà salvato. |

### Return Value

true se l'operazione è completata con successo; altrimenti, false.

## Remarks

Il metodo TryAppend è simile al metodo Append, tranne per il fatto che il metodo TryAppend non genera un'eccezione se l'operazione fallisce.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)