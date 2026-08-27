---
title: "PdfFileEditor.Concatenate"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor metod. Sammanfogar två filer"
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

Sammanfogar två filer.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | String | Första filen att sammanfoga. |
| secInputFile | String | Andra filen att sammanfoga. |
| outputFile | String | Utdatafil. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Sammanfogar två filer.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | Stream | Ström för den första filen. |
| secInputStream | Stream | Ström för den andra filen. |
| outputStream | Stream | Ström där resultatfilen kommer att lagras. |

### Returvärde

True om operationen lyckades.

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Sammanfogar dokument.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | Document[] | Array av källdokument. |
| dest | Dokument | Destinationsdokument. |

### Returvärde

Sant om sammanslagning lyckas.

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

Sammanfogar filer till en fil.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | String[] | Array av filer att sammanfoga. |
| outputFile | String | Namn på utdatafil. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Sammanfogar filer

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream[] | Array av strömmar som ska sammanfogas. |
| outputStream | Stream | Ström där resultatfilen kommer att lagras. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: document1 har 5 sidor: p1, p2, p3, p4, p5. document2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten ger resultatdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | String | Första filen. |
| secInputFile | String | Andra filen. |
| blankPageFile | String | PDF-fil med tom sida. |
| outputFile | String | Resultatfil. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: document1 har 5 sidor: p1, p2, p3, p4, p5. document2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten ger resultatdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | Stream | Den första Pdf-strömmen. |
| secInputStream | Stream | Den andra Pdf-strömmen. |
| blankPageStream | Stream | Pdf-strömmen med tom sida. |
| outputStream | Stream | Utdata-Pdf-ström. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


