---
title: "PdfFileEditor.TryDelete"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor‑metod. Tar bort sidor som anges av en talarray från inmatningsfilen och sparar som en ny Pdf‑fil"
type: docs
weight: 400
url: /sv/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Tar bort sidor som anges av en nummerarray från inmatningsfilen och sparar som en ny Pdf-fil.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Sökväg till inmatningsfil. |
| pageNumber | Int32[] | Index för sida utanför inmatningsfilen. |
| outputFile | String | Sökväg till utdatafil. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryDelete fungerar som Delete-metoden, men TryDelete kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Tar bort sidor som anges av en nummerarray från inmatningsfilen och sparar som en ny Pdf-fil.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatningsfilström. |
| pageNumber | Int32[] | Index för sida utanför inmatningsfilen. |
| outputStream | Stream | Utdatafilström. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

Metoden TryDelete fungerar som Delete-metoden, men TryDelete kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


