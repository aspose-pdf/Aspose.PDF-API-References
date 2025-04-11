---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Table 메서드. System.Data.DataTable에서 Aspose.Pdf.Table로 데이터를 가져옵니다.
type: docs
weight: 260
url: /ko/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

System.Data.DataTable에서 Aspose.Pdf.Table로 데이터를 가져옵니다.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| importedDataTable | DataTable | System.Data.DataTable의 소스 인스턴스 |
| isColumnNamesImported | Boolean | 열 이름이 첫 번째 행으로 가져올지 여부를 지정합니다. |
| firstFilledRow | Int32 | 가져오기를 시작할 대상 테이블의 첫 번째 행의 0 기반 번호를 지정합니다. 해당 번호(및 일부 이전 행)가 대상 테이블에 없으면 먼저 생성됩니다. |
| firstFilledColumn | Int32 | 대상 테이블의 첫 번째 대상 열 번호를 지정합니다. 가져오기를 시작하기 전에 열이 대상 테이블에 존재해야 합니다. |

### 참조

* 클래스 [Table](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

DataTable 객체를 테이블에 가져옵니다.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| importedDataTable | DataTable | 가져올 DataTable 객체입니다. |
| isColumnNamesShown | Boolean | 소스 데이터 테이블의 열 이름이 첫 번째 행으로 가져올지 여부를 지정합니다. |
| firstFilledRow | Int32 | 가져오기를 시작할 대상 테이블의 첫 번째 행의 0 기반 번호를 지정합니다. 해당 번호(및 일부 이전 행)가 대상 테이블에 없으면 먼저 생성됩니다. |
| firstFilledColumn | Byte | 대상 테이블의 첫 번째 대상 열 번호를 지정합니다. 가져오기를 시작하기 전에 열이 대상 테이블에 존재해야 합니다. |
| maxRows | Int32 | 소스 테이블에서 가져올 최대 행 수입니다. |
| maxColumns | Int32 | 소스 테이블에서 가져올 최대 열 수입니다. |
| isHtmlSupported | Boolean | 텍스트가 HTML 문자열인지 여부를 지정합니다. |

### 참조

* 클래스 [Table](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

DataTable 객체를 가져오지만 전체 엔터티로 가져오지는 않습니다. 지정된 행과 열만 가져옵니다.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| importedDataTable | DataTable | 가져올 DataTable 객체입니다. |
| sourceRowList | Int32[] | 가져와야 하는 소스 DataTable 객체의 행 번호 배열입니다. 목록은 null이 아니어야 하며 기존 행 번호만 포함해야 하며, 그렇지 않으면 예외가 발생합니다. |
| sourceColumnList | Int32[] | 가져와야 하는 소스 DataTable 객체의 열 번호 배열입니다. 목록은 null이 아니어야 하며 기존 열 번호만 포함해야 하며, 그렇지 않으면 예외가 발생합니다. |
| firstFilledRow | Int32 | 가져오기를 시작할 대상 테이블의 첫 번째 셀의 0 기반 행 번호입니다. 대상 테이블에 해당 행이 없으면 (필요한 경우 모든 이전 행도) 생성됩니다. |
| firstFilledColumn | Int32 | 가져오기를 시작할 대상 테이블의 첫 번째 셀의 0 기반 열 번호입니다. 가져오기를 시작하기 전에 대상 테이블에 해당 열이 존재해야 하며, 그렇지 않으면 예외가 발생합니다. |
| showColumnNamesAsFirstRow | Boolean | 소스 데이터 테이블의 열 이름이 첫 번째 행으로 가져올지 여부를 지정합니다. |
| isHtmlSupported | Boolean | 텍스트가 HTML 문자열인지 여부를 지정합니다. |

### 참조

* 클래스 [Table](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)