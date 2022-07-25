---
title: TryMakeNUp
second_title: Aspose.PDF för .NET API Referens
description: Gör N-up-dokument och lagrar resultatet i HttpResponse-objekt.
type: docs
weight: 470
url: /sv/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, int, int, PageSize, HttpResponse) {#trymakenup_6}

Gör N-up-dokument och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Sökväg till källfil. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorlek i resultatfil. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Gör N-up-dokument och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström av källdokument. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorlek i resultatfil. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Gör N-up-dokument och lagrar resultatet i HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Källfilens namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Gör N-up-dokument och lagrar resultatet i HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström av inmatningsdokument. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| response | HttpResponse | HttpResponse där resultatet kommer att lagras. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Gör N-Up-dokument från den första InputFile till outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Ange sökväg och namn för pdf-fil. |
| outputFile | String | Utdata pdf-fil sökväg och namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup_2}

Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i utdataström.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Mata in pdf-ström. |
| outputStream | Stream | Utdata pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_3}

Gör N-Up-dokument från den första ingångsströmmen till utdataström.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Mata in pdf-ström. |
| outputStream | Stream | Utdata pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken för den utgående pdf-filen. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_10}

Gör N-Up-dokument från de två inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida är från den första inmatningsfilen och en annan är från den andra inmatningsfilen. De två sidorna är staplade horisontellt.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | String | första inmatningsfilen. |
| secondInputFile | String | andra inmatningsfilen. |
| outputFile | String | Utdata pdf-fil sökväg och namn. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_4}

Gör N-Up-dokument från de två ingående PDF-strömmarna till outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | Stream | första ingångsström. |
| secondInputStream | Stream | andra ingångsström. |
| outputStream | Stream | Utdata pdf-ström. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_11}

Gör N-Up-dokument från PDF-filer med flera indata till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, som är kombination med sidorna i inmatningsfilerna med samma sidnummer. Flera sidor staplade upp horisontellt om isSidewise är sant och staplade upp vertikalt om isSidewise är falskt.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | String[] | Mata in pdf-filer. |
| outputFile | String | Utdata pdf-fil sökväg och namn. |
| isSidewise | Boolean | Staplad långt, sant för horisontellt och falskt för vertikalt. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_5}

Gör N-Up-dokument från PDF-strömmarna med flera indata till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, som är kombinationer med sidorna i inmatningsströmmarna med samma sidnummer. Flera sidor staplade upp horisontellt om isSidewise är sant och staplade upp vertikalt om isSidewise är falskt.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStreams | Stream[] | Inmatning av pdf-strömmar. |
| outputStream | Stream | Utdata pdf-ström. |
| isSidewise | Boolean | Staplad långt, sant för horisontellt och falskt för vertikalt. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_9}

Gör N-Up-dokument från indatafilen till outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Ange sökväg och namn för pdf-fil. |
| outputFile | String | Utdata pdf-fil sökväg och namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken för den utgående pdf-filen. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
