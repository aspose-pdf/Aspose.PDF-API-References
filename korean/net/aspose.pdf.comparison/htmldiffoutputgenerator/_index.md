---
title: "클래스 HtmlDiffOutputGenerator"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator 클래스. 텍스트 차이의 HTML 표현을 생성하기 위한 클래스를 나타냅니다. 삭제된 줄 바꿈은 단락 기호로 표시됩니다."
type: docs
weight: 3310
url: /ko/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

텍스트 차이의 HTML 표현을 생성하는 클래스를 나타냅니다. 삭제된 줄 바꿈은 단락 기호로 표시됩니다.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | `HtmlDiffOutputGenerator` 클래스의 인스턴스를 생성합니다. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | `HtmlDiffOutputGenerator` 클래스의 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | 삭제 작업에 대한 CSS 스타일 문자열을 가져오고 설정합니다. 예시: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | 동일 작업에 대한 CSS 스타일 문자열을 가져오고 설정합니다. 예시: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | 삽입 작업에 대한 CSS 스타일 문자열을 가져오고 설정합니다. 예시: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | 삭제 작업에 대한 text-decoration: line-through 스타일을 가져오거나 설정합니다. 기본값은 `False`입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |

### 또 보기

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


