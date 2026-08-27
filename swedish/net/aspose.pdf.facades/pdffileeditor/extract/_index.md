---
title: "PdfFileEditor.Extract"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metod. Extraherar pages från input file och sparar som en ny Pdf file."
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Extraherar sidor från inmatningsfilen och sparar som en ny Pdf-fil.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings-Pdf-filsökväg. |
| startPage | Int32 | Start page number. |
| endPage | Int32 | End page number. |
| outputFile | String | Utdata Pdf-filsökväg. |

### Returvärde

Sant för framgång, annars falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Extraherar sidor som anges av en nummerarray och sparar som en ny PDF-fil.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Sökväg till inmatningsfil. |
| pageNumber | Int32[] | Index för sida utanför inmatningsfilen. |
| outputFile | String | Sökväg till utdatafil. |

### Returvärde

True om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extraherar sidor från inmatningsfilen och sparar som en ny Pdf-fil.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatningsfilström. |
| startPage | Int32 | Start page number. |
| endPage | Int32 | End page number. |
| outputStream | Stream | Utdata Pdf-filström. |

### Returvärde

Sant för framgång, annars falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extraherar sidor som anges av en nummerarray och sparar som en ny Pdf-fil.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatningsfilström. |
| pageNumber | Int32[] | Index för sida utanför inmatningsfilen. |
| outputStream | Stream | Utdatafilström. |

### Returvärde

Sant för framgång, annars falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


