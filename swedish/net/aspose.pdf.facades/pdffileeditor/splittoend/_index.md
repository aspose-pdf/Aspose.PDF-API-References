---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Delar från plats och sparar den bakre delen som en ny fil
type: docs
weight: 360
url: /sv/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Delar från angiven plats och sparar den bakre delen som en ny filström.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Käll Pdf-filström. |
| location | Int32 | Delningspositionen. |
| outputStream | Stream | Utdata Pdf-filström. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

Strömmarna stängs INTE efter denna operation om inte CloseConcatedStreams anges.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Delar från plats och sparar den bakre delen som en ny fil.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Käll Pdf-fil. |
| location | Int32 | Delningspositionen. |
| outputFile | String | Utdata Pdf-filväg. |

### Returvärde

Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Delar från angiven plats och sparar den bakre delen som en ny filström.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Käll Pdf-filström. |
| location | Int32 | Delningspositionen. |
| outputStream | Stream | Utdata Pdf-filström. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

Strömmarna stängs INTE efter denna operation om inte CloseConcatedStreams anges.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)