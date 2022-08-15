---
title: TryMakeBooklet
second_title: Aspose.PDF per .NET API Reference
description: Crea opuscolo dal file sorgente e memorizza il risultato in oggetti HttpResponse.
type: docs
weight: 460
url: /it/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, PageSize, int[], int[], HttpResponse) {#trymakebooklet_6}

Crea opuscolo dal file sorgente e memorizza il risultato in oggetti HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di origine. |
| pageSize | PageSize | Dimensione pagina desiderata. |
| leftPages | Int32[] | Una serie di numeri di pagina da inserire a sinistra. |
| rightPages | Int32[] | Matrice di numeri di pagina da inserire a destra. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Crea un opuscolo da un file PDF e lo memorizza in HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Input flusso di documenti. |
| pageSize | PageSize | Dimensione pagina desiderata. |
| leftPages | Int32[] | Matrice di numeri di pagina che verranno inseriti a sinistra. |
| rightPages | Int32[] | Matrice di numeri di pagina che verranno posizionati a destra. |
| response | HttpResponse | Oggetto HTTPResponse. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Crea opuscolo dal file di origine e memorizza il risultato in oggetti HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di origine. |
| pageSize | PageSize | Dimensione pagina desiderata nel file di output. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Crea opuscolo dal file sorgente e memorizza il risultato in HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Input flusso di documenti. |
| pageSize | PageSize | Dimensione pagina desiderata nel file di output. |
| response | HttpResponse | Respose l'oggetto in cui verrà salvato il risultato. |

### Valore di ritorno

true se il libretto è stato creato correttamente.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Crea opuscolo dal file di input al file di output.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso e il nome del file pdf. |
| outputFile | String | Percorso e nome del file pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet_2}

Crea opuscolo da InputStream a outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Input flusso pdf. |
| outputStream | Stream | flusso di output pdf. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_9}

Crea opuscolo da inputFile a outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso e il nome del file pdf. |
| outputFile | String | Percorso e nome del file pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_3}

Crea opuscolo dal flusso di input e salva il risultato nel flusso di output.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Inserisci flusso PDF. |
| outputStream | Stream | flusso di output pdf. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_11}

Crea opuscolo personalizzato dal firstInputFile a outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Il file di input. |
| outputFile | String | Output percorso e nome del file pdf. |
| leftPages | Int32[] | Le pagine di sinistra del libretto. |
| rightPages | Int32[] | Le pagine giuste del libretto. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_5}

Crea opuscoli personalizzati dal primo InputStream a outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Il flusso di input. |
| outputStream | Stream | flusso di output pdf. |
| leftPages | Int32[] | Le pagine di sinistra. |
| rightPages | Int32[] | Le pagine giuste |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_10}

Crea opuscolo personalizzato dal firstInputFile a outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Il file di input. |
| outputFile | String | Output percorso e nome del file pdf. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |
| leftPages | Int32[] | Le pagine di sinistra. |
| rightPages | Int32[] | Le pagine giuste |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_4}

Crea opuscolo dal primo InputStream a outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Il flusso di input. |
| outputStream | Stream | flusso di output pdf. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |
| leftPages | Int32[] | Le pagine di sinistra. |
| rightPages | Int32[] | Le pagine giuste |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryMakeBooklet è come il metodo MakeBooklet, tranne per il fatto che il metodo TryMakeBooklet non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
