---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacement 클래스. Pdf 문서 페이지에 배치된 이미지의 특성을 나타냅니다.
type: docs
weight: 5900
url: /ko/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

Pdf 문서 페이지에 배치된 이미지의 특성을 나타냅니다.

```csharp
public sealed class ImagePlacement
```

## Properties

| Name | Description |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | 페이지에 배치된 이미지에 대해 활성화된 그래픽 상태의 합성 매개변수를 가져옵니다. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | 관련된 XImage 리소스 객체를 가져옵니다. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | 이 이미지의 현재 변환 행렬입니다. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | 이미지를 표시하는 데 사용되는 연산자입니다. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | 이미지를 포함하는 페이지를 가져옵니다. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | 이미지의 사각형을 가져옵니다. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | 이미지의 해상도를 가져옵니다. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | 이미지의 회전 각도를 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | 페이지에서 이미지를 삭제합니다. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | 컬렉션의 이미지를 다른 이미지로 교체합니다. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | 해당 변환(스케일링, 회전 및 해상도)으로 이미지를 저장합니다. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | 해당 변환(스케일링, 회전 및 해상도)으로 이미지를 저장합니다. |

## Remarks

이미지가 페이지에 배치될 때 [`Resources`](../resources/)에 정의된 물리적 치수와 다른 치수를 가질 수 있습니다. 객체 `ImagePlacement`는 치수, 해상도 등의 정보를 제공하기 위해 설계되었습니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 이미지를 찾고 가시적인 치수를 가진 비트맵으로 이미지를 가져오는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)