---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: テーブルメソッド。DataViewオブジェクトのデータをテーブルにインポートします
type: docs
weight: 270
url: /ja/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView メソッド

DataViewオブジェクトのデータをテーブルにインポートします。

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceDataView | DataView | インポートされるDataViewオブジェクト。 |
| isColumnNamesImported | Boolean | 列名が最初の行としてインポートされるかどうかを示します。 |
| firstFilledRow | Int32 | インポートが開始されるターゲットテーブルの最初のセルのゼロベースの行番号。ターゲットテーブルにその行が含まれていない場合は、その行（必要に応じてすべての前の行も）が作成されます。 |
| firstFilledColumn | Int32 | インポートが開始されるターゲットテーブルの最初のセルのゼロベースの列番号。インポートが開始される前にターゲットテーブルにその列が含まれている必要があります。そうでない場合は例外がスローされます。 |
| maxRows | Int32 | ソースDataViewからインポートされる最大行数。 |
| maxColumns | Int32 | ソースDataViewからインポートされる最大列数。 |

### 参照

* クラス [Table](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)