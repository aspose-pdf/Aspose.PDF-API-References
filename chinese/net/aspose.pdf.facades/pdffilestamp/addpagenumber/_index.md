---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 方法。向文件添加页码。页码文本可能包含 # 符号，该符号将被页码替换。页码位于页面底部，水平居中。
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

向文件添加页码。页码文本可能包含 # 符号，该符号将被页码替换。页码位于页面底部，水平居中。

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

向页面添加页码。页码可能包含 # 符号，该符号将被页码替换。页码位于页面底部，水平居中。

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 表示页码的格式字符串，作为 FormattedText。 |

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

向文档的页面添加页码。

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 页码的格式字符串。 |
| position | Int32 | 页码在页面上的位置。0-底部中间，1-底部右侧，2-顶部右侧，3-右侧，4-顶部中间，5-底部左侧，6-左侧，7-顶部左侧。您可以使用以下常量：PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | 页面左边缘的边距。 |
| rightMargin | Single | 页面右边缘的边距。 |
| topMargin | Single | 页面顶部边缘的边距。 |
| bottomMargin | Single | 页面底部边缘的边距。 |

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
| formatString | String | 格式字符串。格式字符串可以包含 # 符号，该符号将被页码替换。 |
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

向文档的页面添加页码。

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 表示页码格式和文本属性的 FormattedText 对象。 |
| position | Int32 | 页码在页面上的位置。0-底部中间，1-底部右侧，2-顶部右侧，3-右侧，4-顶部中间，5-底部左侧，6-左侧，7-顶部左侧。您可以使用以下常量：PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | 页面左边缘的边距。 |
| rightMargin | Single | 页面右边缘的边距。 |
| topMargin | Single | 页面顶部边缘的边距。 |
| bottomMargin | Single | 页面底部边缘的边距。 |

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
| formattedText | FormattedText | 表示页码格式和文本属性的格式化文本。格式字符串可以包含 # 符号，该符号将被页码替换。 |
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

向页面添加页码。

```csharp
public void AddPageNumber(string formatString, int position)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 页码的格式。该文本可能包含 #，将被页码替换。 |
| position | Int32 | 页码在页面上的位置。0-底部中间，1-底部右侧，2-顶部右侧，3-右侧，4-顶部中间，5-底部左侧，6-左侧，7-顶部左侧。您可以使用以下常量：PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

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

向页面添加页码。

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 包含页码格式和文本属性的 FormattedText 对象。该文本可能包含 #，将被页码替换。 |
| position | Int32 | 页码在页面上的位置。0-底部中间，1-底部右侧，2-顶部右侧，3-右侧，4-顶部中间，5-底部左侧，6-左侧，7-顶部左侧。您可以使用以下常量：PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

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