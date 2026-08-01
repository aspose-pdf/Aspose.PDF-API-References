---
title: "클래스 Stamp"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.Stamp 클래스. 스탬프를 나타내는 클래스"
type: docs
weight: 4840
url: /ko/net/aspose.pdf.facades/stamp/
---
## Stamp class

스탬프를 나타내는 클래스입니다.

```csharp
public sealed class Stamp
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Stamp](stamp/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | 페이지에서 투명도 및 블렌딩 작업을 수행하는 데 사용되는 색 공간을 정의하는 BlendingColorSpace 값을 가져오거나 설정합니다. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | 배경 상태를 가져오거나 설정합니다. true인 경우 스탬프가 해당 페이지의 배경으로 배치됩니다. 기본값은 false입니다. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | 스탬프의 불투명도를 가져오거나 설정합니다. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | 페이지 번호를 가져오거나 설정합니다. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | 스탬프에 의해 영향을 받을 페이지 번호 배열을 가져오거나 설정합니다. Pages가 null인 경우 문서의 모든 페이지가 영향을 받습니다. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | 이미지 스탬프의 품질을 백분율로 가져오거나 설정합니다. 허용 값은 0..100%입니다. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | 스탬프의 회전을 도 단위로 가져오거나 설정합니다. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | 스탬프의 식별자를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | 스탬프로 사용할 이미지를 설정합니다. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | 이미지를 스탬프로 설정합니다. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | 텍스트를 스탬프로 설정합니다. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | 스탬프로 사용할 PDF 파일과 페이지 번호를 설정합니다. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | 스탬프로 사용할 PDF 파일과 페이지 번호를 설정합니다. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | 스탬프 텍스트의 텍스트 상태를 설정합니다. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | 이미지 스탬프의 크기를 설정합니다. 이미지는 지정된 값에 따라 스케일됩니다. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | 스탬프가 배치될 페이지상의 위치를 설정합니다. |

### 또 보기

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


