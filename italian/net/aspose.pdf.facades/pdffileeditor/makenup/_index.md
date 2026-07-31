---
title: "PdfFileEditor.MakeNUp"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Crea un documento NUp dai due flussi PDF di input verso outputStream"
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Crea un documento N-Up dai due stream PDF di input a outputStream.

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

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Crea un documento N-Up dai più file PDF di input a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono combinazioni delle pagine nei file di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | File Pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| isSidewise | Boolean | Modo impilato, true per orizzontale e false per verticale. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Crea un documento N-Up dai più stream PDF di input a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono combinazioni delle pagine nei stream di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStreams | Stream[] | Flussi Pdf di input. |
| outputStream | Stream | Flusso pdf di output. |
| isSidewise | Boolean | Modo impilato, true per orizzontale e false per verticale. |

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

### Vedi anche

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

### Vedi anche

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Crea un documento N-Up da firstInputFile a outputFile.

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

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Crea un documento N-Up dallo stream di input e salva il risultato nello stream di output.

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

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Crea un documento N-Up dal primo stream di input a output stream.

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

### Vedi anche

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Crea un documento N-Up dai due file PDF di input a outputFile. Ogni pagina di outputFile conterrà due pagine, una proveniente dal primo file di input e l'altra dal secondo file di input. Le due pagine sono impilate orizzontalmente.

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

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


