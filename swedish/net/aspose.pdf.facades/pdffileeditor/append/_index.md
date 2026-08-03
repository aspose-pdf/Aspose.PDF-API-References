---
title: "PdfFileEditor.Append"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor metod. Lägger till sidor som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla sidor från portStreams-dokumenten i intervallet startPage till endPage"
type: docs
weight: 250
url: /sv/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Lägger till sidor, som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams-dokumentens sidor i intervallet startPage till endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑Pdf‑ström. |
| portStreams | Stream[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sidan börjar i portStreams-dokument. |
| endPage | Int32 | Sidan slutar i portStreams-dokument. |
| outputStream | Stream | Utdata Pdf-ström. |

### Returvärde

Sant för framgång, annars falskt.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Lägger till sidor, som väljs från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentens sidor i intervallet startPage till endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Indata‑Pdf‑fil. |
| portFiles | String[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sidan börjar i portFiles-dokument. |
| endPage | Int32 | Sidan slutar i portFiles-dokument. |
| outputFile | String | Utdata Pdf-dokument. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Se även

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
| inputFile | String | Indata‑Pdf‑fil. |
| portFile | String | Sidor från Pdf-fil. |
| startPage | Int32 | Sidan börjar i portFile. |
| endPage | Int32 | Sidan slutar i portFile. |
| outputFile | String | Utdata Pdf-dokument. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Se även

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
| inputStream | Stream | Inmatningsfilström. |
| portStream | Stream | Sidor från Pdf-filström. |
| startPage | Int32 | Sidan börjar i portFile-ström. |
| endPage | Int32 | Sidan slutar i portFile-ström. |
| outputStream | Stream | Utdata Pdf-filström. |

### Returvärde

Sant för framgång, annars falskt.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


