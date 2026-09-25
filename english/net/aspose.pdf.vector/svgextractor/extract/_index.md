---
title: "SvgExtractor.Extract"
linktitle: "Extract"
articleTitle: "Extract"
second_title: "Aspose.PDF for .NET API Reference"
description: "SvgExtractor method. Exracts svg image to string from graphic elements represents by !:absorber with a predicate filter."
type: docs
weight: 30
url: "/net/aspose.pdf.vector/svgextractor/extract/"
product_version: "26.9.0"
---
## Extract([GraphicsAbsorber](../../../aspose.pdf.vector/graphicsabsorber/), Predicate<GraphicElement>, [Page](../../../aspose.pdf/page/)) {#extract}

Exracts svg image to string from graphic elements represents by `!:absorber` with a predicate filter.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| absorber | GraphicsAbsorber | The GraphicsAbsorber object that contains the graphic elements. |
| filter | Predicate<GraphicElement> | A predicate function used to filter the graphic elements. |
| page | Page | The page where the absorber gets graphic elements. |

### Return Value

string

The string with SVG content.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract([GraphicsAbsorber](../../../aspose.pdf.vector/graphicsabsorber/), Predicate<GraphicElement>, [Page](../../../aspose.pdf/page/), string) {#extract_1}

Exracts svg image to file from graphic elements represents by `!:absorber` with a predicate filter.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, string svgFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| absorber | GraphicsAbsorber | The GraphicsAbsorber object that contains the graphic elements. |
| filter | Predicate<GraphicElement> | A predicate function used to filter the graphic elements. |
| page | Page | The page where the absorber gets graphic elements. |
| svgFilePath | string | The target SVG file path. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable<GraphicElement>, [Page](../../../aspose.pdf/page/)) {#extract_2}

Extracts graphic elements into a SVG string.
 Options ignored - grouping, extracting from rectangle

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| elements | IEnumerable<GraphicElement> | The graphic elements to convert. |
| page | Page | The page where the absorber gets graphic elements. |

### Return Value

string

The string with SVG content.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable<GraphicElement>, [Page](../../../aspose.pdf/page/), string) {#extract_3}

Extracts graphic elements into a single SVG file.
 Options ignored - grouping, extracting from rectangle

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| elements | IEnumerable<GraphicElement> | The graphic elements to convert. |
| page | Page | The page where the absorber gets graphic elements. |
| svgFilePath | string | The target SVG file path. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract([Page](../../../aspose.pdf/page/)) {#extract_4}

Extracts Svg images from a page to strings.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | The page to extract. |

### Return Value

[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<string>

The list of SVG content strings.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract([Page](../../../aspose.pdf/page/), string) {#extract_5}

Extracts Svg images from a page to files.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | The page to extract. |
| directory | string | The target directory to place SVG images. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | If an error occurred when converting to SVG. |

### See Also

* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

