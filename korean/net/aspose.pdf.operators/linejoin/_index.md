---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin 열거형. 선 조인 스타일은 스트로크된 경로의 모서리에서 사용될 모양을 지정해야 합니다.
type: docs
weight: 7450
url: /ko/net/aspose.pdf.operators/linejoin/
---
## LineJoin 열거형

선 조인 스타일은 스트로크된 경로의 모서리에서 사용될 모양을 지정해야 합니다.

```csharp
public enum LineJoin
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| MiterJoin | `0` | 미터 조인. 두 세그먼트의 외부 가장자리는 각도에서 만날 때까지 연장되어야 하며, 이는 사진 프레임과 같습니다. 세그먼트가 미터 한계 매개변수에 의해 정의된 너무 날카로운 각도로 만나는 경우(8.4.3.5, "미터 한계" 참조), 대신 베벨 조인이 사용되어야 합니다. |
| RoundJoin | `1` | 둥근 조인. 두 세그먼트가 만나는 지점 주위에 선 너비와 같은 지름을 가진 원호가 그려져야 하며, 두 세그먼트의 외부 가장자를 연결합니다. 이 파이 조각 모양의 도형은 채워져 둥근 모서리를 생성합니다. |
| BevelJoin | `2` | 베벨 조인. 두 세그먼트는 버트 캡으로 마무리되어야 하며(8.4.3.3, "선 캡 스타일" 참조), 세그먼트 끝 너머의 결과적인 홈은 삼각형으로 채워져야 합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 어셈블리 [Aspose.PDF](../../)