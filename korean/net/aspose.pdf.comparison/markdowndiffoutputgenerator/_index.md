---
title: "클래스 MarkdownDiffOutputGenerator"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator 클래스. 텍스트 차이의 마크다운 표현을 생성하는 클래스를 나타냅니다. 마크다운 구문 때문에 공백 문자에 대한 변경을 표시할 수 없습니다. 변경 선택은 서식 주위에 공백 문자를 추가하도록 만들며, 그렇지 않으면 마크다운 뷰어가 텍스트를 올바르게 표시하지 못합니다. 삭제된 줄 바꿈은 단락 기호로 표시됩니다."
type: docs
weight: 3360
url: /ko/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class

텍스트 차이의 markdown 표현을 생성하는 클래스를 나타냅니다. markdown 구문 때문에 공백 문자 변경을 표시할 수 없습니다. 변경을 선택하면 서식 주변에 공백 문자를 추가하게 되며, 그렇지 않으면 markdown 뷰어가 텍스트를 올바르게 표시하지 못합니다. 삭제된 줄 바꿈은 - 단락 기호로 표시됩니다.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |

### 또 보기

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


