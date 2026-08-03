---
title: "PdfFileEditor.Delete"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor‑metod. Tar bort sidor som anges av en talarray från inmatningsfilen och sparar som en ny Pdf‑fil"
type: docs
weight: 270
url: /sv/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Tar bort sidor som anges av en nummerarray från inmatningsfilen och sparar som en ny Pdf-fil.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
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
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Tar bort sidor som anges av en nummerarray från inmatningsfilen och sparar som en ny Pdf-fil.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
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
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


