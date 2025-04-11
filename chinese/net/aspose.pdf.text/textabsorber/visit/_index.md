---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber 方法。提取指定页面上的文本
type: docs
weight: 70
url: /zh/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

提取指定页面上的文本

```csharp
public virtual void Visit(Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | Pdf 文档页面对象。 |

## 示例

该示例演示如何提取第一个 PDF 文档页面上的文本。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1]);

// get the extracted text
string extractedText = absorber.Text;
```

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

提取指定 XForm 上的文本。

```csharp
public virtual void Visit(XForm form)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| form | XForm | Pdf 表单对象。 |

## 示例

该示例演示如何提取第一个 PDF 文档页面上的文本。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// get the extracted text
string extractedText = absorber.Text;
```

### 另请参见

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

提取指定文档上的文本

```csharp
public virtual void Visit(Document pdf)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdf | Document | Pdf 文档对象。 |

## 示例

该示例演示如何提取 PDF 文档上的文本。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc);

// get the extracted text
string extractedText = absorber.Text;
```

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)