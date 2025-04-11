---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Table method. 테이블에 DataView 객체의 데이터를 가져옵니다.
type: docs
weight: 270
url: /ko/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView 메서드

DataView 객체의 데이터를 테이블에 가져옵니다.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceDataView | DataView | 가져올 DataView 객체입니다. |
| isColumnNamesImported | Boolean | 열 이름이 첫 번째 행으로 가져올지 여부를 나타냅니다. |
| firstFilledRow | Int32 | 가져오기를 시작할 대상 테이블의 첫 번째 셀의 0 기반 행 번호입니다. 대상 테이블에 해당 행이 없으면 필요에 따라 해당 행(및 이전 모든 행)이 생성됩니다. |
| firstFilledColumn | Int32 | 가져오기를 시작할 대상 테이블의 첫 번째 셀의 0 기반 열 번호입니다. 가져오기가 시작되기 전에 대상 테이블에 해당 열이 포함되어 있어야 하며, 그렇지 않으면 예외가 발생합니다. |
| maxRows | Int32 | source dataview에서 가져올 최대 행 수입니다. |
| maxColumns | Int32 | source dataview에서 가져올 최대 열 수입니다. |

### 참조

* 클래스 [Table](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)