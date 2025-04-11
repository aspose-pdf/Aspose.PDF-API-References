---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber 构造函数。初始化 TextAbsorber 的新实例
type: docs
weight: 10
url: /zh/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

初始化 [`TextAbsorber`](../) 的新实例。

```csharp
public TextAbsorber()
```

## 备注

执行文本提取，并通过 [`Text`](../text/) 对象提供对提取文本的访问。

## 示例

该示例演示如何从 PDF 文档的所有页面提取文本。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 另见

* 类 [TextAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

使用提取选项初始化 [`TextAbsorber`](../) 的新实例。

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | 文本提取选项 |

## 备注

执行文本提取，并通过 [`Text`](../text/) 对象提供对提取文本的访问。

## 示例

该示例演示如何从 PDF 文档的所有页面提取文本。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 另见

* 类 [TextExtractionOptions](../../textextractionoptions/)
* 类 [TextAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

使用提取和文本搜索选项初始化 [`TextAbsorber`](../) 的新实例。

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | 文本提取选项 |
| textSearchOptions | TextSearchOptions | 文本搜索选项 |

## 备注

执行文本提取，并通过 [`Text`](../text/) 对象提供对提取文本的访问。

### 另见

* 类 [TextExtractionOptions](../../textextractionoptions/)
* 类 [TextSearchOptions](../../textsearchoptions/)
* 类 [TextAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

使用文本搜索选项初始化 [`TextAbsorber`](../) 的新实例。

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | 文本搜索选项 |

## 备注

执行文本提取，并通过 [`Text`](../text/) 对象提供对提取文本的访问。

### 另见

* 类 [TextSearchOptions](../../textsearchoptions/)
* 类 [TextAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)