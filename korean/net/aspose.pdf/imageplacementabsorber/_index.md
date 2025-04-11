---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacementAbsorber 클래스. 이미지 배치 객체의 흡수기 객체를 나타냅니다. 이미지 사용을 검색하고 [`ImagePlacements`](./imageplacements/) 컬렉션을 통해 검색 결과에 접근합니다.
type: docs
weight: 5910
url: /ko/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber 클래스

이미지 배치 객체의 흡수기 객체를 나타냅니다. 이미지 사용을 검색하고 [`ImagePlacements`](./imageplacements/) 컬렉션을 통해 검색 결과에 접근합니다.

```csharp
public sealed class ImagePlacementAbsorber
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | [`ImagePlacement`](../imageplacement/) 객체로 표현되는 이미지 배치 발생의 컬렉션을 가져옵니다. |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | 파싱 작업 컬렉션에 대한 읽기 전용 모드를 가져오거나 설정합니다. 이는 메모리 부족 예외를 방지하는 데 도움이 될 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | 지정된 문서에서 검색을 수행합니다. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | 지정된 페이지에서 검색을 수행합니다. |

## 비고

`ImagePlacementAbsorber` 객체는 기본적으로 이미지 검색 시나리오에서 사용됩니다. 검색이 완료되면 발생은 [`ImagePlacement`](../imageplacement/) 객체로 표현되며, 이 객체는 [`ImagePlacements`](./imageplacements/) 컬렉션에 포함됩니다. [`ImagePlacement`](../imageplacement/) 객체는 이미지 배치 속성에 대한 접근을 제공합니다: 치수, 해상도 등. 이미지의 긍정적인 회전은 반시계 방향이며, 페이지의 경우 시계 방향입니다. 여기서 우리는 이미지 회전 각도를 나타내야 하므로 페이지 각도를 이미지 각도에서 빼야 합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 이미지를 찾고 이미지 배치 속성을 가져오는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
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

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)