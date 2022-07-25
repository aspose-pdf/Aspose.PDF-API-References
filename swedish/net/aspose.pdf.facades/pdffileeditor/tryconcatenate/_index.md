---
title: TryConcatenate
second_title: Aspose.PDF för .NET API Referens
description: Sammanfogar två filer.
type: docs
weight: 420
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_4}

Sammanfogar två filer.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | String | Första filen att sammanfoga. |
| secInputFile | String | Andra filen att sammanfoga. |
| outputFile | String | Utdatafil. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Sammanfogar dokument.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | Document[] | En rad källdokument. |
| dest | Document | Destinationsdokument. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_6}

Sammanfogar filer till en fil.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | String[] | Uppsättning av filer att sammanfoga. |
| outputFile | String | Namn på utdatafil. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Sammanfogar filer

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream[] | En rad strömmar som ska sammanfogas. |
| outputStream | Stream | Streama där resultatfilen kommer att lagras. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_5}

Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor på alternativa sätt och fyll de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Genom att slå samman de två PDF-dokumenten skapas resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blanksida, p5, blanksida .

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | String | Första filen. |
| secInputFile | String | Andra filen. |
| blankPageFile | String | PDF-fil med tom sida. |
| outputFile | String | Resultatfil. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryConcatenate-metoden är som Concatenate -metoden, förutom att TryConcatenate-metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor på alternativa sätt och fyll de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Genom att slå samman de två PDF-dokumenten skapas resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blanksida, p5, blanksida .

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | Stream | Den första pdf-strömmen. |
| secInputStream | Stream | Den andra pdf-strömmen. |
| blankPageStream | Stream | Pdf-strömmen med tom sida. |
| outputStream | Stream | Utdata pdf-ström. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryConcatenate-metoden är som Concatenate -metoden, förutom att TryConcatenate-metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Sammanfogar filer och sparar reslt i HttpResposnse-objekt.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | String[] | Uppsättning av filer att sammanfoga. |
| response | HttpResponse | Responsobjekt. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Sammanfogar filer och lagrar resultat till HttpResponse-objekt.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream[] | Strömmar array som innehåller filer att sammanfoga. |
| response | HttpResponse | Svarsobjekt/ |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
