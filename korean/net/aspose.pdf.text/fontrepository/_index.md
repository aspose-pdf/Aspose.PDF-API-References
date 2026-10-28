---
title: "클래스 FontRepository"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.FontRepository 클래스. 폰트 검색을 수행합니다. 시스템에 설치된 폰트와 표준 Pdf 폰트를 검색합니다. 또한 사용자 정의 폰트를 열 수 있는 기능을 제공합니다."
type: docs
weight: 10720
url: /ko/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

글꼴 검색을 수행합니다. 시스템에 설치된 글꼴과 표준 Pdf 글꼴을 검색합니다. 또한 사용자 정의 글꼴을 열 수 있는 기능을 제공합니다.

```csharp
public sealed class FontRepository
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FontRepository](fontrepository/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | 폰트 소스 컬렉션을 가져옵니다. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | 폰트 대체 전략 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | 지정된 폰트 이름으로 폰트를 검색하고 반환합니다. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | 대소문자 구분을 무시하거나 존중하여 지정된 폰트 이름으로 폰트를 검색하고 반환합니다. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | 지정된 폰트 이름과 폰트 스타일로 폰트를 검색하고 반환합니다. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | 대소문자 구분을 무시하거나 존중하여 지정된 폰트 이름과 폰트 스타일로 폰트를 검색하고 반환합니다. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | 시스템에 설치된 폰트와 표준 Pdf 폰트를 로드합니다. 이 메서드는 폰트 로드 프로세스를 가속화하도록 설계되었습니다. 기본적으로 폰트는 첫 번째 폰트 요청 시 로드됩니다. 이 메서드를 사용하면 Pdf 문서가 열리기 전에 시스템 및 표준 Pdf 폰트를 즉시 로드합니다. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | 지정된 폰트 파일 경로로 폰트를 엽니다. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | 지정된 폰트 스트림으로 폰트를 엽니다. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | 지정된 폰트 파일 경로와 메트릭스 파일 경로로 폰트를 엽니다. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | 속성 [`Sources`](./sources/)에 지정된 모든 폰트를 다시 로드합니다. |

## 예제

이 예제는 폰트를 찾고 첫 페이지 텍스트의 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 폰트 찾기
Font font = FontRepository.FindFont("Arial");

// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 폰트를 변경합니다
absorber.TextFragments[1].TextState.Font = font;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


