---
title: "TextFragmentAbsorber.Visit"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragmentAbsorber 方法。对指定页面执行搜索。"
type: docs
weight: 150
url: /zh/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

在指定的 Page 上执行搜索。

```csharp
public override void Visit(Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | 页面 | PDF 文档页面对象。 |

## 示例

示例演示了如何在 PDF 文档的第一页查找文本并替换该文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
absorber.Visit(doc.Pages[1]);

// 更改所有搜索匹配项的文本。
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

在指定的 Document 上执行搜索。

```csharp
public override void Visit(Document pdf)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdf | Document | PDF 文档对象。 |

## 示例

示例演示了如何在 PDF 文档上查找文本并替换所有搜索匹配项的文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
absorber.Visit(doc);

// 更改第一次文本出现的内容。
absorber.TextFragments[1].Text = "hi world";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

在指定的表单对象上执行搜索。

```csharp
public void Visit(XForm xForm)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xForm | XForm | Pdf 表单对象。 |

### 另请参见

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


