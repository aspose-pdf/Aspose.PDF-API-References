---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentAbsorber 클래스. 텍스트 조각의 흡수기 객체를 나타냅니다. 텍스트 검색을 수행하고 TextFragments 컬렉션을 통해 검색 결과에 접근할 수 있습니다.
type: docs
weight: 10950
url: /ko/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber 클래스

텍스트 조각의 흡수기 객체를 나타냅니다. 텍스트 검색을 수행하고 [`TextFragments`](./textfragments/) 컬렉션을 통해 검색 결과에 접근할 수 있습니다.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | 문서 또는 페이지의 모든 텍스트 세그먼트를 검색하는 `TextFragmentAbsorber`의 새 인스턴스를 초기화합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | 지정된 System.Text.RegularExpressions.Regex 클래스 객체에 대한 `TextFragmentAbsorber` 클래스의 새 인스턴스를 초기화합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | 지정된 텍스트 구문에 대한 `TextFragmentAbsorber` 클래스의 새 인스턴스를 초기화합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | 텍스트 편집 옵션으로 `TextFragmentAbsorber`의 새 인스턴스를 초기화하며, 문서 또는 페이지의 모든 텍스트 세그먼트를 검색합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | 지정된 텍스트 구문 및 텍스트 편집 옵션에 대한 `TextFragmentAbsorber` 클래스의 새 인스턴스를 초기화합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | 지정된 텍스트 구문 및 텍스트 검색 옵션에 대한 `TextFragmentAbsorber` 클래스의 새 인스턴스를 초기화합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | 지정된 텍스트 구문 및 텍스트 검색 옵션에 대한 `TextFragmentAbsorber` 클래스의 새 인스턴스를 초기화합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | 지정된 텍스트 구문 및 텍스트 편집 옵션에 대한 `TextFragmentAbsorber` 클래스의 새 인스턴스를 초기화합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | 지정된 텍스트 구문 및 텍스트 검색 옵션에 대한 `TextFragmentAbsorber` 클래스의 새 인스턴스를 초기화합니다. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | 지정된 텍스트 구문, 텍스트 검색 옵션 및 텍스트 편집 옵션에 대한 `TextFragmentAbsorber` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | 텍스트 추출 중 발견된 오류에 대한 정보를 포함하는 [`TextExtractionError`](../textextractionerror/) 객체의 목록입니다. 오류 검색은 TextSearchOptions.LogTextExtractionErrors = true일 때만 수행됩니다. 성능이 저하될 수 있습니다. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | 텍스트 추출 옵션을 가져오거나 설정합니다. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | 텍스트 추출 중 오류가 발견되었는지를 나타내는 값입니다. 오류 검색은 TextSearchOptions.LogTextExtractionErrors = true일 때만 수행됩니다. 성능이 저하될 수 있습니다. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | `TextFragmentAbsorber`가 PDF 문서 또는 페이지에서 검색하는 구문을 가져오거나 설정합니다. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | System.Text.RegularExpressions.Regex 클래스를 키로 하고 [`TextFragment`](../textfragment/)를 값으로 하는 검색 발생의 사전을 가져옵니다. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | [`TextAbsorber`](../textabsorber/)가 PDF 문서 또는 페이지에서 추출한 텍스트를 가져옵니다. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | 텍스트 편집 옵션을 가져오거나 설정합니다. 이 옵션은 요청된 기호를 글꼴로 쓸 수 없을 때의 특별한 동작을 정의합니다. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 검색 발생의 컬렉션을 가져오거나 설정합니다. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | 텍스트 교체 옵션을 가져오거나 설정합니다. 이 옵션은 조각 텍스트가 더 짧거나 긴 것으로 교체될 때의 동작을 정의합니다. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | 검색 옵션을 가져오거나 설정합니다. 이 옵션은 정규 표현식을 사용한 검색을 가능하게 합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | 흡수된 모든 텍스트 조각에 대해 글꼴 크기를 적용합니다. 페이지의 모든 조각이 흡수된 경우 조각을 반복하는 것보다 빠르게 작동합니다. 그렇지 않으면 반복하는 것과 유사하게 작동합니다. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | 흡수된 모든 텍스트 조각에 대해 글꼴을 적용합니다. 페이지의 모든 조각이 흡수된 경우 조각을 반복하는 것보다 빠르게 작동합니다. 그렇지 않으면 반복하는 것과 유사하게 작동합니다. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | 흡수된 모든 텍스트 조각에 대해 글꼴과 크기를 적용합니다. 페이지의 모든 조각이 흡수된 경우 조각을 반복하는 것보다 빠르게 작동합니다. 그렇지 않으면 반복하는 것과 유사하게 작동합니다. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | 문서에서 모든 텍스트를 제거합니다. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | 지정된 페이지에서 모든 텍스트를 제거합니다. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | 지정된 페이지에서 지정된 사각형 내부의 텍스트를 제거합니다. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | 이 `TextFragmentAbsorber` 객체의 TextFragments 컬렉션을 지웁니다. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | 지정된 문서에서 검색을 수행합니다. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | 지정된 페이지에서 검색을 수행합니다. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | 지정된 양식 객체에서 검색을 수행합니다. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | 지정된 XForm에서 텍스트를 추출합니다. |

## 비고

`TextFragmentAbsorber` 객체는 기본적으로 텍스트 검색 시나리오에서 사용됩니다. 검색이 완료되면 발생은 [`TextFragment`](../textfragment/) 객체로 표현되며, 이 객체는 [`TextFragments`](./textfragments/) 컬렉션에 포함됩니다. [`TextFragment`](../textfragment/) 객체는 검색 발생 텍스트, 텍스트 속성에 접근할 수 있게 하며, 텍스트를 편집하고 텍스트 상태(글꼴, 글꼴 크기, 색상 등)를 변경할 수 있습니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 텍스트와 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* 클래스 [TextAbsorber](../textabsorber/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)