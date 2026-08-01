---
title: "Table.ImportDataView"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Table メソッド。DataView オブジェクトのデータをテーブルにインポートします"
type: docs
weight: 270
url: /ja/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

DataView オブジェクトのデータをテーブルにインポートします。

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| sourceDataView | DataView | インポートされる DataView オブジェクトです。 |
| isColumnNamesImported | Boolean | 列名を最初の行としてインポートするかどうかを示します。 |
| firstFilledRow | Int32 | インポートが開始される対象テーブルの最初のセルのゼロベース行番号です。対象テーブルにその行が存在しない場合、その行（必要に応じてそれ以前の行）も作成されます。 |
| firstFilledColumn | Int32 | インポートが開始される対象テーブルの最初のセルのゼロベース列番号です。インポート開始前に対象テーブルがその列を含んでいる必要があり、含まれていない場合は例外がスローされます。 |
| maxRows | Int32 | ソース DataView からインポートされる最大行数です。 |
| maxColumns | Int32 | ソース DataView からインポートされる最大列数です。 |

### 関連項目

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


