---
title: "PdfFileEditor.MakeNUp"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metoden. Skapar ett NUp Document från de två inmatade PDF-strömmarna till outputStream."
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Skapar N-Up-dokument från de två inmatade PDF-strömmarna till outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | Stream | första indataström. |
| secondInputStream | Stream | andra indataström. |
| outputStream | Stream | Utdata-pdf-ström. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Skapar N-Up-dokument från de flera inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, vilka är en kombination av sidor i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | String[] | Indata-Pdf-filer. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |
| isSidewise | Boolean | Staplad metod, true för horisontellt och false för vertikalt. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Skapar N-Up-dokument från de flera inmatade PDF-strömmarna till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, vilka är en kombination av sidor i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStreams | Stream[] | Inmatnings‑Pdf‑strömmar. |
| outputStream | Stream | Utdata-pdf-ström. |
| isSidewise | Boolean | Staplad metod, true för horisontellt och false för vertikalt. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Skapar N-Up-dokument från inmatningsfilen till outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings‑pdf‑filens sökväg och namn. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken för utdata‑pdf‑filen. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Skapar N-Up-dokument från firstInputFile till outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings‑pdf‑filens sökväg och namn. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑pdf‑ström. |
| outputStream | Stream | Utdata-pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Skapar N-Up-dokument från den första inmatningsströmmen till output stream.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑pdf‑ström. |
| outputStream | Stream | Utdata-pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken för utdata‑pdf‑filen. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Skapar N-Up-dokument från de två inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida från den första inmatningsfilen och en annan från den andra inmatningsfilen. De två sidorna staplas horisontellt.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | String | första indatafilen. |
| secondInputFile | String | andra indatafilen. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


