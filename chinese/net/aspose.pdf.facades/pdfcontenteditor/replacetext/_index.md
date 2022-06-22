---
title: ReplaceText
second_title: Aspose.PDF for .NET API 参考
description: 替换指定页面上 PDF 文件中的文本TextStateaspose.pdf.text/textstate对象字体系列颜色可以指定为替换文本
type: docs
weight: 450
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

替换指定页面上 PDF 文件中的文本。[`TextState`](../../../aspose.pdf.text/textstate)对象（字体系列，颜色）可以指定为替换文本。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| thePage | Int32 | 页码（0 表示“所有页”）。 |
| destString | String | 被替换的字符串。 |
| textState | TextState | 文本状态（文本颜色、字体等）。 |

### 返回值

如果进行了替换，则返回 true。

### 例子

该示例演示如何替换 PDF 文档第一页上的文本并设置[`TextState`](../../../aspose.pdf.text/textstate)新文本的文本属性。

```csharp
// 打开文档
cument doc = new Document(inFile);

// 创建字体并将其标记为embedded
pose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
nt.IsEmbedded = true;

// 创建 PdfContentEditor 对象来编辑 text
fContentEditor editor = new PdfContentEditor();
itor.BindPdf(doc);

// 创建 textState object
xtState textState = new TextState();
xtState.Font = font;
xtState.FontSize = 17;
xtState.FontStyle = FontStyle.Bold | FontStyle.Italic;
xtState.ForegroundColor = Color.Red;

// 用指定的 font

itor.ReplaceText("hello world", 1, "hi world", textState);

 保存文档
c.Save(outFile);
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
cument doc = new Document(inFile);

// 创建 PdfContentEditor 对象来编辑 text
fContentEditor editor = new PdfContentEditor();
itor.BindPdf(doc);

// 更改文本 
itor.ReplaceText("hello world", "hi world");

 保存文档
c.Save(outFile);
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
| srcString | String | 要替换的字符串。 |
| thePage | Int32 | 页码（所有页面均为 0） |
| destString | String | 替换字符串。 |

### 返回值

如果进行了替换，则返回 true。

### 例子

该示例演示如何在指定页面上替换 PDF 文档中的文本。

```csharp
// 打开文档
cument doc = new Document(inFile);

// 创建 PdfContentEditor 对象来编辑 text
fContentEditor editor = new PdfContentEditor();
itor.BindPdf(doc);

// 更改文本 
itor.ReplaceText("hello world", 1, "hi world");

 保存文档
c.Save(outFile);
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

使用指定的[`TextState`](../../../aspose.pdf.text/textstate)对象替换 PDF 文件中的文本。

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

该示例演示了如何替换文本并设置TextState新文本的文本属性。

```csharp
// 打开文档
cument doc = new Document(inFile);

// 创建字体并将其标记为embedded
pose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
nt.IsEmbedded = true;

// 创建 PdfContentEditor 对象来编辑 text
fContentEditor editor = new PdfContentEditor();
itor.BindPdf(doc);

// 创建 textState object
xtState textState = new TextState();
xtState.Font = font;
xtState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// 用指定的 font

itor.ReplaceText("hello world", "hi world", textState);

 保存文档
c.Save(outFile);
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
cument doc = new Document(inFile);

// 创建字体并将其标记为embedded
pose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
nt.IsEmbedded = true;

// 创建 PdfContentEditor 对象来编辑 text
fContentEditor editor = new PdfContentEditor();
itor.BindPdf(doc);

// 用指定的 font

itor.ReplaceText("hello world", "hi world", 14);

 保存文档
c.Save(outFile);
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
