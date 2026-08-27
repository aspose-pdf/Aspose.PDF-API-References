---
title: "클래스 TableAbsorber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TableAbsorber 클래스. 테이블 요소의 흡수 객체를 나타냅니다. 검색을 수행하고 TableList 컬렉션을 통해 검색 결과에 접근할 수 있습니다"
type: docs
weight: 10970
url: /ko/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

테이블 요소의 흡수 객체를 나타냅니다. 검색을 수행하고 [`TableList`](./tablelist/) 컬렉션을 통해 검색 결과에 접근합니다.

```csharp
public class TableAbsorber
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | `TableAbsorber`의 새 인스턴스를 초기화합니다. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | 텍스트 검색 옵션과 함께 `TableAbsorber`의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | 찾은 테이블을 포함하는 읽기 전용 IList를 반환합니다 |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | 텍스트 검색 옵션을 가져오거나 설정합니다. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * 다양한 시나리오에서 우수하고 테두리 없는 테이블을 인식할 수 있는 대체 테이블 인식 엔진을 활성화합니다. 아직 테이블 편집 및 텍스트 스타일 가져오기를 지원하지 않습니다. 기본값은 false입니다; |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Page에서 [`AbsorbedTable`](../absorbedtable/)을 제거합니다. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Page에서 [`AbsorbedTable`](../absorbedtable/)을 [`Table`](../../aspose.pdf/table/)으로 교체합니다. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | 지정된 Document에서 테이블을 추출합니다. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | 지정된 Page에서 테이블을 추출합니다. |

## 예제

이 예제는 첫 번째 PDF Document Page에서 테이블을 찾고 테이블 셀의 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 테이블을 찾기 위해 TableAbsorber 객체를 생성합니다
TableAbsorber absorber = new TableAbsorber();

// 흡수기를 사용하여 첫 번째 Page를 방문합니다
absorber.Visit(pdfDocument.Pages[1]);

// Page에서 첫 번째 테이블, 해당 첫 번째 셀 및 그 안의 텍스트 조각에 접근합니다
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// 셀 안의 첫 번째 텍스트 조각의 텍스트를 변경합니다
fragment.Text = "hi world";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


