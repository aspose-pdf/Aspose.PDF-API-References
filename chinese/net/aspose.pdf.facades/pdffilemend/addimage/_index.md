---
title: AddImage
second_title: Aspose.PDF for .NET API 参考
description: 在指定坐标处将图像添加到 PDF 文档的指定页面
type: docs
weight: 50
url: /zh/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

在指定坐标处将图像添加到 PDF 文档的指定页面。

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 输入图像流。 |
| pageNum | Int32 | 将接收图像的页数。 |
| lowerLeftX | Single | 图像矩形的左下角 x。 |
| lowerLeftY | Single | 图像矩形的左下 y。 |
| upperRightX | Single | 图像矩形的右上角 x。 |
| upperRightY | Single | 图像矩形的右上角 y。 |

### 返回值

如果成功则为真，否则为假。

### 例子

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### 也可以看看

* class [PdfFileMend](../../pdffilemend)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilemend)
* 部件 [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

在指定坐标处将图像添加到 PDF 文档的指定页面。

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 输入图像流。 |
| pageNum | Int32 | 将接收图像的页数。 |
| lowerLeftX | Single | 图像矩形的左下角 x。 |
| lowerLeftY | Single | 图像矩形的左下 y。 |
| upperRightX | Single | 图像矩形的右上角 x。 |
| upperRightY | Single | 图像矩形的右上角 y。 |
| compositingParameters | CompositingParameters | 图像的图形合成参数。 |

### 返回值

如果成功则为真，否则为假。

### 例子

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### 也可以看看

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilemend)
* 部件 [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

在指定坐标处将图像添加到 PDF 文档的指定页面。

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 输入图像流。 |
| pageNums | Int32[] | 将接收图像的页数。 |
| lowerLeftX | Single | 图像矩形的左下角 x。 |
| lowerLeftY | Single | 图像矩形的左下 y。 |
| upperRightX | Single | 图像矩形的右上角 x。 |
| upperRightY | Single | 图像矩形的右上角 y。 |

### 返回值

如果成功则为真，否则为假。

### 例子

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### 也可以看看

* class [PdfFileMend](../../pdffilemend)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilemend)
* 部件 [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

在指定坐标处将图像添加到 PDF 文档的指定页面。

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 输入图像流。 |
| pageNums | Int32[] | 将接收图像的页数。 |
| lowerLeftX | Single | 图像矩形的左下角 x。 |
| lowerLeftY | Single | 图像矩形的左下 y。 |
| upperRightX | Single | 图像矩形的右上角 x。 |
| upperRightY | Single | 图像矩形的右上角 y。 |
| compositingParameters | CompositingParameters | 图像的图形合成参数。 |

### 返回值

如果成功则为真，否则为假。

### 例子

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### 也可以看看

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilemend)
* 部件 [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

在指定坐标处将图像添加到 PDF 文档的指定页面。

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | String | 输入图像文件的路径。 |
| pageNum | Int32 | 将接收图像的页数。 |
| lowerLeftX | Single | 图像矩形的左下角 x。 |
| lowerLeftY | Single | 图像矩形的左下 y。 |
| upperRightX | Single | 图像矩形的右上角 x。 |
| upperRightY | Single | 图像矩形的右上角 y。 |

### 返回值

如果成功则为真，否则为假。

### 例子

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 也可以看看

* class [PdfFileMend](../../pdffilemend)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilemend)
* 部件 [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

在指定坐标处将图像添加到 PDF 文档的指定页面。

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | String | 输入图像文件的路径。 |
| pageNum | Int32 | 将接收图像的页数。 |
| lowerLeftX | Single | 图像矩形的左下角 x。 |
| lowerLeftY | Single | 图像矩形的左下 y。 |
| upperRightX | Single | 图像矩形的右上角 x。 |
| upperRightY | Single | 图像矩形的右上角 y。 |
| compositingParameters | CompositingParameters | 图像的图形合成参数。 |

### 返回值

如果成功则为真，否则为假。

### 例子

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 也可以看看

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilemend)
* 部件 [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

在指定坐标处将图像添加到 PDF 文档的指定页面。

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | String | 输入图像文件的路径。 |
| pageNums | Int32[] | 将接收图像的页数。 |
| lowerLeftX | Single | 图像矩形的左下角 x。 |
| lowerLeftY | Single | 图像矩形的左下 y。 |
| upperRightX | Single | 图像矩形的右上角 x。 |
| upperRightY | Single | 图像矩形的右上角 y。 |

### 返回值

如果成功则为真，否则为假。

### 例子

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 也可以看看

* class [PdfFileMend](../../pdffilemend)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilemend)
* 部件 [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

在指定坐标处将图像添加到 PDF 文档的指定页面。

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | String | 输入图像文件的路径。 |
| pageNums | Int32[] | 将接收图像的页数。 |
| lowerLeftX | Single | 图像矩形的左下角 x。 |
| lowerLeftY | Single | 图像矩形的左下 y。 |
| upperRightX | Single | 图像矩形的右上角 x。 |
| upperRightY | Single | 图像矩形的右上角 y。 |
| compositingParameters | CompositingParameters | 图像的图形合成参数。 |

### 返回值

如果成功则为真，否则为假。

### 例子

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 也可以看看

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilemend)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
