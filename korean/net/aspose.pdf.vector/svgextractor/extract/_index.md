---
title: "SvgExtractor.Extract"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "SvgExtractor 메서드. absorber와 predicate filter로 표현된 그래픽 요소에서 SVG 이미지를 문자열로 추출합니다."
type: docs
weight: 20
url: /ko/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

그래픽 요소( !:absorber 로 표시)에서 predicate 필터를 사용하여 svg 이미지를 문자열로 추출합니다.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| absorber | GraphicsAbsorber | 그래픽 요소를 포함하는 GraphicsAbsorber 객체. |
| 필터 | Predicate`1 | 그래픽 요소를 필터링하는 데 사용되는 predicate 함수. |
| 페이지 | 페이지 | absorber가 그래픽 요소를 가져오는 페이지. |

### 반환 값

SVG 콘텐츠가 포함된 문자열.

### 예외

| 예외 | 조건 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환하는 동안 오류가 발생한 경우. |

### 또 보기

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

그래픽 요소( !:absorber 로 표시)에서 predicate 필터를 사용하여 svg 이미지를 파일로 추출합니다.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| absorber | GraphicsAbsorber | 그래픽 요소를 포함하는 GraphicsAbsorber 객체. |
| 필터 | Predicate`1 | 그래픽 요소를 필터링하는 데 사용되는 predicate 함수. |
| 페이지 | 페이지 | absorber가 그래픽 요소를 가져오는 페이지. |
| svgFilePath | String | 대상 SVG 파일 경로. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환하는 동안 오류가 발생한 경우. |

### 또 보기

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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 요소 | IEnumerable`1 | 변환할 그래픽 요소. |
| 페이지 | 페이지 | absorber가 그래픽 요소를 가져오는 페이지. |

### 반환 값

SVG 콘텐츠가 포함된 문자열.

### 예외

| 예외 | 조건 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환하는 동안 오류가 발생한 경우. |

### 또 보기

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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 요소 | IEnumerable`1 | 변환할 그래픽 요소. |
| 페이지 | 페이지 | absorber가 그래픽 요소를 가져오는 페이지. |
| svgFilePath | String | 대상 SVG 파일 경로. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환하는 동안 오류가 발생한 경우. |

### 또 보기

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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | 페이지 | 추출할 페이지. |

### 반환 값

SVG 콘텐츠 문자열 목록.

### 예외

| 예외 | 조건 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환하는 동안 오류가 발생한 경우. |

### 또 보기

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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | 페이지 | 추출할 페이지. |
| 디렉터리 | String | SVG 이미지를 배치할 대상 디렉터리입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG로 변환하는 동안 오류가 발생한 경우. |

### 또 보기

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


