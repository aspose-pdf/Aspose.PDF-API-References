---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示文本的吸收器对象。执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对结果的访问。 </p> <hr> <pre> 示例。</pre>"
type: docs
weight: 4900
url: /zh/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> 表示文本的吸收器对象。执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对结果的访问。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> {@code TextAbsorber} 对象用于从 Pdf 文档或文档的页面中提取文本。 </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> 初始化 {@code TextAbsorber} 的新实例。 </p> <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对提取文本的访问。 </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> 初始化 {@code TextAbsorber} 的新实例。 </p> <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对提取文本的访问。 </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> 初始化 {@code TextAbsorber} 的新实例。 </p> <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对提取文本的访问。 </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> 初始化 {@code TextAbsorber} 的新实例。 </p> <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对提取文本的访问。 </p> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getErrors](#getErrors--) | {@code TextExtractionError} 对象的列表。它包含在文本提取过程中发现的错误信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| [getExtractionOptions](#getExtractionOptions--) | <p> 获取文本提取选项。 </p> <hr> <pre> 示例演示如何设置 Pure 文本格式模式并执行文本提取。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 允许在提取期间定义文本格式模式 {@code TextExtractionOptions}。默认模式是 {@code TextExtractionOptions.TextFormattingMode.Pure}。</p> |
| [getText](#getText--) | <p> 获取 {@code TextAbsorber} 在 PDF 文档或页面上提取的文本。 </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | 获取文本搜索选项。允许定义限定提取文本的矩形。默认情况下矩形为空。这意味着仅页面边界定义文本提取区域。 |
| [hasErrors](#hasErrors--) | 该值指示在文本提取过程中是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> 设置文本提取选项。 </p> <hr> <pre> 示例演示如何设置 Pure 文本格式模式并执行文本提取。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 允许在提取期间定义文本格式模式 {@code TextExtractionOptions}。默认模式是 {@code TextExtractionOptions.TextFormattingMode.Pure}。</p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | 设置文本搜索选项。允许定义限定提取文本的矩形。默认情况下矩形为空。这意味着仅页面边界定义文本提取区域。 |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> 在指定文档上提取文本 </p> <hr> <pre> 示例演示如何在 PDF 文档上提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> 在指定页面上提取文本 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> 在指定的 XForm 上提取文本。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> 初始化 {@code TextAbsorber} 的新实例。 </p> <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对提取文本的访问。 </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> 初始化 {@code TextAbsorber} 的新实例。 </p> <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对提取文本的访问。 </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> 初始化 {@code TextAbsorber} 的新实例。 </p> <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对提取文本的访问。 </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> 初始化 {@code TextAbsorber} 的新实例。 </p> <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对提取文本的访问。 </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

{@code TextExtractionError} 对象的列表。它包含在文本提取过程中发现的错误信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。

**Returns:**
TextExtractionError 对象的列表

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> 获取文本提取选项。 </p> <hr> <pre> 示例演示如何设置 Pure 文本格式模式并执行文本提取。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 允许在提取期间定义文本格式模式 {@code TextExtractionOptions}。默认模式是 {@code TextExtractionOptions.TextFormattingMode.Pure}。</p>

**Returns:**
TextExtractionOptions value

### getText {#getText--}
```
public String getText()
```

<p> 获取 {@code TextAbsorber} 在 PDF 文档或页面上提取的文本。 </p>

**Returns:**
String 值 <hr> <pre> 示例演示如何从 PDF 文档的所有页面提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

获取文本搜索选项。允许定义限定提取文本的矩形。默认情况下矩形为空。这意味着仅页面边界定义文本提取区域。

**Returns:**
TextSearchOptions 值

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

该值指示在文本提取过程中是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。

**Returns:**
布尔值

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> 设置文本提取选项。 </p> <hr> <pre> 示例演示如何设置 Pure 文本格式模式并执行文本提取。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 允许在提取期间定义文本格式模式 {@code TextExtractionOptions}。默认模式是 {@code TextExtractionOptions.TextFormattingMode.Pure}。</p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
设置文本搜索选项。允许定义限定提取文本的矩形。默认情况下矩形为空。这意味着仅页面边界定义文本提取区域。

### visit {#visit-com.aspose.pdf.IDocument-}
<p> 在指定文档上提取文本 </p> <hr> <pre> 示例演示如何在 PDF 文档上提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> 在指定页面上提取文本 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> 在指定的 XForm 上提取文本。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // get the extracted text String extractedText = absorber.getText(); </pre>
