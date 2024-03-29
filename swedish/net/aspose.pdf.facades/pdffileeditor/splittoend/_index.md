---
title: SplitToEnd
second_title: Aspose.PDF för .NET API Referens
description: Delas från plats och sparar den bakre delen som en ny fil.
type: docs
weight: 390
url: /sv/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_2}

Delas från plats och sparar den bakre delen som en ny fil.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Källa pdf-fil. |
| location | Int32 | Klyvningsläget. |
| outputFile | String | Utdata pdf-fil sökväg. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Delas från angiven plats och sparar den bakre delen som en ny fil Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Källa Pdf-fil Stream. |
| location | Int32 | Klyvningsläget. |
| outputStream | Stream | Utdata pdf-fil Stream. |

### Returvärde

Sant för framgång, eller falskt.

### Anmärkningar

Strömmarna stängs INTE efter denna operation om inte CloseConcatedStreams har specificerats.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, HttpResponse) {#splittoend_1}

Delas från angiven plats och sparar den bakre delen i HttpResponse-objekt.

```csharp
public bool SplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Källdokumentström. |
| location | Int32 | Splitpunkt. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

sant om uppdelningen lyckades.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, HttpResponse) {#splittoend_3}

Delas från angiven plats och sparar den bakre delen i HttpResponse-objekt.

```csharp
public bool SplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | källfilens namn. |
| location | Int32 | Splitpunkt. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

Sant om operationen lyckades.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
