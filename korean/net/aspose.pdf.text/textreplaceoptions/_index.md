---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptions 클래스. 텍스트 교체 옵션을 나타냅니다.
type: docs
weight: 11010
url: /ko/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions 클래스

텍스트 교체 옵션을 나타냅니다.

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | 지정된 교체 작업 후에 대한 `TextReplaceOptions` 객체의 새 인스턴스를 초기화합니다. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | 지정된 범위에 대한 `TextReplaceOptions` 객체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | 텍스트 교체가 강제로 새 줄을 생성할 때 사용되는 줄 간격의 값을 가져오거나 설정합니다. 예상되는 값은 교체된 텍스트의 글꼴 크기의 배수입니다. 기본값은 1.2입니다. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | 텍스트 교체 후 페이지에서 텍스트를 조정할 때 별개의 단락을 무시할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | TextReplaceOptions를 사용할 때 교체된 텍스트의 왼쪽 위치 조정을 설정하거나 가져옵니다: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | 더 짧은 텍스트 조각으로 교체된 후 수행될 작업을 가져오거나 설정합니다. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | 텍스트 교체 작업이 적용되는 범위를 가져오거나 설정합니다. |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | TextReplaceOptions를 사용할 때 교체된 텍스트의 오른쪽 위치 조정을 설정하거나 가져옵니다: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### 참조

* 클래스 [TextOptions](../textoptions/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)