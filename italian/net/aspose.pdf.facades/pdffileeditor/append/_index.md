---
title: Append
second_title: Aspose.PDF per .NET API Reference
description: Aggiunge le pagine che sono scelte dallarray di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nellintervallo da startPage a endPage.
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Aggiunge le pagine, che sono scelte dall'array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo da startPage a endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso Pdf di input. |
| portStreams | Stream[] | Documenti da cui copiare le pagine. |
| startPage | Int32 | La pagina inizia nei documenti portStreams. |
| endPage | Int32 | La pagina termina nei documenti portStreams. |
| outputStream | Stream | Uscita flusso Pdf. |

### Valore di ritorno

Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

Aggiunge le pagine scelte dai documenti portFiles. Il documento risultato include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo da startPage a endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il file Pdf. |
| portFiles | String[] | Documenti da cui copiare le pagine. |
| startPage | Int32 | La pagina inizia nei documenti portFiles. |
| endPage | Int32 | La pagina finisce nei documenti portFiles. |
| outputFile | String | Uscita documento PDF. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

Aggiunge le pagine, scelte da portFile nell'intervallo da startPage a endPage, in portFile alla fine di firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il file Pdf. |
| portFile | String | Pagine da file Pdf. |
| startPage | Int32 | La pagina inizia in portFile. |
| endPage | Int32 | La pagina termina in portFile. |
| outputFile | String | Uscita documento PDF. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Aggiunge le pagine, che sono scelte da portStream nell'intervallo da startPage a endPage, in portStream alla fine di firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | File di input Flusso. |
| portStream | Stream | Pagine da file Pdf Stream. |
| startPage | Int32 | La pagina inizia in portFile Stream. |
| endPage | Int32 | La pagina termina in portFile Stream. |
| outputStream | Stream | Output di file Pdf Stream. |

### Valore di ritorno

Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

Aggiunge i documenti al documento di origine e salva il risultato nell'oggetto di risposta.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream che contiene il documento di origine. |
| portStreams | Stream[] | Matrice di flussi con documenti da allegare. |
| startPage | Int32 | Pagina iniziale della pagina allegata. |
| endPage | Int32 | Pagina finale delle pagine allegate. |
| response | HttpResponse | Oggetto di risposta in cui verrà salvato il documento. |

### Valore di ritorno

true se l'operazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

Aggiunge i documenti al documento di origine e salva il risultato nell'oggetto HttpResponse.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Nome del file contenente il documento di origine. |
| portFiles | String[] | Matrice di nomi di file contenenti documenti aggiunti. |
| startPage | Int32 | Pagina iniziale delle pagine allegate. |
| endPage | Int32 | Pagina finale delle pagine allegate. |
| response | HttpResponse | Oggetto di risposta in cui verrà salvato il documento. |

### Valore di ritorno

true se l'operazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
