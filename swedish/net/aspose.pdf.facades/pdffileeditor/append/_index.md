---
title: Append
second_title: Aspose.PDF för .NET API Referens
description: Lägger till sidor som väljs från en mängd dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams dokumentsidor i intervallet startPage to endPage.
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Lägger till sidor, som väljs från en mängd dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams dokumentsidor i intervallet startPage to endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Mata in pdf-ström. |
| portStreams | Stream[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sidan startar i portStreams-dokument. |
| endPage | Int32 | Sidan slutar i portStreams-dokument. |
| outputStream | Stream | Utdata pdf-ström. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

Lägger till sidor som är valda från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentsidor i intervallet startPage to endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Mata in pdf-fil. |
| portFiles | String[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sidan startar i portFiles-dokument. |
| endPage | Int32 | Sidan slutar i portFiles-dokument. |
| outputFile | String | Utdata pdf-dokument. |

### Returvärde

Sant om operationen lyckades.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

Lägger till sidor, som är valda från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Mata in pdf-fil. |
| portFile | String | Sidor från pdf-fil. |
| startPage | Int32 | Sidan startar i portFile. |
| endPage | Int32 | Sidan slutar i portFile. |
| outputFile | String | Utdata pdf-dokument. |

### Returvärde

Sant om operationen lyckades.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Lägger till sidor, som är valda från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| portStream | Stream | Sidor från pdf-fil Stream. |
| startPage | Int32 | Sidan startar i portFile Stream. |
| endPage | Int32 | Sidan slutar i portFile Stream. |
| outputStream | Stream | Utdata pdf-fil Stream. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

Lägger till dokument till källdokument och sparar resultatet i svarsobjekt.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Stream som innehåller källdokument. |
| portStreams | Stream[] | Uppsättning strömmar med dokument som ska läggas till. |
| startPage | Int32 | Startsida för bifogad sida. |
| endPage | Int32 | Slutsida av bifogade sidor. |
| response | HttpResponse | Svarsobjekt där dokumentet kommer att sparas. |

### Returvärde

sant om operationen lyckades.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

Lägger till dokument till källdokument och sparar resultatet i HttpResponse-objekt.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Namnet på filen som innehåller källdokumentet. |
| portFiles | String[] | Matris med filnamn som innehåller bifogade dokument. |
| startPage | Int32 | Startsida för bifogade sidor. |
| endPage | Int32 | Slutsida av bifogade sidor. |
| response | HttpResponse | Svarsobjekt där dokumentet kommer att sparas. |

### Returvärde

sant om operationen lyckades.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
