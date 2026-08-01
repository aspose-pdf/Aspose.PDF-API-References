---
title: "클래스 PdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters 클래스. 페이지 크기 조정을 지정하기 위한 클래스. 다음 매개변수를 설정할 수 있습니다: 결과 Page의 크기(너비, 높이)를 기본 공간 단위 또는 초기 Page 크기의 백분율로 지정, 왼쪽, 위, 아래 및 오른쪽 여백을 기본 공간 단위 또는 초기 Page 크기의 백분율로 지정. 일부 값은 자동 계산을 위해 null로 둘 수 있습니다. 이러한 값은 명시적으로 지정된 값을 제외한 나머지 Page 크기에서 계산됩니다. 예를 들어 Page 너비가 100이고 새 Page 너비를 60 단위로 지정하면 왼쪽 및 오른쪽 여백이 자동으로 계산됩니다: (100 - 60) / 2 = 15. 이 클래스는 ResizeContents 메서드에서 사용됩니다."
type: docs
weight: 4600
url: /ko/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

페이지 크기 조정을 지정하기 위한 클래스. 다음 매개변수를 설정할 수 있습니다: 결과 Page의 크기(너비, 높이)를 기본 공간 단위 또는 초기 Page 크기의 백분율로 지정; 왼쪽, 위, 아래 및 오른쪽 여백을 기본 공간 단위 또는 초기 Page 크기의 백분율로 지정; 일부 값은 자동 계산을 위해 null로 둘 수 있습니다. 이러한 값은 명시적으로 지정된 값을 제외한 나머지 Page 크기에서 계산됩니다. 예: Page 너비 = 100이고 새 Page 너비를 60 단위로 지정하면 왼쪽 및 오른쪽 여백이 자동으로 계산됩니다: (100 - 60) / 2 = 15. 이 클래스는 ResizeContents 메서드에서 사용됩니다.

```csharp
public class ContentsResizeParameters
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | 모든 값이 "auto"로 설정된 크기 조정 매개변수를 생성합니다. 필요에 따라 나중에 여백 및 내용 크기를 지정할 수 있습니다. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | 지정된 여백 값과 내용 크기로 크기 조정 매개변수를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | 결과 Page의 아래쪽 여백을 가져오거나 설정합니다. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | 결과 Page에서 원본 Page 내용의 높이를 가져오거나 설정합니다. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | 결과 Page에서 원본 Page 내용의 너비를 가져오거나 설정합니다. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | 결과 Page의 왼쪽 여백을 가져오거나 설정합니다. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | 결과 Page의 오른쪽 여백을 가져오거나 설정합니다. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | 결과 Page의 위쪽 여백을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | 지정된 내용 크기로 크기 조정 매개변수를 생성합니다. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | 초기 Page 크기의 백분율로 지정된 내용 크기로 크기 조정 매개변수를 생성합니다. 여백은 자동으로 계산됩니다. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | 지정된 여백 값으로 크기 조정 매개변수를 생성합니다. 내용 크기는 자동으로 계산됩니다. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | 크기 조정 매개변수를 생성합니다. 여백은 초기 Page 크기의 백분율로 지정됩니다. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Page 크기 조정을 위한 크기 조정 매개변수를 생성합니다. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Page 크기 조정을 위한 크기 조정 매개변수를 생성합니다. 새로운 크기는 백분율로 지정됩니다. |

### 또 보기

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


