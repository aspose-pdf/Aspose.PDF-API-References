---
title: "TextAbsorber.TextAbsorber"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextAbsorber 构造函数。初始化 TextAbsorber 的新实例。"
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

此示例演示如何从 PDF Document 的所有 Page 提取文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 TextAbsorber 对象以提取文本
TextAbsorber absorber = new TextAbsorber();

// 接受所有文档页面的吸收器
doc.Pages.Accept(absorber);

// 获取提取的文本
string extractedText = absorber.Text;

```

### 另请参见

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

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

此示例演示如何从 PDF Document 的所有 Page 提取文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 TextAbsorber 对象以使用格式提取文本。
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// 接受所有文档页面的吸收器
doc.Pages.Accept(absorber);

// 获取提取的文本
string extractedText = absorber.Text;

```

### 另请参见

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

使用提取和文本搜索选项初始化一个新的 [`TextAbsorber`](../) 实例。

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | 文本提取选项 |
| textSearchOptions | TextSearchOptions | 文本搜索选项 |

## 备注

执行文本提取，并通过 [`Text`](../text/) 对象提供对提取文本的访问。

### 另请参见

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

使用文本搜索选项初始化一个新的 [`TextAbsorber`](../) 实例。

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | 文本搜索选项 |

## 备注

执行文本提取，并通过 [`Text`](../text/) 对象提供对提取文本的访问。

### 另请参见

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


