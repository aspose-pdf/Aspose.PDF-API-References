---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Estrae pagine da file di input e salva come un nuovo file Pdf
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Estrae pagine dal file di input, salva come un nuovo file Pdf.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Percorso del file Pdf di input. |
| startPage | Int32 | Numero della pagina di inizio. |
| endPage | Int32 | Numero della pagina finale. |
| outputFile | String | Percorso del file Pdf di output. |

### Return Value

True per successo, o false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Estrae pagine specificate da un array di numeri, salva come un nuovo file PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Percorso del file di input. |
| pageNumber | Int32[] | Indice della pagina dal file di input. |
| outputFile | String | Percorso del file di output. |

### Return Value

True se l'operazione è riuscita.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Estrae pagine dal file di input, salva come un nuovo file Pdf.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream del file di input. |
| startPage | Int32 | Numero della pagina di inizio. |
| endPage | Int32 | Numero della pagina finale. |
| outputStream | Stream | Stream del file Pdf di output. |

### Return Value

True per successo, o false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Estrae pagine specificate da un array di numeri, salva come un nuovo file Pdf.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream del file di input. |
| pageNumber | Int32[] | Indice della pagina dal file di input. |
| outputStream | Stream | Stream del file di output. |

### Return Value

True per successo, o false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)