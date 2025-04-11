---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Dela Pdf-fil från första sidan till angiven plats och spara den främre delen som en ny fil
type: docs
weight: 340
url: /sv/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Dela Pdf-fil från första sidan till angiven plats och spara den främre delen som en ny fil.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Käll Pdf-fil. |
| location | Int32 | Delningspunkt. |
| outputFile | Sträng | Utdata Pdf-fil. |

### Returvärde

Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Dela från början till angiven plats och spara den främre delen i utdata Stream.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Käll Pdf-fil Stream. |
| location | Int32 | Delningspunkt. |
| outputStream | Stream | Utdata fil Stream. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

Strömmarna stängs INTE efter denna operation.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)