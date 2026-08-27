---
title: "SvgExtractor.Extract"
second_title: "Aspose.PDF for .NET API 参考"
description: "SvgExtractor 方法。提取由 absorber 表示的图形元素中的 svg 图像为字符串，使用谓词过滤器。"
type: docs
weight: 20
url: /zh/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

从由 !:absorber 表示的图形元素中提取 svg 图像为字符串，使用谓词过滤器。

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 吸收器 | GraphicsAbsorber | 包含图形元素的GraphicsAbsorber对象。 |
| 过滤器 | Predicate`1 | 用于过滤图形元素的谓词函数。 |
| 页面 | 页面 | 吸收器获取图形元素的页面。 |

### 返回值

包含 SVG 内容的字符串。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另请参见

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

从由 !:absorber 表示的图形元素中提取 svg 图像为文件，使用谓词过滤器。

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 吸收器 | GraphicsAbsorber | 包含图形元素的GraphicsAbsorber对象。 |
| 过滤器 | Predicate`1 | 用于过滤图形元素的谓词函数。 |
| 页面 | 页面 | 吸收器获取图形元素的页面。 |
| svgFilePath | String | 目标 SVG 文件路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另请参见

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

将图形元素提取为 SVG 字符串。忽略的选项 - 分组、从矩形提取。

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 元素 | IEnumerable`1 | 要转换的图形元素。 |
| 页面 | 页面 | 吸收器获取图形元素的页面。 |

### 返回值

包含 SVG 内容的字符串。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另请参见

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

将图形元素提取为单个 SVG 文件。忽略的选项 - 分组、从矩形提取。

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 元素 | IEnumerable`1 | 要转换的图形元素。 |
| 页面 | 页面 | 吸收器获取图形元素的页面。 |
| svgFilePath | String | 目标 SVG 文件路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另请参见

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

将页面中的 Svg 图像提取为字符串。

```csharp
public List<string> Extract(Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | 页面 | 要提取的页面。 |

### 返回值

SVG 内容字符串列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

将页面中的 Svg 图像提取为文件。

```csharp
public void Extract(Page page, string directory)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | 页面 | 要提取的页面。 |
| 目录 | String | 用于放置 SVG 图像的目标目录。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | 如果在转换为 SVG 时发生错误。 |

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


