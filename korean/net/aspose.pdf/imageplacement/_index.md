---
title: "클래스 ImagePlacement"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.ImagePlacement 클래스. Pdf Document 페이지에 배치된 이미지의 특성을 나타냅니다."
type: docs
weight: 6030
url: /ko/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

PDF 문서 페이지에 배치된 이미지의 특성을 나타냅니다.

```csharp
public sealed class ImagePlacement
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | 페이지에 배치된 이미지에 대해 활성화된 그래픽 상태의 합성 매개변수를 가져옵니다. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | 관련 XImage 리소스 객체를 가져옵니다. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | 이 이미지에 대한 현재 변환 Matrix. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | 이미지를 표시하는 데 사용되는 연산자. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | 이미지를 포함하는 페이지를 가져옵니다. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | 이미지의 Rectangle을 가져옵니다. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | 이미지의 해상도를 가져옵니다. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | 이미지의 회전 각도를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | 페이지에서 이미지를 삭제합니다. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | 컬렉션의 이미지를 다른 이미지로 교체합니다. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | 이미지를 해당 변환(스케일링, 회전 및 해상도)과 함께 저장합니다. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | 이미지를 해당 변환(스케일링, 회전 및 해상도)과 함께 저장합니다. |

## 비고

이미지가 page에 배치될 때, [`Resources`](../resources/)에 정의된 물리적 차원과 다른 차원을 가질 수 있습니다. `ImagePlacement` 객체는 차원, 해상도 등과 같은 정보를 제공하도록 설계되었습니다.

## 예제

이 예제는 첫 번째 PDF document page에서 이미지를 찾고, 가시적인 차원을 가진 비트맵 이미지로 가져오는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 이미지 배치 검색을 수행하기 위해 ImagePlacementAbsorber 객체를 생성합니다.
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(abs);

// 가시적인 차원을 가진 이미지 가져오기
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // 리소스에서 이미지 가져오기
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // 실제 차원을 가진 새 비트맵 만들기
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


