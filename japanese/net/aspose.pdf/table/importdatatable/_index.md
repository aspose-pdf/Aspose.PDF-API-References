---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Table メソッド。System.Data.DataTable から Aspose.Pdf.Table にデータをインポートします。
type: docs
weight: 260
url: /ja/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

System.Data.DataTable から Aspose.Pdf.Table にデータをインポートします。

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| importedDataTable | DataTable | System.Data.DataTable のソースインスタンス |
| isColumnNamesImported | Boolean | 列名が最初の行としてインポートされるかどうかを指定します |
| firstFilledRow | Int32 | インポートが開始されるターゲットテーブルの最初の行のゼロベースの番号を指定します。指定された番号の行（およびいくつかの前の行）がターゲットテーブルに存在しない場合、それらは最初に作成されます |
| firstFilledColumn | Int32 | ターゲットテーブルの最初のターゲット列の番号を指定します。インポート開始前に列はターゲットテーブルに存在している必要があります |

### 参照

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

DataTable オブジェクトをテーブルにインポートします。

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| importedDataTable | DataTable | インポートされる DataTable オブジェクト。 |
| isColumnNamesShown | Boolean | ソースデータテーブルの列名が最初の行としてインポートされるかどうかを指定します。 |
| firstFilledRow | Int32 | インポートが開始されるターゲットテーブルの最初の行のゼロベースの番号を指定します。指定された番号の行（およびいくつかの前の行）がターゲットテーブルに存在しない場合、それらは最初に作成されます |
| firstFilledColumn | Byte | ターゲットテーブルの最初のターゲット列の番号を指定します。インポート開始前に列はターゲットテーブルに存在している必要があります |
| maxRows | Int32 | ソーステーブルからインポートされる最大行数。 |
| maxColumns | Int32 | ソーステーブルからインポートされる最大列数。 |
| isHtmlSupported | Boolean | テキストが HTML 文字列であるかどうかを指定します。 |

### 参照

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

DataTable オブジェクトをインポートしますが、全体としてではなく、指定された行と列のみがインポートされます。

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| importedDataTable | DataTable | インポートされる DataTable オブジェクト。 |
| sourceRowList | Int32[] | インポートされる必要があるソース DataTable オブジェクトの行番号の配列。リストは null であってはならず、既存の行の番号のみを含む必要があります。そうでない場合は例外がスローされます。 |
| sourceColumnList | Int32[] | インポートされる必要があるソース DataTable オブジェクトの列番号の配列。リストは null であってはならず、既存の列の番号のみを含む必要があります。そうでない場合は例外がスローされます。 |
| firstFilledRow | Int32 | インポートが開始されるターゲットテーブルの最初のセルのゼロベースの行番号。ターゲットテーブルにその行が含まれていない場合、それ（および必要に応じてすべての前の行）が作成されます |
| firstFilledColumn | Int32 | インポートが開始されるターゲットテーブルの最初のセルのゼロベースの列番号。インポート開始前にターゲットテーブルにその列が含まれている必要があります。そうでない場合は例外がスローされます。 |
| showColumnNamesAsFirstRow | Boolean | ソースデータテーブルの列名が最初の行としてインポートされるかどうかを指定します。 |
| isHtmlSupported | Boolean | テキストが HTML 文字列であるかどうかを指定します。 |

### 参照

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)