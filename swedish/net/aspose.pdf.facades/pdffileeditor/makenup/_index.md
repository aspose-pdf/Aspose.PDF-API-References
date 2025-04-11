---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Skapar NUp-dokument från de två inmatade PDF-strömmarna till outputStream
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Skapar N-Up-dokument från firstInputFile till outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Inmatad pdf-filens sökväg och namn. |
| outputFile | Sträng | Utmatad pdf-filens sökväg och namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i utmatningsströmmen.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Inmatad pdf-ström. |
| outputStream | Ström | Utmatad pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Skapar N-Up-dokument från den första inmatningsströmmen till utmatningsströmmen.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Inmatad pdf-ström. |
| outputStream | Ström | Utmatad pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken på den utmatade pdf-filen. |

### Returvärde

Sant om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Skapar N-Up-dokument från de två inmatade PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla två sidor, en sida är från den första inmatade filen och en annan är från den andra inmatade filen. De två sidorna staplas horisontellt.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | Sträng | första inmatade fil. |
| secondInputFile | Sträng | andra inmatade fil. |
| outputFile | Sträng | Utmatad pdf-filens sökväg och namn. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Skapar N-Up-dokument från de två inmatade PDF-strömmarna till outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | Ström | första inmatningsström. |
| secondInputStream | Ström | andra inmatningsström. |
| outputStream | Ström | Utmatad pdf-ström. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Skapar N-Up-dokument från de flera inmatade PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | Sträng[] | Inmatade Pdf-filer. |
| outputFile | Sträng | Utmatad pdf-filens sökväg och namn. |
| isSidewise | Boolean | Staplingssätt, sant för horisontellt och falskt för vertikalt. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Skapar N-Up-dokument från de flera inmatade PDF-strömmarna till outputStream. Varje sida av outputStream kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsströmmen med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStreams | Ström[] | Inmatade Pdf-strömmar. |
| outputStream | Ström | Utmatad pdf-ström. |
| isSidewise | Boolean | Staplingssätt, sant för horisontellt och falskt för vertikalt. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Skapar N-Up-dokument från inmatningsfilen till outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Inmatad pdf-filens sökväg och namn. |
| outputFile | Sträng | Utmatad pdf-filens sökväg och namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken på den utmatade pdf-filen. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Skapar N-Up-dokument från firstInputFile till outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Inmatad pdf-filens sökväg och namn. |
| outputFile | Sträng | Utmatad pdf-filens sökväg och namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i utmatningsströmmen.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Inmatad pdf-ström. |
| outputStream | Ström | Utmatad pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Skapar N-Up-dokument från den första inmatningsströmmen till utmatningsströmmen.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Inmatad pdf-ström. |
| outputStream | Ström | Utmatad pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken på den utmatade pdf-filen. |

### Returvärde

Sant om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Skapar N-Up-dokument från de två inmatade PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla två sidor, en sida är från den första inmatade filen och en annan är från den andra inmatade filen. De två sidorna staplas horisontellt.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | Sträng | första inmatade fil. |
| secondInputFile | Sträng | andra inmatade fil. |
| outputFile | Sträng | Utmatad pdf-filens sökväg och namn. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)