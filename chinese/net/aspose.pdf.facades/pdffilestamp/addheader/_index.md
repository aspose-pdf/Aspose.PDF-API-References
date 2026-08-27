---
title: "PdfFileStamp.AddHeader"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileStamp 方法。向页面添加页眉"
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

在页面添加页眉。

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 页眉文本和文本属性。 |
| topMargin | Single | 页面顶部的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### 另请参见

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

在文件的页面添加页眉。

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 格式化文本对象，包含页面文本及其属性。 |
| topMargin | Single | 页面顶部的边距。 |
| leftMargin | Single | 页面左侧的边距。 |
| rightMargin | Single | 页面右侧的边距。 |

## 示例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### 另请参见

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

将图像添加为文件页面的页眉。

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | String | 图像文件的路径。 |
| topMargin | Single | 页面顶部的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

在页面上将图像添加为页眉。

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | String | 图像文件的路径。 |
| topMargin | Single | 页面顶部的边距。 |
| leftMargin | Single | 页面左侧的边距。 |
| rightMargin | Single | 页面右侧的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

在页面上将图像添加为页眉。

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 图像流。 |
| topMargin | Single | 页面顶部的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

在页面顶部添加图像。

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 包含图像数据的流。 |
| topMargin | Single | 页面顶部的边距。 |
| leftMargin | Single | 页面左侧的边距。 |
| rightMargin | Single | 页面右侧的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


