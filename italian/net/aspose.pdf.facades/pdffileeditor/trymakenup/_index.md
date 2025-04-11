---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodo. Ottiene documento NUp dal fileInput primo al fileOutput
type: docs
weight: 440
url: /it/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file sorgente. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | Dimensione della pagina nel file di risultato. |
| response | HttpResponse | Oggetto HttpResponse dove verrà memorizzato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del documento sorgente. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | Dimensione della pagina nel file di risultato. |
| response | HttpResponse | Oggetto HttpResponse dove verrà memorizzato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Crea un documento N-up e memorizza il risultato nell'HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Nome del file sorgente. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| response | HttpResponse | Oggetto HttpResponse dove verrà memorizzato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Crea un documento N-up e memorizza il risultato nell'HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del documento di input. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| response | HttpResponse | HttpResponse dove verrà memorizzato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Crea un documento N-Up dal firstInputFile a outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Crea un documento N-Up dallo stream di input e salva il risultato nello stream di output.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream pdf di input. |
| outputStream | Stream | Stream pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Crea un documento N-Up dal primo stream di input allo stream di output.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream pdf di input. |
| outputStream | Stream | Stream pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Crea un documento N-Up dai due file PDF di input a outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina è dal primo file di input e l'altra è dal secondo file di input. Le due pagine sono sovrapposte orizzontalmente.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | primo file di input. |
| secondInputFile | String | secondo file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Crea un documento N-Up dai due stream PDF di input a outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | primo stream di input. |
| secondInputStream | Stream | secondo stream di input. |
| outputStream | Stream | Stream pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Crea un documento N-Up dai file PDF di input multipli a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione delle pagine nei file di input dello stesso numero di pagina. Le pagine multiple sono sovrapposte orizzontalmente se isSidewise è true e sovrapposte verticalmente se isSidewise è false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | File Pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| isSidewise | Boolean | Modalità di sovrapposizione, true per orizzontale e false per verticale. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Crea un documento N-Up dai flussi PDF di input multipli a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione delle pagine negli stream di input dello stesso numero di pagina. Le pagine multiple sono sovrapposte orizzontalmente se isSidewise è true e sovrapposte verticalmente se isSidewise è false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStreams | Stream[] | Flussi Pdf di input. |
| outputStream | Stream | Stream pdf di output. |
| isSidewise | Boolean | Modalità di sovrapposizione, true per orizzontale e false per verticale. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Crea un documento N-Up dal file di input a outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeNUp è simile al metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)