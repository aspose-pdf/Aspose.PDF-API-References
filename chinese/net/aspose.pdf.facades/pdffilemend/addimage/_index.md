---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: PdfFileMend 方法。将图像添加到 PDF 文档的指定页面的指定坐标
type: docs
weight: 50
url: /zh/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

将图像添加到 PDF 文档的指定页面的指定坐标。

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 输入图像流。 |
| pageNum | Int32 | 将接收图像的页面编号。 |
| lowerLeftX | Single | 图像矩形的左下角 x 坐标。 |
| lowerLeftY | Single | 图像矩形的左下角 y 坐标。 |
| upperRightX | Single | 图像矩形的右上角 x 坐标。 |
| upperRightY | Single | 图像矩形的右上角 y 坐标。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### 另请参见

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

将图像添加到 PDF 文档的指定页面的指定坐标。

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 输入图像流。 |
| pageNum | Int32 | 将接收图像的页面编号。 |
| lowerLeftX | Single | 图像矩形的左下角 x 坐标。 |
| lowerLeftY | Single | 图像矩形的左下角 y 坐标。 |
| upperRightX | Single | 图像矩形的右上角 x 坐标。 |
| upperRightY | Single | 图像矩形的右上角 y 坐标。 |
| compositingParameters | CompositingParameters | 图像的图形合成参数。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### 另请参见

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

将图像添加到 PDF 文档的指定页面的指定坐标。

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 输入图像流。 |
| pageNums | Int32[] | 将接收图像的页面编号。 |
| lowerLeftX | Single | 图像矩形的左下角 x 坐标。 |
| lowerLeftY | Single | 图像矩形的左下角 y 坐标。 |
| upperRightX | Single | 图像矩形的右上角 x 坐标。 |
| upperRightY | Single | 图像矩形的右上角 y 坐标。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### 另请参见

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

将图像添加到 PDF 文档的指定页面的指定坐标。

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 输入图像流。 |
| pageNums | Int32[] | 将接收图像的页面编号。 |
| lowerLeftX | Single | 图像矩形的左下角 x 坐标。 |
| lowerLeftY | Single | 图像矩形的左下角 y 坐标。 |
| upperRightX | Single | 图像矩形的右上角 x 坐标。 |
| upperRightY | Single | 图像矩形的右上角 y 坐标。 |
| compositingParameters | CompositingParameters | 图像的图形合成参数。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### 另请参见

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

将图像添加到 PDF 文档的指定页面的指定坐标。

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageName | String | 输入图像文件的路径。 |
| pageNum | Int32 | 将接收图像的页面编号。 |
| lowerLeftX | Single | 图像矩形的左下角 x 坐标。 |
| lowerLeftY | Single | 图像矩形的左下角 y 坐标。 |
| upperRightX | Single | 图像矩形的右上角 x 坐标。 |
| upperRightY | Single | 图像矩形的右上角 y 坐标。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 另请参见

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

将图像添加到 PDF 文档的指定页面的指定坐标。

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageName | String | 输入图像文件的路径。 |
| pageNum | Int32 | 将接收图像的页面编号。 |
| lowerLeftX | Single | 图像矩形的左下角 x 坐标。 |
| lowerLeftY | Single | 图像矩形的左下角 y 坐标。 |
| upperRightX | Single | 图像矩形的右上角 x 坐标。 |
| upperRightY | Single | 图像矩形的右上角 y 坐标。 |
| compositingParameters | CompositingParameters | 图像的图形合成参数。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 另请参见

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

将图像添加到 PDF 文档的指定页面的指定坐标。

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageName | String | 输入图像文件的路径。 |
| pageNums | Int32[] | 将接收图像的页面编号。 |
| lowerLeftX | Single | 图像矩形的左下角 x 坐标。 |
| lowerLeftY | Single | 图像矩形的左下角 y 坐标。 |
| upperRightX | Single | 图像矩形的右上角 x 坐标。 |
| upperRightY | Single | 图像矩形的右上角 y 坐标。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 另请参见

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

将图像添加到 PDF 文档的指定页面的指定坐标。

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageName | String | 输入图像文件的路径。 |
| pageNums | Int32[] | 将接收图像的页面编号。 |
| lowerLeftX | Single | 图像矩形的左下角 x 坐标。 |
| lowerLeftY | Single | 图像矩形的左下角 y 坐标。 |
| upperRightX | Single | 图像矩形的右上角 x 坐标。 |
| upperRightY | Single | 图像矩形的右上角 y 坐标。 |
| compositingParameters | CompositingParameters | 图像的图形合成参数。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 另请参见

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)