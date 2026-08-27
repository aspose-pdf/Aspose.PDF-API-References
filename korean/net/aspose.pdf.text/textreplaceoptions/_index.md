---
title: "클래스 TextReplaceOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextReplaceOptions 클래스. 텍스트 교체 옵션을 나타냅니다"
type: docs
weight: 11190
url: /ko/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

텍스트 교체 옵션을 나타냅니다.

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | `TextReplaceOptions` 객체의 새 인스턴스를 지정된 교체 후 작업에 대해 초기화합니다. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | `TextReplaceOptions` 객체의 새 인스턴스를 지정된 범위에 대해 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | 교체 조정이 강제로 새로운 텍스트 줄을 만들 때 사용되는 줄 간격 값을 가져오거나 설정합니다. 예상값은 교체된 텍스트의 글꼴 크기에 대한 배수이며, 기본값은 1.2입니다. |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | [`Rectangle`](./rectangle/) 로 정의된 경계에 맞게 글꼴 크기를 조정하는 정책을 가져오거나 설정합니다. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | 텍스트 교체 후 페이지의 텍스트를 조정할 때 별개의 단락을 무시할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | TextReplaceOptions를 사용할 때 교체된 텍스트의 왼쪽 위치 조정을 설정하거나 가져옵니다: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | 교체 후 텍스트에 맞추기 위한 rectangle을 가져오거나 설정합니다. |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | 텍스트 조각을 더 짧게 교체한 후 수행될 작업을 가져오거나 설정합니다. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | 텍스트 교체 작업이 적용되는 범위를 가져오거나 설정합니다. |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | TextReplaceOptions를 사용할 때 교체된 텍스트의 오른쪽 위치 조정을 설정하거나 가져옵니다: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### 또 보기

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


