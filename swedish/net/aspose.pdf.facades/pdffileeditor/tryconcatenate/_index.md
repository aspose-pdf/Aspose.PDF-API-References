---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Sammanfogar två filer
type: docs
weight: 390
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

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

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Sammanfogar dokument.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | Document[] | Array av källdokument. |
| dest | Document | Destinationsdokument. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Sammanfogar filer till en fil.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | String[] | Array av filer att sammanfoga. |
| outputFile | String | Namn på utdatafil. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Sammanfogar filer

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream[] | Array av strömmar som ska sammanfogas. |
| outputStream | Stream | Ström där resultatfilen kommer att lagras. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor på alternerande sätt och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten kommer att producera resultatdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, tomsida, p5, tomsida.

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

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor på alternerande sätt och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten kommer att producera resultatdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, tomsida, p5, tomsida.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | Stream | Den första Pdf-strömmen. |
| secInputStream | Stream | Den andra Pdf-strömmen. |
| blankPageStream | Stream | Pdf-strömmen med tom sida. |
| outputStream | Stream | Utdata Pdf-ström. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Sammanfogar filer och sparar resultatet i HttpResponse-objektet.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | String[] | Array av filer att sammanfoga. |
| response | HttpResponse | Svarsobjekt. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Sammanfogar filer och lagrar resultatet i HttpResponse-objektet.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream[] | Strömmar array som innehåller filer att sammanfoga. |
| response | HttpResponse | Svarsobjekt. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryConcatenate-metoden är som Concatenate-metoden, förutom att TryConcatenate-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)