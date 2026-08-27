---
title: "PdfFileMend.AddImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileMend-metoden. Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater"
type: docs
weight: 50
url: /sv/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Inmatningsström för bild. |
| pageNum | Int32 | Numret på sidan som ska ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x-koordinaten för bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y-koordinaten för bildrektangeln. |
| upperRightX | Single | Den övre högra x-koordinaten för bildrektangeln. |
| upperRightY | Single | Den övre högra y-koordinaten för bildrektangeln. |

### Returvärde

Sant om lyckat, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Se även

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Inmatningsström för bild. |
| pageNum | Int32 | Numret på sidan som ska ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x-koordinaten för bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y-koordinaten för bildrektangeln. |
| upperRightX | Single | Den övre högra x-koordinaten för bildrektangeln. |
| upperRightY | Single | Den övre högra y-koordinaten för bildrektangeln. |
| compositingParameters | CompositingParameters | Grafiska sammansättningsparametrar för bilden. |

### Returvärde

Sant om lyckat, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Se även

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Inmatningsström för bild. |
| pageNums | Int32[] | Antalet sidor som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x-koordinaten för bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y-koordinaten för bildrektangeln. |
| upperRightX | Single | Den övre högra x-koordinaten för bildrektangeln. |
| upperRightY | Single | Den övre högra y-koordinaten för bildrektangeln. |

### Returvärde

Sant om lyckat, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Se även

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Inmatningsström för bild. |
| pageNums | Int32[] | Antalet sidor som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x-koordinaten för bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y-koordinaten för bildrektangeln. |
| upperRightX | Single | Den övre högra x-koordinaten för bildrektangeln. |
| upperRightY | Single | Den övre högra y-koordinaten för bildrektangeln. |
| compositingParameters | CompositingParameters | Grafiska sammansättningsparametrar för bilderna. |

### Returvärde

Sant om lyckat, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Se även

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | String | Sökvägen till inmatningsbildfilen. |
| pageNum | Int32 | Numret på sidan som ska ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x-koordinaten för bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y-koordinaten för bildrektangeln. |
| upperRightX | Single | Den övre högra x-koordinaten för bildrektangeln. |
| upperRightY | Single | Den övre högra y-koordinaten för bildrektangeln. |

### Returvärde

Sant om lyckat, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Se även

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | String | Sökvägen till inmatningsbildfilen. |
| pageNum | Int32 | Numret på sidan som ska ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x-koordinaten för bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y-koordinaten för bildrektangeln. |
| upperRightX | Single | Den övre högra x-koordinaten för bildrektangeln. |
| upperRightY | Single | Den övre högra y-koordinaten för bildrektangeln. |
| compositingParameters | CompositingParameters | Grafiska sammansättningsparametrar för bilderna. |

### Returvärde

Sant om lyckat, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Se även

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | String | Sökvägen till inmatningsbildfilen. |
| pageNums | Int32[] | Antalet sidor som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x-koordinaten för bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y-koordinaten för bildrektangeln. |
| upperRightX | Single | Den övre högra x-koordinaten för bildrektangeln. |
| upperRightY | Single | Den övre högra y-koordinaten för bildrektangeln. |

### Returvärde

Sant om lyckat, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Se även

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | String | Sökvägen till inmatningsbildfilen. |
| pageNums | Int32[] | Antalet sidor som kommer att ta emot bilden. |
| lowerLeftX | Single | Den nedre vänstra x-koordinaten för bildrektangeln. |
| lowerLeftY | Single | Den nedre vänstra y-koordinaten för bildrektangeln. |
| upperRightX | Single | Den övre högra x-koordinaten för bildrektangeln. |
| upperRightY | Single | Den övre högra y-koordinaten för bildrektangeln. |
| compositingParameters | CompositingParameters | Grafiska sammansättningsparametrar för bilderna. |

### Returvärde

Sant om lyckat, falskt annars.

## Exempel

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Se även

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


