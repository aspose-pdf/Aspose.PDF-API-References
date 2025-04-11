---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: PdfFileMend-metod. Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater
type: docs
weight: 50
url: /sv/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Inmatningsbildström. |
| pageNum | Int32 | Numret på sidan som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x av bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y av bildrektangeln. |
| upperRightX | Single | Den övre högra x av bildrektangeln. |
| upperRightY | Single | Den övre högra y av bildrektangeln. |

### Returvärde

Sant om framgång, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Se Även

* klass [PdfFileMend](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Inmatningsbildström. |
| pageNum | Int32 | Numret på sidan som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x av bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y av bildrektangeln. |
| upperRightX | Single | Den övre högra x av bildrektangeln. |
| upperRightY | Single | Den övre högra y av bildrektangeln. |
| compositingParameters | CompositingParameters | Grafiska sammansättningsparametrar för bilden. |

### Returvärde

Sant om framgång, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Se Även

* klass [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* klass [PdfFileMend](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Lägger till bild på de angivna sidorna av PDF-dokumentet vid angivna koordinater.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Inmatningsbildström. |
| pageNums | Int32[] | Numren på sidorna som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x av bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y av bildrektangeln. |
| upperRightX | Single | Den övre högra x av bildrektangeln. |
| upperRightY | Single | Den övre högra y av bildrektangeln. |

### Returvärde

Sant om framgång, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Se Även

* klass [PdfFileMend](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Lägger till bild på de angivna sidorna av PDF-dokumentet vid angivna koordinater.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Inmatningsbildström. |
| pageNums | Int32[] | Numren på sidorna som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x av bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y av bildrektangeln. |
| upperRightX | Single | Den övre högra x av bildrektangeln. |
| upperRightY | Single | Den övre högra y av bildrektangeln. |
| compositingParameters | CompositingParameters | Grafiska sammansättningsparametrar för bilderna. |

### Returvärde

Sant om framgång, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Se Även

* klass [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* klass [PdfFileMend](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | String | Sökvägen till inmatningsbildfilen. |
| pageNum | Int32 | Numret på sidan som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x av bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y av bildrektangeln. |
| upperRightX | Single | Den övre högra x av bildrektangeln. |
| upperRightY | Single | Den övre högra y av bildrektangeln. |

### Returvärde

Sant om framgång, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Se Även

* klass [PdfFileMend](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | String | Sökvägen till inmatningsbildfilen. |
| pageNum | Int32 | Numret på sidan som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x av bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y av bildrektangeln. |
| upperRightX | Single | Den övre högra x av bildrektangeln. |
| upperRightY | Single | Den övre högra y av bildrektangeln. |
| compositingParameters | CompositingParameters | Grafiska sammansättningsparametrar för bilderna. |

### Returvärde

Sant om framgång, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Se Även

* klass [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* klass [PdfFileMend](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Lägger till bild på de angivna sidorna av PDF-dokumentet vid angivna koordinater.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | String | Sökvägen till inmatningsbildfilen. |
| pageNums | Int32[] | Numren på sidorna som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x av bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y av bildrektangeln. |
| upperRightX | Single | Den övre högra x av bildrektangeln. |
| upperRightY | Single | Den övre högra y av bildrektangeln. |

### Returvärde

Sant om framgång, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Se Även

* klass [PdfFileMend](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Lägger till bild på de angivna sidorna av PDF-dokumentet vid angivna koordinater.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | String | Sökvägen till inmatningsbildfilen. |
| pageNums | Int32[] | Numren på sidorna som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x av bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y av bildrektangeln. |
| upperRightX | Single | Den övre högra x av bildrektangeln. |
| upperRightY | Single | Den övre högra y av bildrektangeln. |
| compositingParameters | CompositingParameters | Grafiska sammansättningsparametrar för bilderna. |

### Returvärde

Sant om framgång, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Se Även

* klass [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* klass [PdfFileMend](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)