---
title: "Table.ImportDataTable"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Table メソッド。System.Data.DataTable から Aspose.Pdf.Table へデータをインポートします"
type: docs
weight: 260
url: /ja/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

System.Data.DataTable からデータを Aspose.Pdf.Table にインポートします

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| importedDataTable | DataTable | System.Data.DataTable のソースインスタンス |
| isColumnNamesImported | Boolean | 列名を最初の行としてインポートするかどうかを指定します |
| firstFilledRow | Int32 | インポート開始対象テーブルの最初の行のゼロベース番号を指定します。その番号の行（およびいくつかの前の行）が対象テーブルに存在しない場合、最初に作成されます |
| firstFilledColumn | Int32 | 対象テーブルの最初の対象列番号を指定します。インポート開始前に、その列が対象テーブルに存在している必要があります |

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| importedDataTable | DataTable | インポート対象の DataTable オブジェクトです。 |
| isColumnNamesShown | Boolean | ソースデータテーブルの列名を最初の行としてインポートするかどうかを指定します |
| firstFilledRow | Int32 | インポート開始対象テーブルの最初の行のゼロベース番号を指定します。その番号の行（およびいくつかの前の行）が対象テーブルに存在しない場合、最初に作成されます |
| firstFilledColumn | Byte | 対象テーブルの最初の対象列番号を指定します。インポート開始前に、その列が対象テーブルに存在している必要があります |
| maxRows | Int32 | ソーステーブルからインポートする最大行数 |
| maxColumns | Int32 | ソーステーブルからインポートされる列の最大数。 |
| isHtmlSupported | Boolean | テキストが HTML 文字列かどうかを指定します。 |

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| importedDataTable | DataTable | インポート対象の DataTable オブジェクトです。 |
| sourceRowList | Int32[] | インポートする必要があるソース DataTable オブジェクトの行番号の配列です。リストは null であってはならず、既存の行番号のみを含む必要があります。そうでない場合は例外がスローされます。 |
| sourceColumnList | Int32[] | インポートする必要があるソース DataTable オブジェクトの列番号の配列です。リストは null であってはならず、既存の列番号のみを含む必要があります。そうでない場合は例外がスローされます。 |
| firstFilledRow | Int32 | インポートが開始される対象テーブルの最初のセルのゼロベース行番号です。対象テーブルにその行が存在しない場合、その行（必要に応じてそれ以前の行）も作成されます。 |
| firstFilledColumn | Int32 | インポートが開始される対象テーブルの最初のセルのゼロベース列番号です。対象テーブルがインポート開始前にその列を含んでいなければ、例外がスローされます。 |
| showColumnNamesAsFirstRow | Boolean | ソースデータテーブルの列名を最初の行としてインポートするかどうかを指定します。 |
| isHtmlSupported | Boolean | テキストが HTML 文字列かどうかを指定します。 |

### 関連項目

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


