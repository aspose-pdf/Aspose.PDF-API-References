---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer 속성. 보기 및 인쇄 중 해상도를 가져오거나 설정합니다. 해상도가 높을수록 속도가 느려집니다. 기본값은 150입니다.
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution 속성

보기 및 인쇄 중 해상도를 가져오거나 설정합니다. 해상도가 높을수록 속도가 느려집니다. 기본값은 150입니다.

```csharp
public int Resolution { get; set; }
```

## 비고

이 속성은 페이지를 이미지로 변환하는 흐름에서 이미지 해상도를 변경합니다: [`PrintAsImage`](../printasimage/)가 `true`로 설정되거나 [`DecodePage`](../decodepage/) 또는 [`DecodeAllPages`](../decodeallpages/) 메서드가 호출될 때. 프린터에 직접 인쇄하기 위한 프린터 해상도를 설정하려면 [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) 클래스의 [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) 속성을 사용하십시오.

### 참조

* 클래스 [PdfViewer](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)