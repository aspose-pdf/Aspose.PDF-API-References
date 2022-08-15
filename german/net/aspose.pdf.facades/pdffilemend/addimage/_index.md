---
title: AddImage
second_title: Aspose.PDF für .NET-API-Referenz
description: Fügt der angegebenen Seite des PDF-Dokuments ein Bild an den angegebenen Koordinaten hinzu.
type: docs
weight: 50
url: /de/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Fügt der angegebenen Seite des PDF-Dokuments ein Bild an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Bildstrom eingeben. |
| pageNum | Int32 | Die Anzahl der Seiten, die das Bild erhalten. |
| lowerLeftX | Single | Das untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Das untere linke y des Bildrechtecks. |
| upperRightX | Single | Das obere rechte x des Bildrechtecks. |
| upperRightY | Single | Das obere rechte y des Bildrechtecks. |

### Rückgabewert

Wahr, wenn Erfolg, sonst falsch.

### Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Siehe auch

* class [PdfFileMend](../../pdffilemend)
* namensraum [Aspose.Pdf.Facades](../../pdffilemend)
* Montage [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Fügt der angegebenen Seite des PDF-Dokuments ein Bild an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Bildstrom eingeben. |
| pageNum | Int32 | Die Anzahl der Seiten, die das Bild erhalten. |
| lowerLeftX | Single | Das untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Das untere linke y des Bildrechtecks. |
| upperRightX | Single | Das obere rechte x des Bildrechtecks. |
| upperRightY | Single | Das obere rechte y des Bildrechtecks. |
| compositingParameters | CompositingParameters | Die Grafik-Compositing-Parameter für das Bild. |

### Rückgabewert

Wahr, wenn Erfolg, sonst falsch.

### Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Siehe auch

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* namensraum [Aspose.Pdf.Facades](../../pdffilemend)
* Montage [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Bildstrom eingeben. |
| pageNums | Int32[] | Die Anzahl der Seiten, die das Bild erhalten. |
| lowerLeftX | Single | Das untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Das untere linke y des Bildrechtecks. |
| upperRightX | Single | Das obere rechte x des Bildrechtecks. |
| upperRightY | Single | Das obere rechte y des Bildrechtecks. |

### Rückgabewert

Wahr, wenn Erfolg, sonst falsch.

### Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Siehe auch

* class [PdfFileMend](../../pdffilemend)
* namensraum [Aspose.Pdf.Facades](../../pdffilemend)
* Montage [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Bildstrom eingeben. |
| pageNums | Int32[] | Die Anzahl der Seiten, die das Bild erhalten. |
| lowerLeftX | Single | Das untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Das untere linke y des Bildrechtecks. |
| upperRightX | Single | Das obere rechte x des Bildrechtecks. |
| upperRightY | Single | Das obere rechte y des Bildrechtecks. |
| compositingParameters | CompositingParameters | Die Grafik-Compositing-Parameter für die Bilder. |

### Rückgabewert

Wahr, wenn Erfolg, sonst falsch.

### Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Siehe auch

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* namensraum [Aspose.Pdf.Facades](../../pdffilemend)
* Montage [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Fügt der angegebenen Seite des PDF-Dokuments ein Bild an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageName | String | Der Pfad der Eingabebilddatei. |
| pageNum | Int32 | Die Anzahl der Seiten, die das Bild erhalten. |
| lowerLeftX | Single | Das untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Das untere linke y des Bildrechtecks. |
| upperRightX | Single | Das obere rechte x des Bildrechtecks. |
| upperRightY | Single | Das obere rechte y des Bildrechtecks. |

### Rückgabewert

Wahr, wenn Erfolg, sonst falsch.

### Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Siehe auch

* class [PdfFileMend](../../pdffilemend)
* namensraum [Aspose.Pdf.Facades](../../pdffilemend)
* Montage [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Fügt der angegebenen Seite des PDF-Dokuments ein Bild an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageName | String | Der Pfad der Eingabebilddatei. |
| pageNum | Int32 | Die Anzahl der Seiten, die das Bild erhalten. |
| lowerLeftX | Single | Das untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Das untere linke y des Bildrechtecks. |
| upperRightX | Single | Das obere rechte x des Bildrechtecks. |
| upperRightY | Single | Das obere rechte y des Bildrechtecks. |
| compositingParameters | CompositingParameters | Die Grafik-Compositing-Parameter für die Bilder. |

### Rückgabewert

Wahr, wenn Erfolg, sonst falsch.

### Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Siehe auch

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* namensraum [Aspose.Pdf.Facades](../../pdffilemend)
* Montage [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageName | String | Der Pfad der Eingabebilddatei. |
| pageNums | Int32[] | Die Anzahl der Seiten, die das Bild erhalten. |
| lowerLeftX | Single | Das untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Das untere linke y des Bildrechtecks. |
| upperRightX | Single | Das obere rechte x des Bildrechtecks. |
| upperRightY | Single | Das obere rechte y des Bildrechtecks. |

### Rückgabewert

Wahr, wenn Erfolg, sonst falsch.

### Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Siehe auch

* class [PdfFileMend](../../pdffilemend)
* namensraum [Aspose.Pdf.Facades](../../pdffilemend)
* Montage [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageName | String | Der Pfad der Eingabebilddatei. |
| pageNums | Int32[] | Die Anzahl der Seiten, die das Bild erhalten. |
| lowerLeftX | Single | Das untere linke x des Bildrechtecks. |
| lowerLeftY | Single | Das untere linke y des Bildrechtecks. |
| upperRightX | Single | Das obere rechte x des Bildrechtecks. |
| upperRightY | Single | Das obere rechte y des Bildrechtecks. |
| compositingParameters | CompositingParameters | Die Grafik-Compositing-Parameter für die Bilder. |

### Rückgabewert

Wahr, wenn Erfolg, sonst falsch.

### Beispiele

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Siehe auch

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* namensraum [Aspose.Pdf.Facades](../../pdffilemend)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
