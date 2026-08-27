---
title: "PdfContentEditor.ReplaceText"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。 替换指定页面上 PDF 文件中的文本。 可以为替换的文本指定 TextState 对象的字体系列和颜色。"
type: docs
weight: 450
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

在指定页面的 PDF 文件中替换文本。可以为替换的文本指定 [`TextState`](../../../aspose.pdf.text/textstate/) 对象（字体系列、颜色）。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要被替换的字符串。 |
| thePage | Int32 | 页码（0 表示“所有页”。） |
| destString | String | 被替换的字符串。 |
| textState | TextState | 文本状态（文本颜色、字体等）。 |

### 返回值

如果已进行替换，则返回 true。

## 示例

示例演示如何在 PDF 文档的首页替换文本，并为新文本设置 [`TextState`](../../../aspose.pdf.text/textstate/) 文本属性。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建字体并标记为嵌入
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 创建 PdfContentEditor 对象以编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 创建 textState 对象
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// 使用指定字体更改文本
editor.ReplaceText("hello world", 1, "hi world", textState);

// 保存文档
doc.Save(outFile);
```

### 另请参见

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

替换 PDF 文件中的文本。

```csharp
public bool ReplaceText(string srcString, string destString)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要被替换的字符串。 |
| destString | String | 正在替换字符串。 |

### 返回值

如果已进行替换，则返回 true。

## 示例

示例演示如何在 PDF 文档中替换文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 PdfContentEditor 对象以编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 更改文本
editor.ReplaceText("hello world", "hi world");

// 保存文档
doc.Save(outFile);
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

在指定页面上替换 PDF 文件中的文本。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要被替换的字符串。 |
| thePage | Int32 | 页码（0 表示所有页） |
| destString | String | 正在替换字符串。 |

### 返回值

如果已进行替换，则返回 true。

## 示例

示例演示如何在指定页面的 PDF 文档中替换文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 PdfContentEditor 对象以编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 更改文本
editor.ReplaceText("hello world", 1, "hi world");

// 保存文档
doc.Save(outFile);
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

使用指定的 [`TextState`](../../../aspose.pdf.text/textstate/) 对象替换 PDF 文件中的文本。

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串 |
| destString | String | 正在替换字符串 |
| textState | TextState | 文本状态（文本颜色、字体等） |

### 返回值

如果已进行替换，则返回 true。

## 示例

示例演示如何替换文本并为新文本设置 [`TextState`](../../../aspose.pdf.text/textstate/) 文本属性。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建字体并标记为嵌入
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 创建 PdfContentEditor 对象以编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 创建 textState 对象
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// 使用指定字体更改文本
editor.ReplaceText("hello world", "hi world", textState);

// 保存文档
doc.Save(outFile);
```

### 另请参见

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

替换 PDF 文件中的文本并设置字体大小。

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| destString | String | 正在替换字符串。 |
| fontSize | Int32 | 字体大小。 |

### 返回值

如果已进行替换，则返回 true。

## 示例

示例演示如何替换文本并为新文本设置字体大小。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建字体并标记为嵌入
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 创建 PdfContentEditor 对象以编辑文本
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 使用指定字体更改文本
editor.ReplaceText("hello world", "hi world", 14);

// 保存文档
doc.Save(outFile);
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


