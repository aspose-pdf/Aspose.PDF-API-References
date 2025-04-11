---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Crea un opuscolo dal file di input al file di output
type: docs
weight: 430
url: /it/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Crea un opuscolo dal file sorgente e memorizza il risultato negli oggetti HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file sorgente. |
| pageSize | PageSize | Dimensione della pagina desiderata. |
| leftPages | Int32[] | Array di numeri di pagina da posizionare a sinistra. |
| rightPages | Int32[] | Array di numeri di pagina da posizionare a destra. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà memorizzato il risultato. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Crea un opuscolo da un file PDF e lo memorizza in HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del documento di input. |
| pageSize | PageSize | Dimensione della pagina desiderata. |
| leftPages | Int32[] | Array di numeri di pagina che saranno posizionati a sinistra. |
| rightPages | Int32[] | Array di numeri di pagina che saranno posizionati a destra. |
| response | HttpResponse | Oggetto HttpResponse. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Crea un opuscolo dal file sorgente e memorizza il risultato negli oggetti HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file sorgente. |
| pageSize | PageSize | Dimensione della pagina desiderata nel file di output. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà memorizzato il risultato. |

### Valore di ritorno

True se l'operazione ha avuto successo.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Crea un opuscolo dal file sorgente e memorizza il risultato in HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del documento di input. |
| pageSize | PageSize | Dimensione della pagina desiderata nel file di output. |
| response | HttpResponse | Oggetto Respose in cui verrà salvato il risultato. |

### Valore di ritorno

true se l'opuscolo è stato costruito con successo.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Crea un opuscolo dal file di input al file di output.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Crea un opuscolo dallo InputStream a outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream pdf di input. |
| outputStream | Stream | stream pdf di output. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Crea un opuscolo dal inputFile al outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

True se l'operazione ha avuto successo.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Crea un opuscolo dal flusso di input e salva il risultato nel flusso di output.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream PDF di input. |
| outputStream | Stream | stream pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Crea un opuscolo personalizzato dal firstInputFile al outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Il file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| leftPages | Int32[] | Le pagine sinistre dell'opuscolo. |
| rightPages | Int32[] | Le pagine destre dell'opuscolo. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Crea un opuscolo personalizzato dal firstInputStream a outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Il flusso di input. |
| outputStream | Stream | stream pdf di output. |
| leftPages | Int32[] | Le pagine sinistre. |
| rightPages | Int32[] | Le pagine destre. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Crea un opuscolo personalizzato dal firstInputFile al outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Il file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |
| leftPages | Int32[] | Le pagine sinistre. |
| rightPages | Int32[] | Le pagine destre. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Crea un opuscolo dal firstInputStream a outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Il flusso di input. |
| outputStream | Stream | stream pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |
| leftPages | Int32[] | Le pagine sinistre. |
| rightPages | Int32[] | Le pagine destre. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryMakeBooklet è simile al metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)