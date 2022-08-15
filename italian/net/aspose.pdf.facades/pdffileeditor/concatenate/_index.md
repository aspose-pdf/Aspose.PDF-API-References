---
title: Concatenate
second_title: Aspose.PDF per .NET API Reference
description: Concatena due file.
type: docs
weight: 290
url: /it/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_5}

Concatena due file.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo file da concatenare. |
| secInputFile | String | Secondo file da concatenare. |
| outputFile | String | File di uscita. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Concatena due file.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | Flusso del primo file. |
| secInputStream | Stream | Flusso del secondo file. |
| outputStream | Stream | Stream in cui verrà archiviato il file dei risultati. |

### Valore di ritorno

Vero se l'operazione è riuscita.

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Concatena i documenti.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | Document[] | Matrice di documenti di origine. |
| dest | Document | Documento di destinazione. |

### Valore di ritorno

Vero se la concatenazione ha esito positivo.

### Guarda anche

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_7}

Concatena i file in un unico file.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Matrice di file da concatenare. |
| outputFile | String | Nome del file di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Concatena i file

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Matrice di flussi da concatenare. |
| outputStream | Stream | Stream in cui verrà archiviato il file dei risultati. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_6}

Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie gli spazi vuoti con pagine vuote. es: il documento1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo fascicolo. |
| secInputFile | String | Secondo fascicolo. |
| blankPageFile | String | File PDF con pagina vuota. |
| outputFile | String | File dei risultati. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie gli spazi vuoti con pagine vuote. es: il documento1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | Il primo Stream Pdf. |
| secInputStream | Stream | Il secondo Stream Pdf. |
| blankPageStream | Stream | Il flusso Pdf con pagina vuota. |
| outputStream | Stream | Flusso Pdf di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Concatenate(string[], HttpResponse) {#concatenate_8}

Concatena i file e salva il risultato nell'oggetto HttpResposnse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Matrice di file da concatenare. |
| response | HttpResponse | Oggetto risposta. |

### Valore di ritorno

true se la concatenazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Concatena i file e memorizza i risultati nell'oggetto HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Streams array che contiene i file da concatenare. |
| response | HttpResponse | Oggetto risposta/ |

### Valore di ritorno

true se l'operazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
