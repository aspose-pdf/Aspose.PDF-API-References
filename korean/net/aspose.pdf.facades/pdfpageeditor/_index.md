---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfPageEditor 클래스. 페이지 회전, 페이지 확대, 페이지 위치 이동 및 페이지 크기 변경을 포함하여 PDF 파일의 페이지를 편집하는 클래스를 나타냅니다.
type: docs
weight: 4590
url: /ko/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor 클래스

페이지 회전, 페이지 확대, 페이지 위치 이동 및 페이지 크기 변경을 포함하여 PDF 파일의 페이지를 편집하는 클래스를 나타냅니다.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | PdfPageEditor 클래스의 생성자입니다. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | PdfPageEditor 클래스의 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | 페이지의 표시 지속 시간을 가져오거나 설정합니다. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 문서 파사드를 가져옵니다. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | 결과 페이지에서 원본 PDF 콘텐츠의 수평 정렬을 가져오거나 설정합니다. 기본값은 AlignmentType.Left입니다. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | 페이지 번호와 회전 각도를 포함하는 해시 테이블입니다. 키는 페이지 번호를 나타내고, 키의 값은 각도를 나타냅니다. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | 출력 파일의 페이지 크기를 가져오거나 설정합니다. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | 편집할 페이지 번호를 가져오거나 설정합니다. 기본적으로 각 페이지가 편집됩니다. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | 페이지의 회전을 가져오거나 설정합니다. 회전은 0, 90, 180 또는 270이어야 합니다. 기본값은 0입니다. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | 전환 효과의 지속 시간을 가져오거나 설정합니다. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | 프레젠테이션 중 다른 페이지에서 이 페이지로 이동할 때 사용할 전환 스타일을 가져오거나 설정합니다. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | 결과 페이지에서 원본 PDF 콘텐츠의 수직 정렬을 가져오거나 설정합니다. 기본값은 VerticalAlignmentType.Bottom입니다. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | 확대 계수를 가져오거나 설정합니다. 값 1.0은 100%에 해당합니다. 기본값은 1.0입니다. 다음 예제는 문서 페이지의 확대를 변경하는 방법을 보여줍니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | 문서 페이지에 적용된 변경 사항을 적용합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 파사드를 초기화합니다. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 파사드와 연결된 Aspose.Pdf.Document를 해제합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 해제합니다. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | 문서에서 지정된 박스의 크기를 반환합니다. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | 지정된 페이지의 회전을 반환합니다. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | 총 페이지 수를 반환합니다. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | 지정된 페이지의 페이지 크기를 반환합니다. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | 원점을 (0, 0)에서 지정된 점으로 이동합니다. 원점은 왼쪽 하단이며 단위는 포인트(1인치 = 72포인트)입니다. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | 변경된 문서를 스트림에 저장합니다. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | 변경된 문서를 파일에 저장합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | 수직 블라인드 |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | 수직 블라인드 |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | 아래에서 위로 닦기 |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | 대각선 반짝임 |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | 이전 페이지가 녹아내립니다 |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | 내부 박스 |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | 왼쪽에서 오른쪽으로 반짝임 |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | 왼쪽에서 오른쪽으로 닦기 |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | 외부 박스 |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | 오른쪽에서 왼쪽으로 닦기 |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | 수평 분할 안 |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | 수평 분할 밖 |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | 수직 분할 안 |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | 수직 분할 밖 |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | 위에서 아래로 반짝임 |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | 위에서 아래로 닦기 |

### 참조

* 클래스 [SaveableFacade](../saveablefacade/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)