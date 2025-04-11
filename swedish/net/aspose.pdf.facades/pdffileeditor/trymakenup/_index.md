---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Skapar NUp-dokument från firstInputFile till outputFile
type: docs
weight: 440
url: /sv/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Skapar N-up-dokument och lagrar resultatet i HttpResponse-objektet.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till källfil. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorlek i resultatfilen. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Skapar N-up-dokument och lagrar resultatet i HttpResponse-objektet.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström av källdokument. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorlek i resultatfilen. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Skapar N-up-dokument och lagrar resultatet i HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Källfilens namn. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Skapar N-up-dokument och lagrar resultatet i HttpResponse.

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

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Skapar N-Up-dokument från firstInputFile till outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg och namn på inmatnings-pdf-filen. |
| outputFile | Sträng | Sökväg och namn på utmatnings-pdf-filen. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i utmatningsströmmen.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings-pdf-ström. |
| outputStream | Stream | Utmatnings-pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Skapar N-Up-dokument från den första inmatningsströmmen till utmatningsströmmen.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings-pdf-ström. |
| outputStream | Stream | Utmatnings-pdf-ström. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken på utmatnings-pdf-filen. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Skapar N-Up-dokument från de två inmatnings-PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla två sidor, en sida är från den första inmatningsfilen och en annan är från den andra inmatningsfilen. De två sidorna staplas horisontellt.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | Sträng | första inmatningsfil. |
| secondInputFile | Sträng | andra inmatningsfil. |
| outputFile | Sträng | Sökväg och namn på utmatnings-pdf-filen. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Skapar N-Up-dokument från de två inmatnings-PDF-strömmarna till outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | Stream | första inmatningsström. |
| secondInputStream | Stream | andra inmatningsström. |
| outputStream | Stream | Utmatnings-pdf-ström. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Skapar N-Up-dokument från de flera inmatnings-PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är true och staplas vertikalt om isSidewise är false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | Sträng[] | Inmatnings-Pdf-filer. |
| outputFile | Sträng | Sökväg och namn på utmatnings-pdf-filen. |
| isSidewise | Boolean | Staplingssätt, true för horisontellt och false för vertikalt. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Skapar N-Up-dokument från de flera inmatnings-PDF-strömmarna till outputStream. Varje sida av outputStream kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är true och staplas vertikalt om isSidewise är false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStreams | Stream[] | Inmatnings-Pdf-strömmar. |
| outputStream | Stream | Utmatnings-pdf-ström. |
| isSidewise | Boolean | Staplingssätt, true för horisontellt och false för vertikalt. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Skapar N-Up-dokument från inmatningsfilen till outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg och namn på inmatnings-pdf-filen. |
| outputFile | Sträng | Sökväg och namn på utmatnings-pdf-filen. |
| x | Int32 | Antal kolumner. |
| y | Int32 | Antal rader. |
| pageSize | PageSize | Sidstorleken på utmatnings-pdf-filen. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryMakeNUp-metoden är som MakeNUp-metoden, förutom att TryMakeNUp-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)