---
title: AddPageNumber
second_title: Aspose.PDF for .NET API 参考
description: 将页码添加到文件中页码文本可能包含  符号该符号将替换为页码 页码放置在页面底部水平居中
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

将页码添加到文件中。页码文本可能包含 # 符号，该符号将替换为页码。 页码放置在页面底部水平居中。

```csharp
public void AddPageNumber(string formatString)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 页码文本 |

### 例子

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### 也可以看看

* class [PdfFileStamp](../../pdffilestamp)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilestamp)
* 部件 [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

将页码添加到页面。页码可能包含 # 符号，该符号将替换为页码。 页码放置在页面底部水平居中。

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 页码的格式字符串表示为 FormattedText。 |

### 例子

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### 也可以看看

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilestamp)
* 部件 [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

将页码添加到文档页面。

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 页码的格式字符串。 |
| position | Int32 | 将在页面上放置页码的位置。 0-中下，1-右下，2-右上， 3 - 右侧，4 - 上中，5 - 左下，6 - 左侧，7 - 左上。 您可以使用以下常量: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | 页面左边缘的边距。 |
| rightMargin | Single | 页面右边缘的边距。 |
| topMargin | Single | 页面上边缘的边距。 |
| bottomMargin | Single | 页面底部边缘的边距。 |

### 例子

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 也可以看看

* class [PdfFileStamp](../../pdffilestamp)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilestamp)
* 部件 [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

在页面的指定位置添加页码。

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 格式字符串。格式字符串可以包含 # 符号，该符号将替换为页码。 |
| x | Single | 页码X坐标。 |
| y | Single | 页码的 Y 坐标。 |

### 例子

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 也可以看看

* class [PdfFileStamp](../../pdffilestamp)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilestamp)
* 部件 [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

将页码添加到文档页面。

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText 对象，表示页码格式和文本的属性。 |
| position | Int32 | 将在页面上放置页码的位置。 0-中下，1-右下，2-右上， 3 - 右侧，4 - 上中，5 - 左下，6 - 左侧，7 - 左上。 您可以使用以下常量: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | 页面左边缘的边距。 |
| rightMargin | Single | 页面右边缘的边距。 |
| topMargin | Single | 页面上边缘的边距。 |
| bottomMargin | Single | 页面底部边缘的边距。 |

### 例子

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 也可以看看

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilestamp)
* 部件 [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

在页面的指定位置添加页码。

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | 表示页码格式和文本属性的格式化文本。 格式字符串可以包含#号，将替换为页码。 |
| x | Single | 页码X坐标。 |
| y | Single | 页码的 Y 坐标。 |

### 例子

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 也可以看看

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilestamp)
* 部件 [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

将页码添加到页面。

```csharp
public void AddPageNumber(string formatString, int position)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatString | String | 页码格式。此文本可能包含 # 将替换为页码。 |
| position | Int32 | 将在页面上放置页码的位置。 0-中下，1-右下，2-右上， 3 - 右侧，4 - 上中，5 - 左下，6 - 左侧，7 - 左上。 您可以使用以下常量: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### 例子

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 也可以看看

* class [PdfFileStamp](../../pdffilestamp)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilestamp)
* 部件 [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

将页码添加到页面。

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText 对象，其中包含页码格式和文本属性。 此文本可能包含 # 将替换为页码。 |
| position | Int32 | 将在页面上放置页码的位置。 0-中下，1-右下，2-右上， 3 - 右侧，4 - 上中，5 - 左下，6 - 左侧，7 - 左上。 您可以使用以下常量: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### 例子

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 也可以看看

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilestamp)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
