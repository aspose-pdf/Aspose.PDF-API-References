---
title: "Enum PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy 열거형. 일부 문서는 PDF/A 형식으로 변환한 후 파일 크기가 크게 증가합니다. 이러한 문서의 파일 크기를 줄이려면 글꼴 제거 전략을 정의해야 합니다. 이 열거형은 글꼴 사용을 최적화하는 데 사용할 수 있는 전략을 선언합니다. 이 열거형의 각 전략은 OptimizeFileSize 플래그가 설정된 경우에만 의미가 있습니다."
type: docs
weight: 8540
url: /ko/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

일부 문서는 PDF/A 형식으로 변환한 후 파일 크기가 크게 증가합니다. 이러한 문서의 파일 크기를 줄이려면 글꼴 제거 전략을 정의해야 합니다. 이 열거형은 글꼴 사용을 최적화하는 데 사용할 수 있는 전략을 선언합니다. 이 열거형의 각 전략은 플래그 [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/)가 설정된 경우에만 의미가 있습니다.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | 이 전략은 문서에서 중복된 모든 글꼴을 제거합니다. 문서에 중복된 글꼴 그룹이 포함된 경우 해당 그룹에서 하나의 글꼴만 문서에 포함되고, 나머지 글꼴은 문서에서 제거되며, 제거된 각 글꼴은 이미 포함된 유사 글꼴로 대체됩니다. |
| RemoveSimilarFontsWithDifferentWidths | `1` | 이 전략은 RemoveDuplicatedFonts와 유사하지만 완전히 중복된 글꼴이 아니라 "Widths" 매개변수만 다른 유사한 글꼴을 제거합니다. 이 매개변수는 글꼴의 특정 기호에 대한 여러 너비 값을 포함합니다. "Widths" 집합의 각 너비 값은 실제 기호(글리프)의 너비가 아니라 시각적 너비를 의미합니다. 실제 너비는 글꼴의 바이너리 데이터에 정의되어 있으며, PDF 뷰어는 표시 시 이 시각적 너비를 사용합니다. 보다 정확히 말하면, Acrobat 5.0 이후 뷰어는 글꼴 사전에 저장된 글리프 너비를 사용해 글꼴 프로그램 자체의 너비를 재정의하여 문서의 표시와 인쇄 일관성을 향상시킵니다. 이 전략은 RemoveDuplicatedFonts보다 효과적이지만, 경우에 따라 변환된 문서의 시각적 표현을 손상시킬 수 있습니다. 선언된 글꼴 너비가 동일 기호에 대해 서로 다를 경우, 글꼴 교체 후 해당 기호의 시각적 너비가 변경되어 잘못 표시될 수 있으며, 텍스트 겹침 등 시각적 결함을 초래할 수 있습니다. 그러나 이러한 결함은 매우 드물며, 이 전략은 문서 크기를 더 효과적으로 감소시킵니다. |
| SubsetFonts | `2` | 이 전략은 문서 크기를 줄이는 가장 효과적인 방법입니다. 완전히 포함된 글꼴 세트를 가져와 사용된 서브셋만 남기도록 축소합니다. RemoveDuplicatedFonts 또는 RemoveSimilarFontsWithDifferentWidths와 함께 사용하면 파일 크기에 대한 다중 압축 효과를 얻을 수 있습니다. 세 가지 전략을 동시에 사용하는 것은 의미가 없으며, 이 경우 RemoveSimilarFontsWithDifferentWidths 전략은 사용되지 않습니다. |

### 또 보기

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


