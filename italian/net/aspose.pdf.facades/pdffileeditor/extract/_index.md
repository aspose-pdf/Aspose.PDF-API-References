---
title: Extract
second_title: Aspose.PDF per .NET API Reference
description: Estrae le pagine dal file di input salva come nuovo file Pdf.
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_3}

Estrae le pagine dal file di input, salva come nuovo file Pdf.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso del file Pdf. |
| startPage | Int32 | Numero di pagina iniziale. |
| endPage | Int32 | Numero di pagina finale. |
| outputFile | String | Percorso del file Pdf di output. |

### Valore di ritorno

Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_4}

Estrae le pagine specificate dall'array di numeri, le salva come un nuovo file PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso del file. |
| pageNumber | Int32[] | Indice della pagina fuori dal file di input. |
| outputFile | String | Percorso del file di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Estrae le pagine dal file di input, salva come nuovo file Pdf.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | File di input Flusso. |
| startPage | Int32 | Numero di pagina iniziale. |
| endPage | Int32 | Numero di pagina finale. |
| outputStream | Stream | Output di file Pdf Stream. |

### Valore di ritorno

Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Estrae le pagine specificate dall'array di numeri, le salva come un nuovo file Pdf.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | File di input Flusso. |
| pageNumber | Int32[] | Indice della pagina fuori dal file di input. |
| outputStream | Stream | Flusso di file di output. |

### Valore di ritorno

Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Extract(Stream, int[], HttpResponse) {#extract_2}

Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del documento di origine. |
| pageNumber | Int32[] | Matrice di numeri di pagina che verranno estratti. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Extract(string, int[], HttpResponse) {#extract_5}

Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool Extract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di origine. |
| pageNumber | Int32[] | Matrice di numeri di pagina che verranno estratti. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

true se le pagine sono state estratte correttamente.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
