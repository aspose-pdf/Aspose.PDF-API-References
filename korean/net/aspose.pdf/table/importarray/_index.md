---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: 테이블 메서드. 일차원 데이터 배열을 테이블로 가져옵니다. 가져오기는 각 배열 항목당 하나의 셀로 진행되며, 매개변수에 정의된 행과 열에서 시작합니다. 가져오는 동안 필요한 행이 여전히 없으면（즉, 대상 테이블이 모든 데이터를 수용하기에는 너무 작으면） 필요한 행이 생성됩니다.
type: docs
weight: 250
url: /ko/net/aspose.pdf/table/importarray/
---
## Table.ImportArray 메서드

일차원 데이터 배열을 테이블로 가져옵니다. 가져오기는 각 배열 항목당 하나의 셀로 진행되며, 매개변수에 정의된 행과 열에서 시작합니다. 가져오는 동안 필요한 행이 여전히 없으면(즉, 대상 테이블이 모든 데이터를 수용하기에는 너무 작으면) 필요한 행이 생성됩니다.

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| importedArray | Object[] | 가져온 데이터, null은 빈 문자열로 가져옵니다. |
| firstFilledRow | Int32 | 가져오기가 시작될 대상 테이블의 첫 번째 대상 행 번호를 정의합니다. 대상 테이블의 행 수가 필요 수보다 적으면, 누락된 행이 먼저 생성됩니다. |
| firstFilledColumn | Int32 | 대상 테이블의 첫 번째 대상 열 번호를 지정합니다. 가져오기 시작 전에 열이 대상 테이블에 존재해야 합니다. |
| isLeftColumnsFilled | Boolean | 'isLeftColumnsFilled'=false인 경우, 두 번째 및 모든 후속 채워진 행에서 firstFilledColumn의 왼쪽에 있는 셀은 건너뜁니다. |

### 참조

* 클래스 [Table](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)