---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontRepository 클래스. 글꼴 검색을 수행합니다. 시스템에 설치된 글꼴과 표준 Pdf 글꼴에서 검색합니다. 또한 사용자 정의 글꼴을 열 수 있는 기능을 제공합니다.
type: docs
weight: 10540
url: /ko/net/aspose.pdf.text/fontrepository/
---
## FontRepository 클래스

글꼴 검색을 수행합니다. 시스템에 설치된 글꼴과 표준 Pdf 글꼴에서 검색합니다. 또한 사용자 정의 글꼴을 열 수 있는 기능을 제공합니다.

```csharp
public sealed class FontRepository
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FontRepository](fontrepository/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | 글꼴 소스 컬렉션을 가져옵니다. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | 글꼴 대체 전략 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | 지정된 글꼴 이름으로 글꼴을 검색하고 반환합니다. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | 대소문자 구분을 무시하거나 존중하여 지정된 글꼴 이름으로 글꼴을 검색하고 반환합니다. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | 지정된 글꼴 이름과 글꼴 스타일로 글꼴을 검색하고 반환합니다. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | 대소문자 구분을 무시하거나 존중하여 지정된 글꼴 이름과 글꼴 스타일로 글꼴을 검색하고 반환합니다. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | 시스템에 설치된 글꼴과 표준 Pdf 글꼴을 로드합니다. 이 메서드는 글꼴 로딩 프로세스를 가속화하기 위해 설계되었습니다. 기본적으로 글꼴은 모든 글꼴에 대한 첫 번째 요청 시 로드됩니다. 이 메서드를 사용하면 Pdf 문서가 열리기 전에 시스템 및 표준 Pdf 글꼴이 즉시 로드됩니다. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | 지정된 글꼴 파일 경로로 글꼴을 엽니다. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | 지정된 글꼴 스트림으로 글꼴을 엽니다. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | 지정된 글꼴 파일 경로와 메트릭스 파일 경로로 글꼴을 엽니다. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | 속성 [`Sources`](./sources/)에 의해 지정된 모든 글꼴을 다시 로드합니다. |

## 예제

이 예제는 글꼴을 찾고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* 클래스 [TextFragmentAbsorber](../textfragmentabsorber/)
* 클래스 [Document](../../aspose.pdf/document/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)