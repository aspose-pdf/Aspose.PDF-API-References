---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Delar från plats och sparar den bakre delen som en ny fil
type: docs
weight: 470
url: /sv/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Delar från plats, och sparar den bakre delen som en ny fil.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Käll Pdf-fil. |
| location | Int32 | Delningsposition. |
| outputFile | Sträng | Utdata Pdf-filens sökväg. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

TrySplitToEnd-metoden är som SplitToEnd-metoden, förutom att TrySplitToEnd-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Delar från angiven plats, och sparar den bakre delen som en ny fil Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Käll Pdf-fil Stream. |
| location | Int32 | Delningsposition. |
| outputStream | Stream | Utdata Pdf-fil Stream. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

Strömmarna stängs INTE efter denna operation om inte CloseConcatedStreams anges. TrySplitToEnd-metoden är som SplitToEnd-metoden, förutom att TrySplitToEnd-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Delar från angiven plats, och sparar den bakre delen i HttpResponse-objektet.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Käll dokumentström. |
| location | Int32 | Delningspunkt. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TrySplitToEnd-metoden är som SplitToEnd-metoden, förutom att TrySplitToEnd-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Delar från angiven plats, och sparar den bakre delen i HttpResponse-objektet.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | källfilens namn. |
| location | Int32 | Delningspunkt. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TrySplitToEnd-metoden är som SplitToEnd-metoden, förutom att TrySplitToEnd-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)