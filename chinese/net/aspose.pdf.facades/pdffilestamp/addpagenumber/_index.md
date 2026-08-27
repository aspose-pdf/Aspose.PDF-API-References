---
title: "PdfFileStamp.AddPageNumber"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileStamp 方法。向文件添加页码。页码文本可能包含  符号，该符号将被页面的编号替代。页码位于页面底部并水平居中"
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

在文件添加页码。页码文本可以包含 # 符号，系统会将其替换为相应的页码。页码位于页面底部，水平居中。

```csharp
public void AddPageNumber(string formatString)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 页码文本 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

在页面添加页码。页码可以包含 # 符号，系统会将其替换为实际页码。页码位于页面底部，水平居中。

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 页码的格式字符串表示为 FormattedText。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### 另请参见

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

在文档的页面添加页码。

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 页码的格式字符串。 |
| position | Int32 | 页码在页面上的放置位置。0‑底部居中，1‑底部右侧，2‑右上角，3‑右侧，4‑上部居中，5‑左下角，6‑左侧，7‑左上角。您可以使用以下常量：PosBottomMiddle = 0，PosBottomRight = 1，PosUpperRight = 2，PosSidesRight = 3，PosUpperMiddle，PosBottomLeft = 5，PosSidesLeft，PosUpperLeft |
| leftMargin | Single | 页面左边缘的边距。 |
| rightMargin | Single | 页面右边缘的边距。 |
| topMargin | Single | 页面顶部的边距。 |
| bottomMargin | Single | 页面底部的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

在页面的指定位置添加页码。

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 格式字符串。格式字符串可以包含 # 符号，该符号将被页码替代。 |
| x | Single | 页码的 X 坐标。 |
| y | Single | 页码的 Y 坐标。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

在文档的页面添加页码。

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText 对象，表示页码格式和文本属性。 |
| position | Int32 | 页码在页面上的放置位置。0‑底部居中，1‑底部右侧，2‑右上角，3‑右侧，4‑上部居中，5‑左下角，6‑左侧，7‑左上角。您可以使用以下常量：PosBottomMiddle = 0，PosBottomRight = 1，PosUpperRight = 2，PosSidesRight = 3，PosUpperMiddle，PosBottomLeft = 5，PosSidesLeft，PosUpperLeft |
| leftMargin | Single | 页面左边缘的边距。 |
| rightMargin | Single | 页面右边缘的边距。 |
| topMargin | Single | 页面顶部的边距。 |
| bottomMargin | Single | 页面底部的边距。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 另请参见

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

在页面的指定位置添加页码。

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 格式化文本，表示页码格式和文本属性。格式字符串可以包含 # 符号，该符号将被页码替代。 |
| x | Single | 页码的 X 坐标。 |
| y | Single | 页码的 Y 坐标。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 另请参见

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

在页面添加页码。

```csharp
public void AddPageNumber(string formatString, int position)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 页码的格式。此文本可能包含 #，该符号将被页码替代。 |
| position | Int32 | 页码在页面上的放置位置。0‑底部居中，1‑底部右侧，2‑右上角，3‑右侧，4‑上部居中，5‑左下角，6‑左侧，7‑左上角。您可以使用以下常量：PosBottomMiddle = 0，PosBottomRight = 1，PosUpperRight = 2，PosSidesRight = 3，PosUpperMiddle，PosBottomLeft = 5，PosSidesLeft，PosUpperLeft |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

在页面添加页码。

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText 对象，包含页码的格式和文本属性。此文本可能包含 #，该符号将被页码替代。 |
| position | Int32 | 页码在页面上的放置位置。0‑底部居中，1‑底部右侧，2‑右上角，3‑右侧，4‑上部居中，5‑左下角，6‑左侧，7‑左上角。您可以使用以下常量：PosBottomMiddle = 0，PosBottomRight = 1，PosUpperRight = 2，PosSidesRight = 3，PosUpperMiddle，PosBottomLeft = 5，PosSidesLeft，PosUpperLeft |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 另请参见

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


