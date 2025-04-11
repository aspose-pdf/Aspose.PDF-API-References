---
title: Class SetGlyphsPositionShowText
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetGlyphsPositionShowText 클래스. 글리프 위치 지정을 포함한 텍스트 표시를 위한 TJ 연산자를 나타내는 클래스
type: docs
weight: 7710
url: /ko/net/aspose.pdf.operators/setglyphspositionshowtext/
---
## SetGlyphsPositionShowText 클래스

TJ 연산자(글리프 위치 지정을 포함한 텍스트 표시)를 나타내는 클래스입니다.

```csharp
public class SetGlyphsPositionShowText : TextShowOperator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SetGlyphsPositionShowText](setglyphspositionshowtext/)(IEnumerable&lt;GlyphPosition&gt;) | TJ 연산자를 위한 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [GlyphPositions](../../aspose.pdf.operators/setglyphspositionshowtext/glyphpositions/) { get; } | 글리프의 위치를 반환합니다. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 페이지 연산자 목록에서의 연산자 인덱스입니다. |
| override [Text](../../aspose.pdf.operators/setglyphspositionshowtext/text/) { get; } | 연산자 인수에서 텍스트를 가져옵니다(글리프 위치 지정은 무시됩니다). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setglyphspositionshowtext/accept/)(IOperatorSelector) | 연산자를 처리하기 위해 방문자 객체를 수락합니다. |
| override [ToString](../../aspose.pdf.operators/setglyphspositionshowtext/tostring/)() | 연산자의 텍스트 표현을 반환합니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |

### 참조

* 클래스 [TextShowOperator](../textshowoperator/)
* 네임스페이스 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 어셈블리 [Aspose.PDF](../../)