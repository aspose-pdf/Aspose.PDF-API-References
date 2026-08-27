---
title: "Table.ImportDataView"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Table 메서드. DataView 객체의 데이터를 테이블에 가져옵니다."
type: docs
weight: 270
url: /ko/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

DataView 객체의 데이터를 표에 가져옵니다.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceDataView | DataView | 가져올 DataView 객체입니다. |
| isColumnNamesImported | Boolean | 열 이름을 첫 번째 행으로 가져올지 여부를 나타냅니다. |
| firstFilledRow | Int32 | 가져오기가 시작될 대상 테이블의 첫 번째 셀의 0부터 시작하는 행 번호입니다. 대상 테이블에 해당 행이 없으면 (필요한 경우 이전 행도) 생성됩니다. |
| firstFilledColumn | Int32 | 가져오기가 시작될 대상 테이블의 첫 번째 셀에 대한 0 기반 열 번호입니다. 가져오기가 시작되기 전에 대상 테이블에 해당 열이 존재해야 하며, 그렇지 않으면 예외가 발생합니다. |
| maxRows | Int32 | 소스 DataView에서 가져올 최대 행 수입니다. |
| maxColumns | Int32 | 소스 DataView에서 가져올 최대 열 수입니다. |

### 또 보기

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


