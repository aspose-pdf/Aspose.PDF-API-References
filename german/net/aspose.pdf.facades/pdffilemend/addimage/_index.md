---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: PdfFileMend-Methode. Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu
type: docs
weight: 50
url: /de/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Eingabebildstream. |
| pageNum | Int32 | Die Nummer der Seite, die das Bild erhalten wird. |
| lowerLeftX | Single | Der untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Der untere linke y des Bildrechtecks. |
| upperRightX | Single | Der obere rechte x des Bildrechtecks. |
| upperRightY | Single | Der obere rechte y des Bildrechtecks. |

### Rückgabewert

Wahr, wenn erfolgreich, falsch andernfalls.

## Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Siehe auch

* Klasse [PdfFileMend](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Eingabebildstream. |
| pageNum | Int32 | Die Nummer der Seite, die das Bild erhalten wird. |
| lowerLeftX | Single | Der untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Der untere linke y des Bildrechtecks. |
| upperRightX | Single | Der obere rechte x des Bildrechtecks. |
| upperRightY | Single | Der obere rechte y des Bildrechtecks. |
| compositingParameters | CompositingParameters | Die Grafikkompositionsparameter für das Bild. |

### Rückgabewert

Wahr, wenn erfolgreich, falsch andernfalls.

## Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Siehe auch

* Klasse [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Klasse [PdfFileMend](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Eingabebildstream. |
| pageNums | Int32[] | Die Nummern der Seiten, die das Bild erhalten werden. |
| lowerLeftX | Single | Der untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Der untere linke y des Bildrechtecks. |
| upperRightX | Single | Der obere rechte x des Bildrechtecks. |
| upperRightY | Single | Der obere rechte y des Bildrechtecks. |

### Rückgabewert

Wahr, wenn erfolgreich, falsch andernfalls.

## Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Siehe auch

* Klasse [PdfFileMend](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Eingabebildstream. |
| pageNums | Int32[] | Die Nummern der Seiten, die das Bild erhalten werden. |
| lowerLeftX | Single | Der untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Der untere linke y des Bildrechtecks. |
| upperRightX | Single | Der obere rechte x des Bildrechtecks. |
| upperRightY | Single | Der obere rechte y des Bildrechtecks. |
| compositingParameters | CompositingParameters | Die Grafikkompositionsparameter für die Bilder. |

### Rückgabewert

Wahr, wenn erfolgreich, falsch andernfalls.

## Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Siehe auch

* Klasse [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Klasse [PdfFileMend](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageName | String | Der Pfad zur Eingabebilddatei. |
| pageNum | Int32 | Die Nummer der Seite, die das Bild erhalten wird. |
| lowerLeftX | Single | Der untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Der untere linke y des Bildrechtecks. |
| upperRightX | Single | Der obere rechte x des Bildrechtecks. |
| upperRightY | Single | Der obere rechte y des Bildrechtecks. |

### Rückgabewert

Wahr, wenn erfolgreich, falsch andernfalls.

## Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Siehe auch

* Klasse [PdfFileMend](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageName | String | Der Pfad zur Eingabebilddatei. |
| pageNum | Int32 | Die Nummer der Seite, die das Bild erhalten wird. |
| lowerLeftX | Single | Der untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Der untere linke y des Bildrechtecks. |
| upperRightX | Single | Der obere rechte x des Bildrechtecks. |
| upperRightY | Single | Der obere rechte y des Bildrechtecks. |
| compositingParameters | CompositingParameters | Die Grafikkompositionsparameter für die Bilder. |

### Rückgabewert

Wahr, wenn erfolgreich, falsch andernfalls.

## Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Siehe auch

* Klasse [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Klasse [PdfFileMend](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageName | String | Der Pfad zur Eingabebilddatei. |
| pageNums | Int32[] | Die Nummern der Seiten, die das Bild erhalten werden. |
| lowerLeftX | Single | Der untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Der untere linke y des Bildrechtecks. |
| upperRightX | Single | Der obere rechte x des Bildrechtecks. |
| upperRightY | Single | Der obere rechte y des Bildrechtecks. |

### Rückgabewert

Wahr, wenn erfolgreich, falsch andernfalls.

## Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Siehe auch

* Klasse [PdfFileMend](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageName | String | Der Pfad zur Eingabebilddatei. |
| pageNums | Int32[] | Die Nummern der Seiten, die das Bild erhalten werden. |
| lowerLeftX | Single | Der untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Der untere linke y des Bildrechtecks. |
| upperRightX | Single | Der obere rechte x des Bildrechtecks. |
| upperRightY | Single | Der obere rechte y des Bildrechtecks. |
| compositingParameters | CompositingParameters | Die Grafikkompositionsparameter für die Bilder. |

### Rückgabewert

Wahr, wenn erfolgreich, falsch andernfalls.

## Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Siehe auch

* Klasse [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Klasse [PdfFileMend](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)