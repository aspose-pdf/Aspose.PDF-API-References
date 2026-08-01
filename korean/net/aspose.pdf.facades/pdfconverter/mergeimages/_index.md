---
title: "PdfConverter.MergeImages"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfConverter 메서드. 이미지 스트림 목록을 하나의 이미지 스트림으로 병합합니다. 지원되지 않는 형식의 출력 스트림을 사용할 경우 기본적으로 JPEG로 인코딩되어 PNG/JPG/TIFF 출력 형식이 지원됩니다."
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

이미지 스트림 목록을 하나의 이미지 스트림으로 병합합니다. Png/jpg/tiff 출력 형식이 지원되며, 지원되지 않는 형식을 사용할 경우 출력 스트림은 기본적으로 Jpeg으로 인코딩됩니다.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputImagesStreams | List`1 | 병합할 이미지 스트림 목록입니다. |
| outputImageFormat | ImageFormat | 병합된 스트림의 이미지 출력 형식입니다. |
| mergeMode | ImageMergeMode | 병합 모드. Png/Jpg 형식에 사용됩니다. |
| horizontal | Nullable`1 | 출력 이미지 스트림의 캔버스 너비를 설정하기 위한 수평 비율입니다. ImageMergeMode.Center와 함께 사용할 때만 Png/Jpg 형식에 적용됩니다. |
| vertical | Nullable`1 | 출력 이미지 스트림의 캔버스 높이를 설정하기 위한 수직 비율입니다. ImageMergeMode.Center와 함께 사용할 때만 Png/Jpg 형식에 적용됩니다. |

### 반환 값

이미지 스트림이 출력 이미지 형식으로 인코딩됩니다.

### 또 보기

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


