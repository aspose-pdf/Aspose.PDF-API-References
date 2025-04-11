---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Stamp 클래스. 스탬프를 나타내는 클래스
type: docs
weight: 4720
url: /ko/net/aspose.pdf.facades/stamp/
---
## 스탬프 클래스

스탬프를 나타내는 클래스.

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
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | 투명도 및 혼합 작업을 수행하는 데 사용되는 색상 공간을 정의하는 BlendingColorSpace 값을 가져오거나 설정합니다. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | 배경 상태를 가져오거나 설정합니다. true이면 스탬프가 스탬프된 페이지의 배경으로 배치됩니다. 기본값은 false로 설정됩니다. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | 스탬프의 불투명도를 가져오거나 설정합니다. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | 페이지 번호를 가져오거나 설정합니다. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | 스탬프의 영향을 받을 페이지 번호 배열을 가져오거나 설정합니다. Pages가 null이면 문서의 모든 페이지에 영향을 미칩니다. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | 이미지 스탬프의 품질을 백분율로 가져오거나 설정합니다. 유효한 값은 0..100%입니다. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | 스탬프의 회전을 도 단위로 가져오거나 설정합니다. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | 스탬프의 식별자를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | 스탬프로 사용될 이미지를 설정합니다. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | 이미지를 스탬프로 설정합니다. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | 텍스트를 스탬프로 설정합니다. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | 스탬프로 사용될 PDF 파일과 페이지 번호를 설정합니다. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | 스탬프로 사용될 PDF 파일과 페이지 번호를 설정합니다. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | 스탬프 텍스트의 텍스트 상태를 설정합니다. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | 이미지 스탬프의 크기를 설정합니다. 이미지는 지정된 값에 따라 크기가 조정됩니다. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | 스탬프가 배치될 페이지의 위치를 설정합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)