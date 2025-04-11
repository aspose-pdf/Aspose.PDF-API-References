---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Aggiunge pagine scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo da startPage a endPage
type: docs
weight: 250
url: /it/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Aggiunge pagine, che sono scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo da startPage a endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream Pdf di input. |
| portStreams | Stream[] | Documenti da cui copiare le pagine. |
| startPage | Int32 | La pagina inizia nei documenti portStreams. |
| endPage | Int32 | La pagina termina nei documenti portStreams. |
| outputStream | Stream | Stream Pdf di output. |

### Return Value

True per successo, o false.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Aggiunge pagine, che sono scelte dai documenti portFiles. Il documento risultante include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo da startPage a endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | File Pdf di input. |
| portFiles | String[] | Documenti da cui copiare le pagine. |
| startPage | Int32 | La pagina inizia nei documenti portFiles. |
| endPage | Int32 | La pagina termina nei documenti portFiles. |
| outputFile | String | Documento Pdf di output. |

### Return Value

True se l'operazione è riuscita.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Aggiunge pagine, che sono scelte da portFile nell'intervallo da startPage a endPage, in portFile alla fine di firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | File Pdf di input. |
| portFile | String | Pagine da file Pdf. |
| startPage | Int32 | La pagina inizia in portFile. |
| endPage | Int32 | La pagina termina in portFile. |
| outputFile | String | Documento Pdf di output. |

### Return Value

True se l'operazione è riuscita.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Aggiunge pagine, che sono scelte da portStream nell'intervallo da startPage a endPage, in portStream alla fine di firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream di file di input. |
| portStream | Stream | Pagine da stream di file Pdf. |
| startPage | Int32 | La pagina inizia in portFile Stream. |
| endPage | Int32 | La pagina termina in portFile Stream. |
| outputStream | Stream | Stream di file Pdf di output. |

### Return Value

True per successo, o false.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)