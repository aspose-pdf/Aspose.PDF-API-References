---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractor 方法。从由吸收器表示的图形元素中提取 SVG 图像到字符串，使用谓词过滤器
type: docs
weight: 20
url: /zh/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

从由 !:absorber 表示的图形元素中提取 SVG 图像到字符串，使用谓词过滤器。

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absorber | GraphicsAbsorber | 包含图形元素的 GraphicsAbsorber 对象。 |
| filter | Predicate`1 | 用于过滤图形元素的谓词函数。 |
| page | Page | 吸收器获取图形元素的页面。 |

### 返回值

包含 SVG 内容的字符串。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另见

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

从由 !:absorber 表示的图形元素中提取 SVG 图像到文件，使用谓词过滤器。

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absorber | GraphicsAbsorber | 包含图形元素的 GraphicsAbsorber 对象。 |
| filter | Predicate`1 | 用于过滤图形元素的谓词函数。 |
| page | Page | 吸收器获取图形元素的页面。 |
| svgFilePath | String | 目标 SVG 文件路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另见

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

将图形元素提取为 SVG 字符串。选项被忽略 - 分组，从矩形提取

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elements | IEnumerable`1 | 要转换的图形元素。 |
| page | Page | 吸收器获取图形元素的页面。 |

### 返回值

包含 SVG 内容的字符串。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另见

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

将图形元素提取为单个 SVG 文件。选项被忽略 - 分组，从矩形提取

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elements | IEnumerable`1 | 要转换的图形元素。 |
| page | Page | 吸收器获取图形元素的页面。 |
| svgFilePath | String | 目标 SVG 文件路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另见

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

从页面提取 SVG 图像到字符串。

```csharp
public List<string> Extract(Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | 要提取的页面。 |

### 返回值

SVG 内容字符串的列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另见

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

从页面提取 SVG 图像到文件。

```csharp
public void Extract(Page page, string directory)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | 要提取的页面。 |
| directory | String | 放置 SVG 图像的目标目录。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另见

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)