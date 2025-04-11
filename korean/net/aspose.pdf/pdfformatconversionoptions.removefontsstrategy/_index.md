---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy 열거형. 일부 문서는 PDF/A 형식으로 변환한 후 큰 크기를 가집니다. 이러한 문서의 파일 크기를 줄이기 위해서는 글꼴 제거 전략을 정의하는 것이 필요합니다. 이 열거형은 글꼴 사용을 최적화하는 데 사용할 수 있는 전략을 선언합니다. 이 열거형의 모든 전략은 [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) 플래그가 설정된 경우에만 의미가 있습니다.
type: docs
weight: 8400
url: /ko/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy 열거형

일부 문서는 PDF/A 형식으로 변환한 후 큰 크기를 가집니다. 이러한 문서의 파일 크기를 줄이기 위해서는 글꼴 제거 전략을 정의하는 것이 필요합니다. 이 열거형은 글꼴 사용을 최적화하는 데 사용할 수 있는 전략을 선언합니다. 이 열거형의 모든 전략은 [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) 플래그가 설정된 경우에만 의미가 있습니다.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | 이 전략은 문서에서 중복된 모든 글꼴을 제거합니다. 문서에 중복된 글꼴 그룹이 포함되어 있는 경우, 이 그룹에서 하나의 글꼴만 문서에 포함됩니다. 이 그룹의 다른 모든 글꼴은 문서에서 제거되며, 제거된 각 글꼴은 이미 포함된 유사 글꼴로 대체됩니다. |
| RemoveSimilarFontsWithDifferentWidths | `1` | 이 전략은 RemoveDuplicatedFonts와 유사하지만 완전히 중복된 글꼴이 아닌 서로 유사하지만 "Widths" 매개변수만 다른 글꼴을 제거합니다. 이 매개변수는 특정 글꼴 기호에 대한 일부 너비의 집합을 포함합니다. 이 "Widths" 집합의 각 너비 값은 기호(글리프)의 실제 너비가 아니며, 이 기호의 실제 너비는 글꼴의 이진 데이터에서 이미 정의되어 있습니다. "Widths" 집합의 너비 값은 이 기호의 시각적 너비를 의미합니다 - PDF 뷰어 소프트웨어가 기호를 표시할 때 실제 너비 대신 설정해야 하는 너비입니다. 보다 정확하게 사양에서는: Acrobat 5.0 및 이후 버전의 뷰어는 글꼴 사전의 글리프 너비를 사용하여 글꼴 프로그램 자체의 글리프 너비를 재정의하여 문서의 표시 및 인쇄 일관성을 개선합니다. 이 전략은 RemoveDuplicatedFonts보다 더 효과적이지만, 이 전략을 사용하는 경우 이론적으로 변환된 문서의 시각적 표현이 손상될 수 있습니다. 이 결함은 선언된 글꼴의 너비가 동일한 기호에 대해 다를 수 있기 때문에 발생할 수 있으며, 이 경우 글꼴 대체 후 이 기호의 너비가 새 것으로 변경됩니다 - 제거된 글꼴이 문서에서 이미 포함된 글꼴로 대체될 때. 그리고 기호의 시각적 너비가 변경되면 잘못 표시될 수 있으며, 이 차이는 텍스트 겹침 또는 다른 문제와 같은 시각적 결함을 초래할 수 있습니다. 그러나 설명된 시각적 결함은 매우 드문 경우이며, 이 전략은 문서의 크기를 더 효과적으로 줄입니다. |
| SubsetFonts | `2` | 이것은 문서 크기를 줄이는 가장 효과적인 전략입니다. 완전히 포함된 글꼴 세트를 가져와서 사용된 하위 집합만 남깁니다. 이 전략은 RemoveDuplicatedFonts 또는 RemoveSimilarFontsWithDifferentWidths와 함께 사용하여 파일 크기에 대한 다중 압축 효과를 얻는 것이 좋습니다. 세 가지 전략을 동시에 사용하는 것은 의미가 없으며, 이 경우 RemoveSimilarFontsWithDifferentWidths 전략은 사용되지 않습니다. |

### 참조

* 클래스 [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)