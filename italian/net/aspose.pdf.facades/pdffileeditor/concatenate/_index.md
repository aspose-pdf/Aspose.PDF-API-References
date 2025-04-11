---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Concatenare due file
type: docs
weight: 260
url: /it/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

Concatenare due file.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo file da concatenare. |
| secInputFile | String | Secondo file da concatenare. |
| outputFile | String | File di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Concatenare due file.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | Stream del primo file. |
| secInputStream | Stream | Stream del secondo file. |
| outputStream | Stream | Stream dove il file risultante sarà memorizzato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

Vero se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Concatenare documenti.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | Document[] | Array di documenti sorgente. |
| dest | Document | Documento di destinazione. |

### Valore di ritorno

Vero se la concatenazione ha avuto successo.

### Vedi anche

* classe [Document](../../../aspose.pdf/document/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

Concatenare file in un unico file.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Array di file da concatenare. |
| outputFile | String | Nome del file di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Concatenare file

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Array di stream da concatenare. |
| outputStream | Stream | Stream dove il file risultante sarà memorizzato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternati e riempie i posti vuoti con pagine vuote. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. Unendo i due documenti Pdf si otterrà il documento risultante con pagine: p1, p1', p2, p2', p3, p3', p4, pagina vuota, p5, pagina vuota.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo file. |
| secInputFile | String | Secondo file. |
| blankPageFile | String | File PDF con pagina vuota. |
| outputFile | String | File risultante. |

### Valore di ritorno

Vero se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternati e riempie i posti vuoti con pagine vuote. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. Unendo i due documenti Pdf si otterrà il documento risultante con pagine: p1, p1', p2, p2', p3, p3', p4, pagina vuota, p5, pagina vuota.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | Il primo Stream Pdf. |
| secInputStream | Stream | Il secondo Stream Pdf. |
| blankPageStream | Stream | Lo Stream Pdf con pagina vuota. |
| outputStream | Stream | Stream Pdf di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## Concatenate(string[], HttpResponse) {#concatenate_8}

Concatenare file e salvare il risultato nell'oggetto HttpResponse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Array di file da concatenare. |
| response | HttpResponse | Oggetto di risposta. |

### Valore di ritorno

vero se la concatenazione ha avuto successo.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Concatenare file e memorizzare il risultato nell'oggetto HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Array di stream che contengono file da concatenare. |
| response | HttpResponse | Oggetto di risposta. |

### Valore di ritorno

vero se l'operazione è riuscita.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)