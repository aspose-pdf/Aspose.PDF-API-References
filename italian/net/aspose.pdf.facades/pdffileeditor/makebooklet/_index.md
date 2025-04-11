---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Crea un opuscolo dal file di input al file di output
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Crea un opuscolo dal file di input al file di output.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Crea un opuscolo dallo InputStream allo outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream pdf di input. |
| outputStream | Stream | stream pdf di output. |

### Valore di ritorno

True se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Crea un opuscolo dal inputFile al outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso e nome del file pdf di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

True se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Crea un opuscolo dallo stream di input e salva il risultato nello stream di output.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream PDF di input. |
| outputStream | Stream | stream pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |

### Valore di ritorno

True se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Crea un opuscolo personalizzato dal firstInputFile al outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Il file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| leftPages | Int32[] | Le pagine sinistre dell'opuscolo. |
| rightPages | Int32[] | Le pagine destra dell'opuscolo. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Crea un opuscolo personalizzato dal firstInputStream allo outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Lo stream di input. |
| outputStream | Stream | stream pdf di output. |
| leftPages | Int32[] | Le pagine sinistre. |
| rightPages | Int32[] | Le pagine destra. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Crea un opuscolo personalizzato dal firstInputFile al outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Il file di input. |
| outputFile | String | Percorso e nome del file pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |
| leftPages | Int32[] | Le pagine sinistre. |
| rightPages | Int32[] | Le pagine destra. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Crea un opuscolo dallo firstInputStream allo outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Lo stream di input. |
| outputStream | Stream | stream pdf di output. |
| pageSize | PageSize | La dimensione della pagina del file pdf di output. |
| leftPages | Int32[] | Le pagine sinistre. |
| rightPages | Int32[] | Le pagine destra. |

### Valore di ritorno

boolean - True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Crea un opuscolo dal file sorgente e memorizza il risultato negli oggetti HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file sorgente. |
| pageSize | PageSize | Dimensione della pagina desiderata. |
| leftPages | Int32[] | Array di numeri di pagina da posizionare a sinistra. |
| rightPages | Int32[] | Array di numeri di pagina da posizionare a destra. |
| response | HttpResponse | Oggetto HttpResponse dove verrà memorizzato il risultato. |

### Valore di ritorno

True se l'operazione è riuscita.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Crea un opuscolo da un file PDF e lo memorizza in HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del documento di input. |
| pageSize | PageSize | Dimensione della pagina desiderata. |
| leftPages | Int32[] | Array di numeri di pagina che saranno posizionati a sinistra. |
| rightPages | Int32[] | Array di numeri di pagina che saranno posizionati a destra. |
| response | HttpResponse | Oggetto HttpResponse. |

### Valore di ritorno

True se l'operazione è riuscita.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Crea un opuscolo dal file sorgente e memorizza il risultato negli oggetti HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file sorgente. |
| pageSize | PageSize | Dimensione della pagina desiderata nel file di output. |
| response | HttpResponse | Oggetto HttpResponse dove verrà memorizzato il risultato. |

### Valore di ritorno

True se l'operazione è riuscita.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Crea un opuscolo dal file sorgente e memorizza il risultato in HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del documento di input. |
| pageSize | PageSize | Dimensione della pagina desiderata nel file di output. |
| response | HttpResponse | Oggetto Respose dove verrà salvato il risultato. |

### Valore di ritorno

true se l'opuscolo è stato costruito con successo.

### Vedi anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)