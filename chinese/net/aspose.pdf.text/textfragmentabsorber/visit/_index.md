---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 方法。对指定页面执行搜索
type: docs
weight: 150
url: /zh/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

对指定页面执行搜索。

```csharp
public override void Visit(Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | PDF 文档页面对象。 |

## 示例

该示例演示如何在第一个 PDF 文档页面上查找文本并替换文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

对指定文档执行搜索。

```csharp
public override void Visit(Document pdf)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdf | Document | PDF 文档对象。 |

## 示例

该示例演示如何在 PDF 文档上查找文本并替换所有搜索到的文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

对指定表单对象执行搜索。

```csharp
public void Visit(XForm xForm)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xForm | XForm | PDF 表单对象。 |

### 另请参阅

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)