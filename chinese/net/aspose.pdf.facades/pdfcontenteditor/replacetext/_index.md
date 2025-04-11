---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。替换指定页面上的 PDF 文件中的文本。可以指定 TextState 对象的字体系列颜色来替换文本
type: docs
weight: 450
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

替换指定页面上的 PDF 文件中的文本。可以指定 [`TextState`](../../../aspose.pdf.text/textstate/) 对象（字体系列，颜色）来替换文本。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| thePage | Int32 | 页码（0 表示“所有页面”）。 |
| destString | String | 替换后的字符串。 |
| textState | TextState | 文本状态（文本颜色，字体等）。 |

### 返回值

如果进行了替换，则返回 true。

## 示例

该示例演示如何在 PDF 文档的第一页上替换文本，并为新文本设置 [`TextState`](../../../aspose.pdf.text/textstate/) 文本属性。

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### 另请参阅

* 类 [TextState](../../../aspose.pdf.text/textstate/)
* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

替换 PDF 文件中的文本。

```csharp
public bool ReplaceText(string srcString, string destString)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| destString | String | 替换字符串。 |

### 返回值

如果进行了替换，则返回 true。

## 示例

该示例演示如何在 PDF 文档中替换文本。

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

替换指定页面上的 PDF 文件中的文本。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| thePage | Int32 | 页码（0 表示所有页面） |
| destString | String | 替换字符串。 |

### 返回值

如果进行了替换，则返回 true。

## 示例

该示例演示如何在指定页面上替换 PDF 文档中的文本。

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

使用指定的 [`TextState`](../../../aspose.pdf.text/textstate/) 对象替换 PDF 文件中的文本。

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串 |
| destString | String | 替换字符串 |
| textState | TextState | 文本状态（文本颜色，字体等） |

### 返回值

如果进行了替换，则返回 true。

## 示例

该示例演示如何替换文本并为新文本设置 [`TextState`](../../../aspose.pdf.text/textstate/) 文本属性。

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### 另请参阅

* 类 [TextState](../../../aspose.pdf.text/textstate/)
* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

替换 PDF 文件中的文本并设置字体大小。

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcString | String | 要替换的字符串。 |
| destString | String | 替换字符串。 |
| fontSize | Int32 | 字体大小。 |

### 返回值

如果进行了替换，则返回 true。

## 示例

该示例演示如何替换文本并为新文本设置字体大小。

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)