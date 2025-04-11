---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 方法。向文档的页面添加页脚
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

向文档的页面添加页脚。

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 包含页脚文本和文本属性的 FormattedText 对象。 |
| bottomMargin | Single | 页面底部的边距。 |

## 示例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### 另请参阅

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

向文档的页面添加页脚。

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 包含页脚文本和文本属性的 FormattedText 对象。 |
| bottomMargin | Single | 页面底部的边距。 |
| leftMargin | Single | 页面左侧的边距。 |
| rightMargin | Single | 页面右侧的边距。 |

## 示例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### 另请参阅

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

将图像作为页脚添加到文档的页面。

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | String | 图像文件名和路径。 |
| bottomMargin | Single | 页面底部的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### 另请参阅

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

将图像作为页面的页脚添加。

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | String | 图像文件名和路径。 |
| bottomMargin | Single | 页面底部的边距。 |
| leftMargin | Single | 页面左侧的边距。 |
| rightMargin | Single | 页面右侧的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### 另请参阅

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

将图像作为页面的页脚添加。

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 包含图像数据的流。 |
| bottomMargin | Single | 页面底部的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### 另请参阅

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

将图像作为页面的页脚添加。

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 包含图像数据的流。 |
| bottomMargin | Single | 页面底部的边距。 |
| leftMargin | Single | 页面左侧的边距。 |
| rightMargin | Single | 页面右侧的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### 另请参阅

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)