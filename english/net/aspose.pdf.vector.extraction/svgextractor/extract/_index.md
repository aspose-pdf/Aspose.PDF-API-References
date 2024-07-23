---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractor method. Exracts svg image to string from graphic elements represents by absorber with a predicate filter
type: docs
weight: 20
url: /net/aspose.pdf.vector.extraction/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Exracts svg image to string from graphic elements represents by !:absorber with a predicate filter.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| absorber | GraphicsAbsorber | The GraphicsAbsorber object that contains the graphic elements. |
| filter | Predicate`1 | A predicate function used to filter the graphic elements. |
| page | Page | The page where the absorber gets graphic elements. |

### Return Value

The string with SVG content.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [GraphicsAbsorber](../../../aspose.pdf.vector/graphicsabsorber/)
* class [GraphicElement](../../../aspose.pdf.vector/graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector.Extraction](../../../aspose.pdf.vector.extraction/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Exracts svg image to file from graphic elements represents by !:absorber with a predicate filter.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| absorber | GraphicsAbsorber | The GraphicsAbsorber object that contains the graphic elements. |
| filter | Predicate`1 | A predicate function used to filter the graphic elements. |
| page | Page | The page where the absorber gets graphic elements. |
| svgFilePath | String | The target SVG file path. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [GraphicsAbsorber](../../../aspose.pdf.vector/graphicsabsorber/)
* class [GraphicElement](../../../aspose.pdf.vector/graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector.Extraction](../../../aspose.pdf.vector.extraction/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Extracts graphic elements into a SVG string. Options ignored - grouping, extracting from rectangle

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| elements | IEnumerable`1 | The graphic elements to convert. |
| page | Page | The page where the absorber gets graphic elements. |

### Return Value

The string with SVG content.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [GraphicElement](../../../aspose.pdf.vector/graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector.Extraction](../../../aspose.pdf.vector.extraction/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Extracts graphic elements into a single SVG file. Options ignored - grouping, extracting from rectangle

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| elements | IEnumerable`1 | The graphic elements to convert. |
| page | Page | The page where the absorber gets graphic elements. |
| svgFilePath | String | The target SVG file path. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [GraphicElement](../../../aspose.pdf.vector/graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector.Extraction](../../../aspose.pdf.vector.extraction/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Extracts Svg images from a page to strings.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | The page to extract. |

### Return Value

The list of SVG content strings.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector.Extraction](../../../aspose.pdf.vector.extraction/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Extracts Svg images from a page to files.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | The page to extract. |
| directory | String | The target directory to place SVG images. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector.Extraction](../../../aspose.pdf.vector.extraction/)
* assembly [Aspose.PDF](../../../)


