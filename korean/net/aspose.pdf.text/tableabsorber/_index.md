---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TableAbsorber 클래스. 테이블 요소의 흡수기 객체를 나타냅니다. 검색을 수행하고 [`TableList`](./tablelist/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.
type: docs
weight: 10790
url: /ko/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber 클래스

테이블 요소의 흡수기 객체를 나타냅니다. 검색을 수행하고 [`TableList`](./tablelist/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

```csharp
public class TableAbsorber
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | `TableAbsorber`의 새 인스턴스를 초기화합니다. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | 텍스트 검색 옵션으로 `TableAbsorber`의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | 발견된 테이블을 포함하는 읽기 전용 IList를 반환합니다. |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | 텍스트 검색 옵션을 가져오거나 설정합니다. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * 여러 시나리오에서 우수한 대체 테이블 인식 엔진을 활성화하며, 테두리 없이 테이블을 인식할 수 있습니다. 테이블 편집 및 텍스트 스타일 가져오기는 아직 지원하지 않습니다. 기본값은 false입니다; |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | 페이지에서 [`AbsorbedTable`](../absorbedtable/)를 제거합니다. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | 페이지에서 [`AbsorbedTable`](../absorbedtable/)를 [`Table`](../../aspose.pdf/table/)로 교체합니다. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | 지정된 문서에서 테이블을 추출합니다. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | 지정된 페이지에서 테이블을 추출합니다. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 테이블을 찾고 테이블 셀의 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)