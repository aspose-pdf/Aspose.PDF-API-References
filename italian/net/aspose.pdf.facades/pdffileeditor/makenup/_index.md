---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Crea un documento NUp dai due flussi PDF di input a outputStream
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Crea un documento N-Up dal firstInputFile a outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Crea un documento N-Up dal flusso di input e salva il risultato nel flusso di output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso pdf di input. |
| outputStream | Stream | Flusso pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Crea un documento N-Up dal primo flusso di input al flusso di output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso pdf di input. |
| outputStream | Stream | Flusso pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

True se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Vedi Anche

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Crea un documento N-Up dai due file PDF di input a outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina è dal primo file di input e l'altra è dal secondo file di input. Le due pagine sono sovrapposte orizzontalmente.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | primo file di input. |
| secondInputFile | String | secondo file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

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
| outputStream | Stream | Flusso pdf di output. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Crea un documento N-Up dai file PDF di input multipli a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione delle pagine nei file di input dello stesso numero di pagina. Le pagine multiple sono sovrapposte orizzontalmente se isSidewise è true e sovrapposte verticalmente se isSidewise è false.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | File Pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| isSidewise | Boolean | Modalità di sovrapposizione, true per orizzontale e false per verticale. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Crea un documento N-Up dai flussi PDF di input multipli a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione delle pagine nei flussi di input dello stesso numero di pagina. Le pagine multiple sono sovrapposte orizzontalmente se isSidewise è true e sovrapposte verticalmente se isSidewise è false.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStreams | Stream[] | Flussi Pdf di input. |
| outputStream | Stream | Flusso pdf di output. |
| isSidewise | Boolean | Modalità di sovrapposizione, true per orizzontale e false per verticale. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Crea un documento N-Up dal file di input a outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Vedi Anche

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Crea un documento N-Up dal firstInputFile a outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Crea un documento N-Up dal flusso di input e salva il risultato nel flusso di output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso pdf di input. |
| outputStream | Stream | Flusso pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Crea un documento N-Up dal primo flusso di input al flusso di output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso pdf di input. |
| outputStream | Stream | Flusso pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

True se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Vedi Anche

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Crea un documento N-Up dai due file PDF di input a outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina è dal primo file di input e l'altra è dal secondo file di input. Le due pagine sono sovrapposte orizzontalmente.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | primo file di input. |
| secondInputFile | String | secondo file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Vedi Anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)