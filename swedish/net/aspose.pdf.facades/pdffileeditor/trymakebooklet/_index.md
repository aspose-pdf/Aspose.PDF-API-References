---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Gör en häfte från indatafilen till utdatafilen
type: docs
weight: 430
url: /sv/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Gör en häfte från källfilen och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Källfilens sökväg. |
| pageSize | PageSize | Önskad sidstorlek. |
| leftPages | Int32[] | Array av sidnummer som ska placeras till vänster. |
| rightPages | Int32[] | Array av sidnummer som ska placeras till höger. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Gör en häfte från PDF-filen och lagrar den i HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatadokumentström. |
| pageSize | PageSize | Önskad sidstorlek. |
| leftPages | Int32[] | Array av sidnummer som kommer att placeras till vänster. |
| rightPages | Int32[] | Array av sidnummer som kommer att placeras till höger. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Gör en häfte från källfilen och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Källfilens sökväg. |
| pageSize | PageSize | Önskad sidstorlek i utdatafilen. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

True om operationen lyckades.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Gör en häfte från källfilen och lagrar resultatet i HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatadokumentström. |
| pageSize | PageSize | Önskad sidstorlek i utdatafilen. |
| response | HttpResponse | Respose-objekt där resultatet kommer att sparas. |

### Returvärde

true om häftet byggdes framgångsrikt.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Gör en häfte från indatafilen till utdatafilen.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg och namn på indata PDF-fil. |
| outputFile | Sträng | Sökväg och namn på utdata PDF-fil. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Gör en häfte från InputStream till outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indata PDF-ström. |
| outputStream | Stream | utdata PDF-ström. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Gör en häfte från inputFile till outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg och namn på indata PDF-fil. |
| outputFile | Sträng | Sökväg och namn på utdata PDF-fil. |
| pageSize | PageSize | Sidstorleken på utdata PDF-fil. |

### Returvärde

True om operationen lyckades.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Gör en häfte från indataströmmen och sparar resultatet i utdataströmmen.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indata PDF-ström. |
| outputStream | Stream | utdata PDF-ström. |
| pageSize | PageSize | Sidstorleken på utdata PDF-fil. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Gör en anpassad häfte från firstInputFile till outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Indatafilen. |
| outputFile | Sträng | Sökväg och namn på utdata PDF-fil. |
| leftPages | Int32[] | De vänstra sidorna av häftet. |
| rightPages | Int32[] | De högra sidorna av häftet. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Gör en anpassad häfte från firstInputStream till outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indataströmmen. |
| outputStream | Stream | utdata PDF-ström. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Gör en anpassad häfte från firstInputFile till outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Indatafilen. |
| outputFile | Sträng | Sökväg och namn på utdata PDF-fil. |
| pageSize | PageSize | Sidstorleken på utdata PDF-fil. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Gör en häfte från firstInputStream till outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indataströmmen. |
| outputStream | Stream | utdata PDF-ström. |
| pageSize | PageSize | Sidstorleken på utdata PDF-fil. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Kommentarer

TryMakeBooklet-metoden är som MakeBooklet-metoden, förutom att TryMakeBooklet-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)