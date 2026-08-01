---
title: "클래스 ImagePlacementAbsorber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.ImagePlacementAbsorber 클래스. 이미지 배치 객체의 흡수기 객체를 나타냅니다. 이미지 사용을 검색하고 검색 결과에 ImagePlacements 컬렉션을 통해 접근을 제공합니다."
type: docs
weight: 6040
url: /ko/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

이미지 배치 객체의 흡수기 객체를 나타냅니다. 이미지 사용을 검색하고 검색 결과에 [`ImagePlacements`](./imageplacements/) 컬렉션을 통해 접근을 제공합니다.

```csharp
public sealed class ImagePlacementAbsorber
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | [`ImagePlacement`](../imageplacement/) 객체로 표시되는 이미지 배치 발생의 컬렉션을 가져옵니다. |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | 구문 분석 작업 컬렉션에 대한 읽기 전용 모드를 가져오거나 설정합니다. 메모리 부족 예외를 방지하는 데 도움이 될 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | 지정된 문서에서 검색을 수행합니다. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | 지정된 페이지에서 검색을 수행합니다. |

## 비고

`ImagePlacementAbsorber` 객체는 기본적으로 이미지 검색 시나리오에서 사용됩니다. 검색이 완료되면 발생은 [`ImagePlacement`](../imageplacement/) 객체로 표시되며, 이는 [`ImagePlacements`](./imageplacements/) 컬렉션에 포함됩니다. [`ImagePlacement`](../imageplacement/) 객체는 이미지 배치 속성에 접근할 수 있게 합니다: 차원, 해상도 등. 이미지의 양의 회전은 반시계 방향이며, Page에 대해서는 시계 방향입니다. 여기서는 이미지 회전 각도를 나타내야 하므로 Page 각도를 이미지 각도에서 빼야 합니다.

## 예제

예제는 첫 번째 PDF Document Page에서 이미지를 찾고 이미지 배치 속성을 가져오는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 이미지 배치 검색을 수행하기 위해 ImagePlacementAbsorber 객체를 생성합니다.
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(abs);

// 모든 배치에 대한 이미지 배치 속성을 표시합니다.
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


