---
title: "PdfFileEditor.TryExtract"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metod. Extraherar pages från input file och sparar som en ny Pdf file."
type: docs
weight: 410
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Extraherar sidor från inmatningsfilen och sparar som en ny Pdf-fil.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings-Pdf-filsökväg. |
| startPage | Int32 | Start page number. |
| endPage | Int32 | End page number. |
| outputFile | String | Utdata Pdf-filsökväg. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

TryExtract-metoden är som Extract-metoden, förutom att TryExtract-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Extraherar sidor som anges av en nummerarray och sparar som en ny PDF-fil.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Sökväg till inmatningsfil. |
| pageNumber | Int32[] | Index för sida utanför inmatningsfilen. |
| outputFile | String | Sökväg till utdatafil. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

TryExtract-metoden är som Extract-metoden, förutom att TryExtract-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extraherar sidor som anges av en nummerarray och sparar som en ny Pdf-fil.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatningsfilström. |
| pageNumber | Int32[] | Index för sida utanför inmatningsfilen. |
| outputStream | Stream | Utdatafilström. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

TryExtract-metoden är som Extract-metoden, förutom att TryExtract-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


