---
title: TrySplitToEnd
second_title: Aspose.PDF för .NET API Referens
description: Delas från plats och sparar den bakre delen som en ny fil.
type: docs
weight: 500
url: /sv/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_2}

Delas från plats och sparar den bakre delen som en ny fil.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Källa pdf-fil. |
| location | Int32 | Klyvningsläget. |
| outputFile | String | Utdata pdf-fil sökväg. |

### Returvärde

Sant för framgång, eller falskt.

### Anmärkningar

Metoden TrySplitToEnd är som SplitToEnd-metoden, förutom att metoden TrySplitToEnd inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Delas från angiven plats och sparar den bakre delen som en ny fil Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Källa Pdf-fil Stream. |
| location | Int32 | Klyvningsläget. |
| outputStream | Stream | Utdata pdf-fil Stream. |

### Returvärde

Sant för framgång, eller falskt.

### Anmärkningar

Strömmarna stängs INTE efter denna operation om inte CloseConcatedStreams har specificerats. Metoden TrySplitToEnd är som SplitToEnd-metoden, förutom att metoden TrySplitToEnd inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Delas från angiven plats och sparar den bakre delen i HttpResponse-objekt.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Källdokumentström. |
| location | Int32 | Splitpunkt. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

Metoden TrySplitToEnd är som SplitToEnd-metoden, förutom att metoden TrySplitToEnd inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Delas från angiven plats och sparar den bakre delen i HttpResponse-objekt.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | källfilens namn. |
| location | Int32 | Splitpunkt. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

Metoden TrySplitToEnd är som SplitToEnd-metoden, förutom att metoden TrySplitToEnd inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->