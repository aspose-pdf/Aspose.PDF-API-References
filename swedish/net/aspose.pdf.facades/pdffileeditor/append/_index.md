---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Lägger till sidor som väljs från array av dokument i portStreams. Det resulterande dokumentet inkluderar firstInputFile och alla portStreams dokument sidor i intervallet startPage till endPage
type: docs
weight: 250
url: /sv/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Lägger till sidor, som väljs från array av dokument i portStreams. Det resulterande dokumentet inkluderar firstInputFile och alla portStreams dokument sidor i intervallet startPage till endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings Pdf-ström. |
| portStreams | Stream[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sida börjar i portStreams dokument. |
| endPage | Int32 | Sida slutar i portStreams dokument. |
| outputStream | Stream | Utmatnings Pdf-ström. |

### Return Value

True för framgång, eller false.

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

Lägger till sidor, som väljs från portFiles dokument. Det resulterande dokumentet inkluderar firstInputFile och alla portFiles dokument sidor i intervallet startPage till endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings Pdf-fil. |
| portFiles | String[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sida börjar i portFiles dokument. |
| endPage | Int32 | Sida slutar i portFiles dokument. |
| outputFile | String | Utmatnings Pdf-dokument. |

### Return Value

True om operationen lyckades.

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

Lägger till sidor, som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings Pdf-fil. |
| portFile | String | Sidor från Pdf-fil. |
| startPage | Int32 | Sida börjar i portFile. |
| endPage | Int32 | Sida slutar i portFile. |
| outputFile | String | Utmatnings Pdf-dokument. |

### Return Value

True om operationen lyckades.

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

Lägger till sidor, som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatningsfil Stream. |
| portStream | Stream | Sidor från Pdf-fil Stream. |
| startPage | Int32 | Sida börjar i portFile Stream. |
| endPage | Int32 | Sida slutar i portFile Stream. |
| outputStream | Stream | Utmatnings Pdf-fil Stream. |

### Return Value

True för framgång, eller false.

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