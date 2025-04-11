---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Concatenare due file
type: docs
weight: 390
url: /it/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

Concatena due file.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo file da concatenare. |
| secInputFile | String | Secondo file da concatenare. |
| outputFile | String | File di output. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Concatena documenti.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | Document[] | Array di documenti sorgente. |
| dest | Document | Documento di destinazione. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [Document](../../../aspose.pdf/document/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Concatena file in un unico file.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Array di file da concatenare. |
| outputFile | String | Nome del file di output. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatena file

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Array di stream da concatenare. |
| outputStream | Stream | Stream dove il file risultante sarà memorizzato. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternati e riempie i posti vuoti con pagine vuote. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. Unendo i due documenti Pdf si otterrà il documento risultante con pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo file. |
| secInputFile | String | Secondo file. |
| blankPageFile | String | File PDF con pagina vuota. |
| outputFile | String | File risultante. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternati e riempie i posti vuoti con pagine vuote. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. Unendo i due documenti Pdf si otterrà il documento risultante con pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | Il primo Stream Pdf. |
| secInputStream | Stream | Il secondo Stream Pdf. |
| blankPageStream | Stream | Lo Stream Pdf con pagina vuota. |
| outputStream | Stream | Stream Pdf di output. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Concatena file e salva il risultato nell'oggetto HttpResponse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Array di file da concatenare. |
| response | HttpResponse | Oggetto di risposta. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Concatena file e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Array di stream che contengono file da concatenare. |
| response | HttpResponse | Oggetto di risposta. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)