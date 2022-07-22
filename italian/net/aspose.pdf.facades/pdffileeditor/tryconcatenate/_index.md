---
title: TryConcatenate
second_title: Aspose.PDF per .NET API Reference
description: Concatena due file.
type: docs
weight: 420
url: /it/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_4}

Concatena due file.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo file da concatenare. |
| secInputFile | String | Secondo file da concatenare. |
| outputFile | String | File di uscita. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryConcatenate è come il metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Concatena i documenti.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | Document[] | Matrice di documenti di origine. |
| dest | Document | Documento di destinazione. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryConcatenate è come il metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_6}

Concatena i file in un unico file.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Matrice di file da concatenare. |
| outputFile | String | Nome del file di output. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryConcatenate è come il metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatena i file

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Matrice di flussi da concatenare. |
| outputStream | Stream | Stream in cui verrà archiviato il file dei risultati. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryConcatenate è come il metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_5}

Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie gli spazi vuoti con pagine vuote. es: il documento1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | Primo fascicolo. |
| secInputFile | String | Secondo fascicolo. |
| blankPageFile | String | File PDF con pagina vuota. |
| outputFile | String | File dei risultati. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryConcatenate è come il metodo Concatenate , tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie gli spazi vuoti con pagine vuote. es: il documento1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | Il primo Stream Pdf. |
| secInputStream | Stream | Il secondo Stream Pdf. |
| blankPageStream | Stream | Il flusso Pdf con pagina vuota. |
| outputStream | Stream | Flusso Pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryConcatenate è come il metodo Concatenate , tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Concatena i file e salva il risultato nell'oggetto HttpResposnse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Matrice di file da concatenare. |
| response | HttpResponse | Oggetto risposta. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryConcatenate è come il metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Concatena i file e memorizza i risultati nell'oggetto HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream[] | Streams array che contiene i file da concatenare. |
| response | HttpResponse | Oggetto risposta/ |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryConcatenate è come il metodo Concatenate, tranne per il fatto che il metodo TryConcatenate non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
