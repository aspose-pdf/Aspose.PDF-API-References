---
title: "열거형 LineJoin"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Operators.LineJoin 열거형. 선 결합 스타일은 스트로크된 경로의 모서리에서 사용될 형태를 지정합니다."
type: docs
weight: 7590
url: /ko/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

라인 조인 스타일은 스트로크된 경로의 코너에 사용될 형태를 지정해야 합니다.

```csharp
public enum LineJoin
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| MiterJoin | `0` | Miter 결합. 두 세그먼트의 스트로크 외곽이 사진 프레임처럼 각도에서 만날 때까지 연장됩니다. 세그먼트가 miter 제한 매개변수(8.4.3.5, "Miter Limit" 참조)로 정의된 너무 날카로운 각도로 만나면 대신 bevel 결합이 사용됩니다. |
| RoundJoin | `1` | Round 결합. 선 너비와 같은 지름을 가진 원의 호가 두 세그먼트가 만나는 지점 주위에 그려져 두 세그먼트의 스트로크 외곽을 연결합니다. 이 파이 조각 모양의 도형은 채워져 둥근 모서리를 생성합니다. |
| BevelJoin | `2` | Bevel 결합. 두 세그먼트는 butt 캡(8.4.3.3, "Line Cap Style" 참조)으로 마무리되며, 세그먼트 끝을 넘어선 결과 노치는 삼각형으로 채워집니다. |

### 또 보기

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


