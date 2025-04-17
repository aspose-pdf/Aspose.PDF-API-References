---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters 클래스. 페이지 크기 조정 매개변수를 지정하는 클래스. 다음 매개변수를 설정할 수 있습니다 결과 페이지의 크기（너비, 높이） 기본 공간 단위 또는 초기 페이지 크기의 백분율; 기본 공간 단위 또는 초기 페이지 크기의 백분율로 왼쪽, 위, 아래 및 오른쪽 여백; 일부 값은 자동 계산을 위해 null로 남길 수 있습니다. 이러한 값은 명시적으로 지정된 값의 계산 후 나머지 페이지 크기에서 계산됩니다. 예를 들어, 페이지 너비가 100이고 새 페이지 너비가 60으로 지정되면 왼쪽 및 오른쪽 여백은 자동으로 계산됩니다 （100 - 60） / 2 = 15. 이 클래스는 ResizeContents 메서드에서 사용됩니다.
type: docs
weight: 4480
url: /ko/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters 클래스

페이지 크기 조정 매개변수를 지정하는 클래스. 다음 매개변수를 설정할 수 있습니다: 결과 페이지의 크기(너비, 높이) 기본 공간 단위 또는 초기 페이지 크기의 백분율; 왼쪽, 위, 아래 및 오른쪽 여백 기본 공간 단위 또는 초기 페이지 크기의 백분율; 일부 값은 자동 계산을 위해 null로 남길 수 있습니다. 이러한 값은 명시적으로 지정된 값의 계산 후 나머지 페이지 크기에서 계산됩니다. 예를 들어: 페이지 너비 = 100이고 새 페이지 너비가 60으로 지정되면 왼쪽 및 오른쪽 여백은 자동으로 계산됩니다: (100 - 60) / 2 = 15. 이 클래스는 ResizeContents 메서드에서 사용됩니다.

```csharp
public class ContentsResizeParameters
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | 모든 값이 "자동"으로 설정된 크기 조정 매개변수를 생성합니다. 나중에 필요에 따라 여백 및 내용 크기를 지정할 수 있습니다. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | 지정된 여백 값과 내용 크기로 크기 조정 매개변수를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | 결과 페이지의 아래쪽 여백을 가져오거나 설정합니다. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | 결과 페이지의 소스 페이지 내용의 높이를 가져오거나 설정합니다. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | 결과 페이지의 소스 페이지 내용의 너비를 가져오거나 설정합니다. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | 결과 페이지의 왼쪽 여백을 가져오거나 설정합니다. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | 결과 페이지의 오른쪽 여백을 가져오거나 설정합니다. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | 결과 페이지의 위쪽 여백을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | 지정된 내용 크기로 크기 조정 매개변수를 생성합니다. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | 초기 페이지 크기의 백분율로 지정된 내용 크기로 크기 조정 매개변수를 생성합니다. 여백은 자동으로 계산됩니다. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | 지정된 여백 값으로 크기 조정 매개변수를 생성합니다. 내용 크기는 자동으로 계산됩니다. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | 크기 조정 매개변수를 생성합니다. 여백은 초기 페이지 크기의 백분율로 지정됩니다. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | 페이지 크기 조정을 위한 크기 조정 매개변수를 생성합니다. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | 페이지 크기 조정을 위한 크기 조정 매개변수를 생성합니다. 새 크기는 백분율로 지정됩니다. |

### 참조

* 클래스 [PdfFileEditor](../pdffileeditor/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)