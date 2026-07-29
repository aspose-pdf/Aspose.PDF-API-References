---
title: "TextAbsorber.Visit"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextAbsorber 方法。提取指定页面上的文本"
type: docs
weight: 70
url: /zh/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

在指定的页面上提取文本

```csharp
public virtual void Visit(Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | 页面 | Pdf 文档页面对象。 |

## 示例

此示例演示如何在第一个 PDF 文档页面上提取文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 TextAbsorber 对象以提取文本
TextAbsorber absorber = new TextAbsorber();

// 接受所有文档页面的吸收器
absorber.Visit(doc.Pages[1]);

// 获取提取的文本
string extractedText = absorber.Text;
```

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

在指定的 XForm 上提取文本。

```csharp
public virtual void Visit(XForm form)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 表单 | XForm | Pdf 表单对象。 |

## 示例

此示例演示如何在第一个 PDF 文档页面上提取文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 TextAbsorber 对象以提取文本
TextAbsorber absorber = new TextAbsorber();

// 接受所有文档页面的吸收器
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// 获取提取的文本
string extractedText = absorber.Text;
```

### 另请参见

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

在指定的文档上提取文本

```csharp
public virtual void Visit(Document pdf)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdf | Document | Pdf pocument 对象。 |

## 示例

此示例演示如何从 PDF Document 中提取文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 TextAbsorber 对象以提取文本
TextAbsorber absorber = new TextAbsorber();

// 接受所有文档页面的吸收器
absorber.Visit(doc);

// 获取提取的文本
string extractedText = absorber.Text;
```

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


