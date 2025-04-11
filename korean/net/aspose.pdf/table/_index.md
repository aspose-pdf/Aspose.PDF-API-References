---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Table 클래스. 페이지에 추가할 수 있는 테이블을 나타냅니다.
type: docs
weight: 10280
url: /ko/net/aspose.pdf/table/
---
## 테이블 클래스

페이지에 추가할 수 있는 테이블을 나타냅니다.

```csharp
public sealed class Table : BaseParagraph
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Table](table/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | 테이블 정렬을 가져오거나 설정합니다. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | 테이블 배경 색상을 가져오거나 설정합니다. |
| [Border](../../aspose.pdf/table/border/) { get; set; } | 테두리를 가져오거나 설정합니다. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | 테이블의 줄 바꿈 텍스트를 가져오거나 설정합니다. |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | 테이블의 수직 분할을 가져오거나 설정합니다. |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | 테이블 열 조정을 가져오거나 설정합니다. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | 테이블의 열 너비를 가져옵니다. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | 테두리 모서리의 스타일을 가져오거나 설정합니다. |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | 기본 셀 테두리를 가져옵니다. |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | 기본 셀 패딩을 가져오거나 설정합니다. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | 기본 셀 텍스트 상태를 가져오거나 설정합니다. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | 기본 열 너비를 가져오거나 설정합니다. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 단락의 수평 정렬을 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( PDF 생성기용). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | 열 너비에 포함된 테두리를 가져오거나 설정합니다. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | 테이블이 분할되었는지 여부를 가져오거나 설정합니다 - 다음 페이지에서 잘립니다. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다( PDF 생성용). |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다( PDF 생성용). |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다( PDF 생성용). |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다( PDF 생성용). |
| [Left](../../aspose.pdf/table/left/) { get; set; } | 테이블의 왼쪽 좌표를 가져오거나 설정합니다. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다( PDF 생성용). |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | 테이블의 최대 열 수를 가져오거나 설정합니다. |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | 여러 페이지에 대해 반복되는 첫 번째 행 수를 가져옵니다. |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | 반복되는 행의 스타일을 가져오거나 설정합니다. |
| [Rows](../../aspose.pdf/table/rows/) { get; } | 테이블의 행을 가져옵니다. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | 테이블의 위쪽 좌표를 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | 테이블을 복제합니다. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | 높이를 가져옵니다. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | 너비를 가져옵니다. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | 데이터의 1차원 배열을 테이블에 가져옵니다. 가져오기는 각 배열 항목당 하나의 셀로 진행되며, 매개변수에 정의된 행과 열에서 시작합니다. 가져오는 동안 필요한 행이 여전히 없으면(즉, 대상 테이블이 모든 데이터를 수용하기에는 너무 작음) 필요한 행이 생성됩니다. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | System.Data.DataTable에서 Aspose.Pdf.Table로 데이터를 가져옵니다. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | DataTable 객체를 테이블에 가져옵니다. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | DataTable 객체를 가져오지만 전체 엔터티로 가져오지 않습니다. 지정된 행과 열만 가져옵니다. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | DataView 객체의 데이터를 테이블에 가져옵니다. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | 높이를 설정합니다. |

### 참조

* 클래스 [BaseParagraph](../baseparagraph/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)