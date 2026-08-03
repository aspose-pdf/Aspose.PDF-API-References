---
title: "PdfFileEditor.TryMakeBooklet"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor metod. Skapar en häfte från indatafilen till utdatafilen"
type: docs
weight: 430
url: /sv/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Skapar häfte från indatafilen till utdatafilen.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings‑pdf‑filens sökväg och namn. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryMakeBooklet fungerar som MakeBooklet-metoden, men TryMakeBooklet kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Skapar häfte från InputStream till outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑pdf‑ström. |
| outputStream | Stream | utdata‑pdf‑ström. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryMakeBooklet fungerar som MakeBooklet-metoden, men TryMakeBooklet kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Skapar häfte från inputFile till outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings‑pdf‑filens sökväg och namn. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |
| pageSize | PageSize | Sidstorleken för utdata‑pdf‑filen. |

### Returvärde

True om operationen lyckas.

## Anmärkningar

Metoden TryMakeBooklet fungerar som MakeBooklet-metoden, men TryMakeBooklet kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Skapar häfte från indataströmmen och sparar resultatet i output stream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑PDF‑ström. |
| outputStream | Stream | utdata‑pdf‑ström. |
| pageSize | PageSize | Sidstorleken för utdata‑pdf‑filen. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryMakeBooklet fungerar som MakeBooklet-metoden, men TryMakeBooklet kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Skapar anpassad häfte från firstInputFile till outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatningsfilen. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |
| leftPages | Int32[] | De vänstra sidorna i häftet. |
| rightPages | Int32[] | De högra sidorna i häftet. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryMakeBooklet fungerar som MakeBooklet-metoden, men TryMakeBooklet kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Skapar anpassat häfte från firstInputStream till outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatningsströmmen. |
| outputStream | Stream | utdata‑pdf‑ström. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryMakeBooklet fungerar som MakeBooklet-metoden, men TryMakeBooklet kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Skapar anpassad häfte från firstInputFile till outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatningsfilen. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |
| pageSize | PageSize | Sidstorleken för utdata‑pdf‑filen. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryMakeBooklet fungerar som MakeBooklet-metoden, men TryMakeBooklet kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Skapar häfte från firstInputStream till outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatningsströmmen. |
| outputStream | Stream | utdata‑pdf‑ström. |
| pageSize | PageSize | Sidstorleken för utdata‑pdf‑filen. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryMakeBooklet fungerar som MakeBooklet-metoden, men TryMakeBooklet kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


