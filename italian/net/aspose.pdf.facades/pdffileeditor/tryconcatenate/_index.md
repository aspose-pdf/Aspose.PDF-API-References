---
title: "PdfFileEditor.TryConcatenate"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfFileEditor metodo. Concatena due file."
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

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
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
| src | Document[] | Array di documenti di origine. |
| dest | Document | Documento di destinazione. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Concatena i file in un unico file.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Array di file da concatenare. |
| outputFile | String | Nome del file di output. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatena file.

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Array di stream da concatenare. |
| outputStream | Stream | Stream dove sarà memorizzato il file risultato. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Unisce due documenti Pdf in un nuovo documento Pdf con le pagine in modo alternato e riempie gli spazi vuoti con pagine bianche. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo file. |
| secInputFile | String | Secondo file. |
| blankPageFile | String | File PDF con pagina vuota. |
| outputFile | String | File di risultato. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Unisce due documenti Pdf in un nuovo documento Pdf con le pagine in modo alternato e riempie gli spazi vuoti con pagine bianche. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | Il primo stream Pdf. |
| secInputStream | Stream | Il secondo stream Pdf. |
| blankPageStream | Stream | Lo stream Pdf con pagina vuota. |
| outputStream | Stream | Stream Pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryConcatenate è simile al metodo Concatenate, tranne che il metodo TryConcatenate non genera un'eccezione se l'operazione fallisce.

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

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


