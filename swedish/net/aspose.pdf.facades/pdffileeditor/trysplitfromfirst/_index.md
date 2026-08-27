---
title: "PdfFileEditor.TrySplitFromFirst"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metod. Delar PDF-fil från första sidan till angiven plats och sparar den främre delen som en ny fil"
type: docs
weight: 460
url: /sv/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Delar Pdf-filen från första sidan till angiven plats och sparar den främre delen som en ny fil.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Käll Pdf-fil. |
| plats | Int32 | Delningspunkten. |
| outputFile | String | Utdata‑Pdf‑fil. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

Metoden TrySplitFromFirst är som metoden SplitFromFirst, förutom att metoden TrySplitFromFirst inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Delar från början till angiven plats och sparar den främre delen i output Stream.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Käll Pdf-filström. |
| plats | Int32 | Delningspunkten. |
| outputStream | Stream | Utdatafilström. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

Strömmarna stängs INTE efter denna operation. Metoden TrySplitFromFirst är som metoden SplitFromFirst, förutom att metoden TrySplitFromFirst inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


