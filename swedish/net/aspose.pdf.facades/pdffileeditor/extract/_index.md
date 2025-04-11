---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Extraherar sidor från indatafiler och sparar som en ny Pdf-fil
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Extraherar sidor från indatafil, sparar som en ny Pdf-fil.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till indata Pdf-fil. |
| startPage | Int32 | Start sidnummer. |
| endPage | Int32 | Slut sidnummer. |
| outputFile | Sträng | Sökväg till utdata Pdf-fil. |

### Return Value

True för framgång, eller false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### See Also

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Extraherar sidor specificerade av nummerarray, sparar som en ny PDF-fil.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till indatafil. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputFile | Sträng | Sökväg till utdatafil. |

### Return Value

True om operationen lyckades.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### See Also

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extraherar sidor från indatafil, sparar som en ny Pdf-fil.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| startPage | Int32 | Start sidnummer. |
| endPage | Int32 | Slut sidnummer. |
| outputStream | Stream | Utdata Pdf-fil Stream. |

### Return Value

True för framgång, eller false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### See Also

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extraherar sidor specificerade av nummerarray, sparar som en ny Pdf-fil.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputStream | Stream | Utdatafil stream. |

### Return Value

True för framgång, eller false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### See Also

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)