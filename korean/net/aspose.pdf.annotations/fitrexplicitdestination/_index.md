---
title: "클래스 FitRExplicitDestination"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations.FitRExplicitDestination 클래스. 좌표 왼쪽, 아래, 오른쪽, 위 로 지정된 사각형이 창 안에 가로·세로 모두 완전히 들어가도록 페이지와 그 내용을 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. 필요한 가로와 세로 확대 비율이 다르면, 두 비율 중 작은 값을 사용하고 다른 차원에서는 사각형을 창 중앙에 맞춥니다. 매개변수 중 하나라도 null 값이면 예측할 수 없는 동작이 발생할 수 있습니다."
type: docs
weight: 1870
url: /ko/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class

좌표 left, bottom, right, top으로 지정된 사각형이 창 안에 완전히 들어가도록 페이지 내용을 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. 수평 및 수직 확대 비율이 다르면 두 비율 중 작은 값을 사용하고, 다른 차원에서는 사각형을 창 중앙에 배치합니다. 매개변수 중 하나에 null 값을 지정하면 예측할 수 없는 동작이 발생할 수 있습니다.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | 원격 명시적 목적지를 생성합니다. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | 로컬 명시적 목적지를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | 보이는 사각형의 아래쪽 수직 좌표를 가져옵니다. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | 보이는 사각형의 왼쪽 가로 좌표를 가져옵니다. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 목적지 페이지 객체를 가져옵니다. |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 목적지 페이지 번호를 가져옵니다. |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | 보이는 사각형의 오른쪽 가로 좌표를 가져옵니다. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | 보이는 사각형의 위쪽 수직 좌표를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | 객체 상태를 문자열 값으로 변환합니다. 예: "1 FitR 100 200 300 400". |

### 또 보기

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


