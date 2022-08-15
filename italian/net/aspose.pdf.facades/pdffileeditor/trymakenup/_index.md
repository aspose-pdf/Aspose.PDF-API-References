---
title: TryMakeNUp
second_title: Aspose.PDF per .NET API Reference
description: Crea un documento N-up e memorizza il risultato nelloggetto HttpResponse.
type: docs
weight: 470
url: /it/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, int, int, PageSize, HttpResponse) {#trymakenup_6}

Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di origine. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | Dimensioni della pagina nel file dei risultati. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del documento di origine. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | Dimensioni della pagina nel file dei risultati. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Crea un documento N-up e memorizza il risultato in HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Nome del file di origine. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Crea un documento N-up e memorizza il risultato in HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del documento di input. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| response | HttpResponse | HttpResponse dove verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Crea un documento N su 1 dal firstInputFile a outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso e il nome del file pdf. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup_2}

Crea un documento N su 1 dal flusso di input e salva il risultato nel flusso di output.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Input flusso pdf. |
| outputStream | Stream | Output flusso pdf. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_3}

Crea un documento N su 1 dal primo flusso di input al flusso di output.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Input flusso pdf. |
| outputStream | Stream | Output flusso pdf. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_10}

Crea un documento N-Up dai due file PDF di input in outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina proviene dal primo file di input e un'altra dal secondo file di input. Le due pagine sono impilate orizzontalmente.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputFile | String | primo file di input. |
| secondInputFile | String | secondo file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_4}

Crea un documento N-Up dai due flussi PDF di input a outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstInputStream | Stream | primo flusso di input. |
| secondInputStream | Stream | secondo flusso di input. |
| outputStream | Stream | Output flusso pdf. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_11}

Crea un documento N-Up dai file PDF multi input a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione con le pagine nei file di input con lo stesso numero di pagina. Le pagine multiple impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFiles | String[] | Inserisci i file Pdf. |
| outputFile | String | Percorso e nome del file pdf di output. |
| isSidewise | Boolean | Accatastati, vero per orizzontalmente e falso per verticalmente. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_5}

Crea un documento N su 1 dai flussi PDF multi input a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione con le pagine nei flussi di input con lo stesso numero di pagina. Le pagine multiple impilate orizzontalmente se isSidewise è vero e impilate verticalmente se isSidewise è false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStreams | Stream[] | Input di flussi Pdf. |
| outputStream | Stream | Output flusso pdf. |
| isSidewise | Boolean | Accatastati, vero per orizzontalmente e falso per verticalmente. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_9}

Crea un documento N su 1 dal file di input a outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso e il nome del file pdf. |
| outputFile | String | Percorso e nome del file pdf di output. |
| x | Int32 | Numero di colonne. |
| y | Int32 | Numero di righe. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeNUp è come il metodo MakeNUp, tranne per il fatto che il metodo TryMakeNUp non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
