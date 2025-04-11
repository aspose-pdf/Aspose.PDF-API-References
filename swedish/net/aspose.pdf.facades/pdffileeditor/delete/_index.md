---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Tar bort sidor som anges av nummerarray från indatafilen och sparar som en ny Pdf-fil
type: docs
weight: 270
url: /sv/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Tar bort sidor som anges av nummerarray från indatafilen, sparar som en ny Pdf-fil.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till indatafil. |
| pageNumber | Int32[] | Index för sidan i indatafilen. |
| outputFile | Sträng | Sökväg till utdatafil. |

### Returvärde

Sant om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Tar bort sidor som anges av nummerarray från indatafilen, sparar som en ny Pdf-fil.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafilens Stream. |
| pageNumber | Int32[] | Index för sidan i indatafilen. |
| outputStream | Stream | Utdatafilens stream. |

### Returvärde

Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)