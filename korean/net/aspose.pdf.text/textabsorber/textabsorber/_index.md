---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber 생성자. TextAbsorber의 새 인스턴스를 초기화합니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

[`TextAbsorber`](../)의 새 인스턴스를 초기화합니다.

```csharp
public TextAbsorber()
```

## Remarks

텍스트 추출을 수행하고 [`Text`](../text/) 객체를 통해 추출된 텍스트에 대한 액세스를 제공합니다.

## Examples

이 예제는 PDF 문서의 모든 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

추출 옵션과 함께 [`TextAbsorber`](../)의 새 인스턴스를 초기화합니다.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | 텍스트 추출 옵션 |

## Remarks

텍스트 추출을 수행하고 [`Text`](../text/) 객체를 통해 추출된 텍스트에 대한 액세스를 제공합니다.

## Examples

이 예제는 PDF 문서의 모든 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | 텍스트 추출 옵션 |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션 |

## Remarks

텍스트 추출을 수행하고 [`Text`](../text/) 객체를 통해 추출된 텍스트에 대한 액세스를 제공합니다.

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션 |

## Remarks

텍스트 추출을 수행하고 [`Text`](../text/) 객체를 통해 추출된 텍스트에 대한 액세스를 제공합니다.

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)