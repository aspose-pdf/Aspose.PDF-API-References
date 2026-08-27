---
title: "열거형 ExplicitDestinationType"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations.ExplicitDestinationType 열거형. 명시적 목적지 유형을 열거합니다."
type: docs
weight: 1780
url: /ko/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enumeration

명시적 목적지 유형을 열거합니다.

```csharp
public enum ExplicitDestinationType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| XYZ | `0` | 창의 왼쪽 위 모서리에 좌표 (left, top)를 배치하고 페이지 내용을 zoom 배율만큼 확대하여 페이지를 표시합니다. left, top 또는 zoom 매개변수 중 어느 하나가 null 값이면 해당 매개변수의 현재 값이 변경되지 않고 유지됩니다. zoom 값이 0인 경우는 null 값과 동일한 의미입니다. |
| Fit | `1` | 페이지 내용을 가로와 세로 모두 창 안에 전체 페이지가 들어갈 만큼 충분히 확대하여 페이지를 표시합니다. 필요한 가로와 세로 확대 배율이 다르면 두 배율 중 작은 값을 사용하고, 다른 차원에서는 페이지를 창 중앙에 배치합니다. |
| FitH | `2` | 창의 상단 가장자리에 수직 좌표 top을 배치하고 페이지 내용을 창 안에 페이지 전체 너비가 들어갈 만큼 충분히 확대하여 페이지를 표시합니다. top이 null 값이면 해당 매개변수의 현재 값이 변경되지 않고 유지됩니다. |
| FitV | `3` | 창의 왼쪽 가장자리에 수평 좌표 left를 배치하고 페이지 내용을 창 안에 페이지 전체 높이가 들어갈 만큼 충분히 확대하여 페이지를 표시합니다. left가 null 값이면 해당 매개변수의 현재 값이 변경되지 않고 유지됩니다. |
| FitR | `4` | 페이지를 표시하고 내용물을 좌표 left, bottom, right, top으로 지정된 사각형이 창 안에 가로와 세로 모두 완전히 들어가도록 충분히 확대합니다. 필요한 가로 및 세로 확대 비율이 다르면 두 비율 중 작은 값을 사용하고, 다른 차원에서는 사각형을 창 중앙에 배치합니다. 매개변수 중 하나라도 null 값이면 예측할 수 없는 동작이 발생할 수 있습니다. |
| FitB | `5` | 페이지를 표시하고 내용물을 바운딩 박스가 창 안에 가로와 세로 모두 완전히 들어가도록 충분히 확대합니다. 필요한 가로 및 세로 확대 비율이 다르면 두 비율 중 작은 값을 사용하고, 다른 차원에서는 바운딩 박스를 창 중앙에 배치합니다. |
| FitBH | `6` | 페이지를 표시하고 세로 좌표 top이 창의 상단 가장자리에 위치하도록 하며, 페이지 내용물을 바운딩 박스의 전체 너비가 창 안에 들어가도록 충분히 확대합니다. top에 null 값을 지정하면 해당 매개변수의 현재 값이 변경되지 않고 유지됩니다. |
| FitBV | `7` | 페이지를 표시하고 가로 좌표 left가 창의 왼쪽 가장자리에 위치하도록 하며, 페이지 내용물을 바운딩 박스의 전체 높이가 창 안에 들어가도록 충분히 확대합니다. left에 null 값을 지정하면 해당 매개변수의 현재 값이 변경되지 않고 유지됩니다. |

### 또 보기

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


