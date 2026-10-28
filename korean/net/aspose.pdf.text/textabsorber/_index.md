---
title: "클래스 TextAbsorber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextAbsorber 클래스. 텍스트 흡수 객체를 나타냅니다. 텍스트 추출을 수행하고 결과에 Text 객체를 통해 접근할 수 있게 합니다."
type: docs
weight: 10980
url: /ko/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

텍스트 흡수 객체를 나타냅니다. 텍스트 추출을 수행하고 결과에 [`Text`](./text/) 객체를 통해 접근할 수 있게 합니다.

```csharp
public class TextAbsorber
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | `TextAbsorber`의 새 인스턴스를 초기화합니다. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | 추출 옵션을 사용하여 `TextAbsorber`의 새 인스턴스를 초기화합니다. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | 텍스트 검색 옵션을 사용하여 `TextAbsorber`의 새 인스턴스를 초기화합니다. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | 추출 및 텍스트 검색 옵션을 사용하여 `TextAbsorber`의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) 객체 목록입니다. 텍스트 추출 중에 발견된 오류에 대한 정보를 포함합니다. 오류 검색은 TextSearchOptions.LogTextExtractionErrors = true인 경우에만 수행되며, 성능이 저하될 수 있습니다. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | 텍스트 추출 옵션을 가져오거나 설정합니다. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | 값은 텍스트 추출 중에 오류가 발견되었는지를 나타냅니다. 오류 검색은 TextSearchOptions.LogTextExtractionErrors = true인 경우에만 수행되며, 성능이 저하될 수 있습니다. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | `TextAbsorber`가 PDF 문서 또는 페이지에서 추출한 텍스트를 가져옵니다. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | 텍스트 검색 옵션을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | 지정된 문서에서 텍스트를 추출합니다. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | 지정된 페이지에서 텍스트를 추출합니다. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | 지정된 XForm에서 텍스트를 추출합니다. |

## 비고

`TextAbsorber` 객체는 PDF 문서 또는 문서의 페이지에서 텍스트를 추출하는 데 사용됩니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 텍스트를 추출하기 위해 TextAbsorber 객체를 생성합니다.
TextAbsorber absorber = new TextAbsorber();

// 첫 번째 페이지에 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 추출된 텍스트를 가져옵니다.
string extractedText = absorber.Text;

```

### 또 보기

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


