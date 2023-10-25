---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: PdfFileMend method. Adds image to the specified page of PDF document at specified coordinates
type: docs
weight: 50
url: /net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Adds image to the specified page of PDF document at specified coordinates.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Input image stream. |
| pageNum | Int32 | The number of page that will receive the image. |
| lowerLeftX | Single | The lower left x of image rectangle. |
| lowerLeftY | Single | The lower left y of image rectangle. |
| upperRightX | Single | The upper right x of image rectangle. |
| upperRightY | Single | The upper right y of image rectangle. |

### Return Value

True if success false otherwise.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### See Also

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Adds image to the specified page of PDF document at specified coordinates.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Input image stream. |
| pageNum | Int32 | The number of page that will receive the image. |
| lowerLeftX | Single | The lower left x of image rectangle. |
| lowerLeftY | Single | The lower left y of image rectangle. |
| upperRightX | Single | The upper right x of image rectangle. |
| upperRightY | Single | The upper right y of image rectangle. |
| compositingParameters | CompositingParameters | The graphics compositing parameters for the image. |

### Return Value

True if success false otherwise.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### See Also

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Adds image to the specified pages of PDF document at specified coordinates.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Input image stream. |
| pageNums | Int32[] | The numbers of pages that will receive the image. |
| lowerLeftX | Single | The lower left x of image rectangle. |
| lowerLeftY | Single | The lower left y of image rectangle. |
| upperRightX | Single | The upper right x of image rectangle. |
| upperRightY | Single | The upper right y of image rectangle. |

### Return Value

True if success false otherwise.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### See Also

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Adds image to the specified pages of PDF document at specified coordinates.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Input image stream. |
| pageNums | Int32[] | The numbers of pages that will receive the image. |
| lowerLeftX | Single | The lower left x of image rectangle. |
| lowerLeftY | Single | The lower left y of image rectangle. |
| upperRightX | Single | The upper right x of image rectangle. |
| upperRightY | Single | The upper right y of image rectangle. |
| compositingParameters | CompositingParameters | The graphics compositing parameters for the images. |

### Return Value

True if success false otherwise.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### See Also

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Adds image to the specified page of PDF document at specified coordinates.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageName | String | The path of input image file. |
| pageNum | Int32 | The number of page that will receive the image. |
| lowerLeftX | Single | The lower left x of image rectangle. |
| lowerLeftY | Single | The lower left y of image rectangle. |
| upperRightX | Single | The upper right x of image rectangle. |
| upperRightY | Single | The upper right y of image rectangle. |

### Return Value

True if success false otherwise.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### See Also

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Adds image to the specified page of PDF document at specified coordinates.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageName | String | The path of input image file. |
| pageNum | Int32 | The number of page that will receive the image. |
| lowerLeftX | Single | The lower left x of image rectangle. |
| lowerLeftY | Single | The lower left y of image rectangle. |
| upperRightX | Single | The upper right x of image rectangle. |
| upperRightY | Single | The upper right y of image rectangle. |
| compositingParameters | CompositingParameters | The graphics compositing parameters for the images. |

### Return Value

True if success false otherwise.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### See Also

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Adds image to the specified pages of PDF document at specified coordinates.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageName | String | The path of input image file. |
| pageNums | Int32[] | The numbers of pages that will receive the image. |
| lowerLeftX | Single | The lower left x of image rectangle. |
| lowerLeftY | Single | The lower left y of image rectangle. |
| upperRightX | Single | The upper right x of image rectangle. |
| upperRightY | Single | The upper right y of image rectangle. |

### Return Value

True if success false otherwise.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### See Also

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Adds image to the specified pages of PDF document at specified coordinates.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageName | String | The path of input image file. |
| pageNums | Int32[] | The numbers of pages that will receive the image. |
| lowerLeftX | Single | The lower left x of image rectangle. |
| lowerLeftY | Single | The lower left y of image rectangle. |
| upperRightX | Single | The upper right x of image rectangle. |
| upperRightY | Single | The upper right y of image rectangle. |
| compositingParameters | CompositingParameters | The graphics compositing parameters for the images. |

### Return Value

True if success false otherwise.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### See Also

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


