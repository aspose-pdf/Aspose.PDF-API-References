---
title: MakeNUp
second_title: Aspose.PDF per .NET API Reference
description: Crea un documento N su 1 dal firstInputFile a outputFile.
type: docs
weight: 340
url: /it/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(string, string, int, int) {#makenup_8}

Crea un documento N su 1 dal firstInputFile a outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso e il nome del file pdf. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

boolean - Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Crea un documento N su 1 dal flusso di input e salva il risultato nel flusso di output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Input flusso pdf. |
| outputStream | Stream | Output flusso pdf. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

boolean - Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Crea un documento N su 1 dal primo flusso di input al flusso di output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Input flusso pdf. |
| outputStream | Stream | Output flusso pdf. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Crea un documento N-Up dai due file PDF di input in outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina proviene dal primo file di input e un'altra dal secondo file di input. Le due pagine sono impilate orizzontalmente.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | primo file di input. |
| secondInputFile | String | secondo file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |

### Valore di ritorno

boolean - Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Crea un documento N-Up dai due flussi PDF di input a outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | primo flusso di input. |
| secondInputStream | Stream | secondo flusso di input. |
| outputStream | Stream | Output flusso pdf. |

### Valore di ritorno

boolean - Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_11}

Crea un documento N-Up dai file PDF multi input a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione con le pagine nei file di input con lo stesso numero di pagina. Le pagine multiple impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Inserisci i file Pdf. |
| outputFile | String | Percorso e nome del file pdf di output. |
| isSidewise | Boolean | Accatastati, vero per orizzontalmente e falso per verticalmente. |

### Valore di ritorno

boolean - Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_5}

Crea un documento N su 1 dai flussi PDF multi input a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione con le pagine nei flussi di input con lo stesso numero di pagina. Le pagine multiple impilate orizzontalmente se isSidewise è vero e impilate verticalmente se isSidewise è false.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStreams | Stream[] | Input di flussi Pdf. |
| outputStream | Stream | Output flusso pdf. |
| isSidewise | Boolean | Accatastati, vero per orizzontalmente e falso per verticalmente. |

### Valore di ritorno

boolean - Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_9}

Crea un documento N su 1 dal file di input a outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso e il nome del file pdf. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

boolean - Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, PageSize, HttpResponse) {#makenup}

Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del documento di origine. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | Dimensioni della pagina nel file dei risultati. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, PageSize, HttpResponse) {#makenup_6}

Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di origine. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | Dimensioni della pagina nel file dei risultati. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, HttpResponse) {#makenup_7}

Crea un documento N-up e memorizza il risultato in HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Nome del file di origine. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, HttpResponse) {#makenup_1}

Crea un documento N-up e memorizza il risultato in HttpResponse.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del documento di input. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| response | HttpResponse | HttpResponse dove verrà archiviato il risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
