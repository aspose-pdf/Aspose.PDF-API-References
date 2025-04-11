---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator 클래스. 텍스트 차이의 마크다운 표현을 생성하는 클래스를 나타냅니다. 마크다운 구문 때문에 공백 문자에 대한 변경 사항을 표시할 수 없습니다. 변경 사항 선택은 포맷 주위에 공백 문자를 추가하게 하며, 그렇지 않으면 마크다운 뷰어가 텍스트를 올바르게 표시하지 않습니다. 삭제된 줄 바꿈은 단락 기호로 표시됩니다.
type: docs
weight: 3250
url: /ko/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator 클래스

텍스트 차이의 마크다운 표현을 생성하는 클래스를 나타냅니다. 마크다운 구문 때문에 공백 문자에 대한 변경 사항을 표시할 수 없습니다. 변경 사항 선택은 포맷 주위에 공백 문자를 추가하게 하며, 그렇지 않으면 마크다운 뷰어가 텍스트를 올바르게 표시하지 않습니다. 삭제된 줄 바꿈은 - 단락 기호로 표시됩니다.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | 텍스트 간의 차이를 기반으로 출력을 생성하고 파일에 저장합니다. |

### 참조

* 인터페이스 [IFileOutputGenerator](../ifileoutputgenerator/)
* 인터페이스 [IStringOutputGenerator](../istringoutputgenerator/)
* 네임스페이스 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* 어셈블리 [Aspose.PDF](../../)