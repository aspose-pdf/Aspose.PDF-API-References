---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractor 메서드. 흡수기에 의해 표현된 그래픽 요소에서 문자열로 svg 이미지를 추출합니다. 프레디케이트 필터가 적용됩니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

흡수기에 의해 표현된 그래픽 요소에서 문자열로 svg 이미지를 추출합니다. 프레디케이트 필터가 적용됩니다.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| absorber | GraphicsAbsorber | 그래픽 요소를 포함하는 GraphicsAbsorber 객체입니다. |
| filter | Predicate`1 | 그래픽 요소를 필터링하는 데 사용되는 프레디케이트 함수입니다. |
| page | Page | 흡수기가 그래픽 요소를 가져오는 페이지입니다. |

### Return Value

SVG 콘텐츠가 포함된 문자열입니다.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환할 때 오류가 발생한 경우입니다. |

### See Also

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

흡수기에 의해 표현된 그래픽 요소에서 파일로 svg 이미지를 추출합니다. 프레디케이트 필터가 적용됩니다.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| absorber | GraphicsAbsorber | 그래픽 요소를 포함하는 GraphicsAbsorber 객체입니다. |
| filter | Predicate`1 | 그래픽 요소를 필터링하는 데 사용되는 프레디케이트 함수입니다. |
| page | Page | 흡수기가 그래픽 요소를 가져오는 페이지입니다. |
| svgFilePath | String | 대상 SVG 파일 경로입니다. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환할 때 오류가 발생한 경우입니다. |

### See Also

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

그래픽 요소를 SVG 문자열로 추출합니다. 옵션은 무시됩니다 - 그룹화, 사각형에서 추출

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| elements | IEnumerable`1 | 변환할 그래픽 요소입니다. |
| page | Page | 흡수기가 그래픽 요소를 가져오는 페이지입니다. |

### Return Value

SVG 콘텐츠가 포함된 문자열입니다.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환할 때 오류가 발생한 경우입니다. |

### See Also

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

그래픽 요소를 단일 SVG 파일로 추출합니다. 옵션은 무시됩니다 - 그룹화, 사각형에서 추출

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| elements | IEnumerable`1 | 변환할 그래픽 요소입니다. |
| page | Page | 흡수기가 그래픽 요소를 가져오는 페이지입니다. |
| svgFilePath | String | 대상 SVG 파일 경로입니다. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환할 때 오류가 발생한 경우입니다. |

### See Also

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

페이지에서 Svg 이미지를 문자열로 추출합니다.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | 추출할 페이지입니다. |

### Return Value

SVG 콘텐츠 문자열 목록입니다.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환할 때 오류가 발생한 경우입니다. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

페이지에서 Svg 이미지를 파일로 추출합니다.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | 추출할 페이지입니다. |
| directory | String | SVG 이미지를 배치할 대상 디렉토리입니다. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환할 때 오류가 발생한 경우입니다. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)