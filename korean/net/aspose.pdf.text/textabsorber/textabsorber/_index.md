---
title: "TextAbsorber.TextAbsorber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextAbsorber 생성자. TextAbsorber의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

[`TextAbsorber`](../)의 새 인스턴스를 초기화합니다.

```csharp
public TextAbsorber()
```

## 비고

텍스트 추출을 수행하고 [`Text`](../text/) 객체를 통해 추출된 텍스트에 접근할 수 있습니다.

## 예제

예제는 PDF 문서의 모든 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 텍스트를 추출하기 위해 TextAbsorber 객체를 생성합니다.
TextAbsorber absorber = new TextAbsorber();

// 문서의 모든 페이지에 대해 흡수기를 수락합니다.
doc.Pages.Accept(absorber);

// 추출된 텍스트를 가져옵니다.
string extractedText = absorber.Text;

```

### 또 보기

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

추출 옵션과 함께 [`TextAbsorber`](../)의 새 인스턴스를 초기화합니다.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | 텍스트 추출 옵션 |

## 비고

텍스트 추출을 수행하고 [`Text`](../text/) 객체를 통해 추출된 텍스트에 접근할 수 있습니다.

## 예제

예제는 PDF 문서의 모든 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 서식이 포함된 텍스트를 추출하기 위해 TextAbsorber 객체를 생성합니다.
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// 문서의 모든 페이지에 대해 흡수기를 수락합니다.
doc.Pages.Accept(absorber);

// 추출된 텍스트를 가져옵니다.
string extractedText = absorber.Text;

```

### 또 보기

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

추출 및 텍스트 검색 옵션과 함께 [`TextAbsorber`](../)의 새 인스턴스를 초기화합니다.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | 텍스트 추출 옵션 |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션 |

## 비고

텍스트 추출을 수행하고 [`Text`](../text/) 객체를 통해 추출된 텍스트에 접근할 수 있습니다.

### 또 보기

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

텍스트 검색 옵션과 함께 [`TextAbsorber`](../)의 새 인스턴스를 초기화합니다.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션 |

## 비고

텍스트 추출을 수행하고 [`Text`](../text/) 객체를 통해 추출된 텍스트에 접근할 수 있습니다.

### 또 보기

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


