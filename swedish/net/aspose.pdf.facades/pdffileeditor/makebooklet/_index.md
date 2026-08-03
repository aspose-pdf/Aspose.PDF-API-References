---
title: "PdfFileEditor.MakeBooklet"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor metod. Skapar en häfte från indatafilen till utdatafilen"
type: docs
weight: 300
url: /sv/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Skapar häfte från indatafilen till utdatafilen.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings‑pdf‑filens sökväg och namn. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Skapar häfte från InputStream till outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑pdf‑ström. |
| outputStream | Stream | utdata‑pdf‑ström. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Skapar häfte från inputFile till outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings‑pdf‑filens sökväg och namn. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |
| pageSize | PageSize | Sidstorleken för utdata‑pdf‑filen. |

### Returvärde

True om operationen lyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Skapar häfte från indataströmmen och sparar resultatet i output stream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑PDF‑ström. |
| outputStream | Stream | utdata‑pdf‑ström. |
| pageSize | PageSize | Sidstorleken för utdata‑pdf‑filen. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Skapar anpassad häfte från firstInputFile till outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatningsfilen. |
| outputFile | String | Utdata‑pdf‑filens sökväg och namn. |
| leftPages | Int32[] | De vänstra sidorna i häftet. |
| rightPages | Int32[] | De högra sidorna i häftet. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Skapar anpassat häfte från firstInputStream till outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatningsströmmen. |
| outputStream | Stream | utdata‑pdf‑ström. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Skapar anpassad häfte från firstInputFile till outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Skapar häfte från firstInputStream till outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

boolesk - True för framgång, eller false.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


