---
title: ReplaceText
second_title: Aspose.PDF for .NET API 参考
description: 替换指定页面上 PDF 文件中的文本TextStateaspose.pdf.text/textstate可以指定对象字体系列颜色来替换文本
type: docs
weight: 450
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

替换指定页面上 PDF 文件中的文本。[`TextState`](../../../aspose.pdf.text/textstate)可以指定对象（字体系列，颜色）来替换文本。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| thePage | Int32 | 页码（0 表示“所有页面”）。 |
| destString | String | 被替换的字符串。 |
| textState | TextState | 文本状态（文本颜色、字体等）。 |

### 返回值

如果进行了替换，则返回 true。

### 例子

示例演示如何替换PDF文档第一页的文本并设置[`TextState`](../../../aspose.pdf.text/textstate)新文本的文本属性。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建字体并将其标记为嵌入
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 创建 PdfContentEditor 对象来编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 创建文本状态对象
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// 改变指定字体的文本
editor.ReplaceText("hello world", 1, "hi world", textState);

// 保存文档
doc.Save(outFile);
```

### 也可以看看

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

替换 PDF 文件中的文本。

```csharp
public bool ReplaceText(string srcString, string destString)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| destString | String | 替换字符串。 |

### 返回值

如果进行了替换，则返回 true。

### 例子

该示例演示如何替换 PDF 文档中的文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 PdfContentEditor 对象来编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 改变文本 
editor.ReplaceText("hello world", "hi world");

// 保存文档
doc.Save(outFile);
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

替换指定页面上 PDF 文件中的文本。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要更换的刺。 |
| thePage | Int32 | 页码（所有页为 0） |
| destString | String | 替换字符串。 |

### 返回值

如果进行了替换，则返回 true。

### 例子

该示例演示了如何在指定页面上替换PDF文档中的文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 PdfContentEditor 对象来编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 改变文本 
editor.ReplaceText("hello world", 1, "hi world");

// 保存文档
doc.Save(outFile);
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

使用指定的替换 PDF 文件中的文本[`TextState`](../../../aspose.pdf.text/textstate)对象.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串 |
| destString | String | 替换字符串 |
| textState | TextState | 文本状态（文本颜色、字体等） |

### 返回值

如果进行了替换，则返回 true。

### 例子

示例演示如何替换文本并设置[`TextState`](../../../aspose.pdf.text/textstate)新文本的文本属性。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建字体并将其标记为嵌入
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 创建 PdfContentEditor 对象来编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 创建文本状态对象
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// 改变指定字体的文本
editor.ReplaceText("hello world", "hi world", textState);

// 保存文档
doc.Save(outFile);
```

### 也可以看看

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

替换 PDF 文件中的文本并设置字体大小。

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| destString | String | 替换字符串。 |
| fontSize | Int32 | 字体大小。 |

### 返回值

如果进行了替换，则返回 true。

### 例子

该示例演示了如何替换文本并为新文本设置字体大小。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建字体并将其标记为嵌入
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 创建 PdfContentEditor 对象来编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 改变指定字体的文本
editor.ReplaceText("hello world", "hi world", 14);

// 保存文档
doc.Save(outFile);
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
