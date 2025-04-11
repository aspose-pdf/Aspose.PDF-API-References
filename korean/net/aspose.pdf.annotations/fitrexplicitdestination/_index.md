---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FitRExplicitDestination 클래스. 좌표에 의해 지정된 사각형에 맞게 페이지와 그 내용을 충분히 확대하여 표시하는 명시적 대상을 나타냅니다. 이 사각형은 수평 및 수직으로 모두 창 안에 완전히 들어가야 합니다. 필요한 수평 및 수직 확대 배율이 다르면 두 값 중 작은 값을 사용하여 다른 차원에서 사각형을 중앙에 배치합니다. 매개변수 중 하나에 null 값이 있으면 예측할 수 없는 동작이 발생할 수 있습니다.
type: docs
weight: 1780
url: /ko/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination 클래스

좌표에 의해 지정된 사각형에 맞게 페이지와 그 내용을 충분히 확대하여 표시하는 명시적 대상을 나타냅니다. 이 사각형은 수평 및 수직으로 모두 창 안에 완전히 들어가야 합니다. 필요한 수평 및 수직 확대 배율이 다르면 두 값 중 작은 값을 사용하여 다른 차원에서 사각형을 중앙에 배치합니다. 매개변수 중 하나에 null 값이 있으면 예측할 수 없는 동작이 발생할 수 있습니다.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | 원격 명시적 대상을 생성합니다. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | 로컬 명시적 대상을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | 보이는 사각형의 하단 수직 좌표를 가져옵니다. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | 보이는 사각형의 왼쪽 수평 좌표를 가져옵니다. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 대상 페이지 객체를 가져옵니다. |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 대상 페이지 번호를 가져옵니다. |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | 보이는 사각형의 오른쪽 수평 좌표를 가져옵니다. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | 보이는 사각형의 상단 수직 좌표를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | 객체 상태를 문자열 값으로 변환합니다. 예: "1 FitR 100 200 300 400". |

### 참조

* 클래스 [ExplicitDestination](../explicitdestination/)
* 네임스페이스 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../)