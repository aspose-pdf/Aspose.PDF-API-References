---
title: "PdfFileEditor.TrySplitToEnd"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metod. Delar från plats och sparar den bakre delen som en ny fil."
type: docs
weight: 470
url: /sv/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Delar från plats och sparar den bakre delen som en ny fil.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Käll Pdf-fil. |
| plats | Int32 | Delningspositionen. |
| outputFile | String | Utdata Pdf-filsökväg. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

TrySplitToEnd-metoden är som SplitToEnd-metoden, förutom att TrySplitToEnd-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Delar från angiven plats och sparar den bakre delen som en ny fil Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Käll Pdf-filström. |
| plats | Int32 | Delningspositionen. |
| outputStream | Stream | Utdata Pdf-filström. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

Strömmarna är INTE stängda efter denna operation om inte CloseConcatedStreams anges. Metoden TrySplitToEnd är som metoden SplitToEnd, förutom att TrySplitToEnd inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


