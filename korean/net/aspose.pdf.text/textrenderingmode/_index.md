---
title: Enum TextRenderingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextRenderingMode 열거형. 텍스트 렌더링 모드 Tmode는 텍스트 표시가 글리프 윤곽선을 스트로크, 채우기, 클리핑 경계로 사용하거나 이 세 가지의 조합 중 하나를 결정하는지 여부를 나타냅니다.
type: docs
weight: 11000
url: /ko/net/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode 열거형

텍스트 렌더링 모드 Tmode는 텍스트 표시가 글리프 윤곽선을 스트로크, 채우기, 클리핑 경계로 사용하거나 이 세 가지의 조합 중 하나를 결정하는지 여부를 나타냅니다.

```csharp
public enum TextRenderingMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| FillText | `0` | 텍스트 채우기. |
| StrokeText | `1` | 텍스트 스트로크. |
| FillThenStrokeText | `2` | 텍스트를 채운 후 스트로크. |
| Invisible | `3` | 텍스트를 채우거나 스트로크하지 않음 (보이지 않음). |
| FillTextAndAddPathToClipping | `4` | 텍스트를 채우고 클리핑을 위한 경로에 추가 (9.3.6, "텍스트 렌더링 모드" 참조). |
| StrokeTextAndAddPathToClipping | `5` | 텍스트를 스트로크하고 클리핑을 위한 경로에 추가. |
| FillThenStrokeTextAndAddPathToClipping | `6` | 텍스트를 채운 후 스트로크하고 클리핑을 위한 경로에 추가. |
| AddPathToClipping | `7` | 클리핑을 위한 경로에 텍스트 추가. |

### 참조

* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)