---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: テーブルメソッド。一次元配列のデータをテーブルにインポートします。インポートは各配列のアイテムごとに1つのセルを使用し、パラメータで定義された行と列から開始します。インポート中に必要な行がまだ存在しないことが検出された場合（つまり、ターゲットテーブルがすべてのデータを吸収するには小さすぎる場合）、必要な行が作成されます。
type: docs
weight: 250
url: /ja/net/aspose.pdf/table/importarray/
---
## Table.ImportArray メソッド

一次元配列のデータをテーブルにインポートします。インポートは各配列のアイテムごとに1つのセルを使用し、パラメータで定義された行と列から開始します。インポート中に必要な行がまだ存在しないことが検出された場合（つまり、ターゲットテーブルがすべてのデータを吸収するには小さすぎる場合）、必要な行が作成されます。

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| importedArray | Object[] | インポートされたデータ、nullは空の文字列としてインポートされます |
| firstFilledRow | Int32 | インポートが開始されるターゲットテーブルの最初のターゲット行の番号を定義します。ターゲットテーブルの行数が必要な行数より少ない場合、最初に不足している行が作成されます。 |
| firstFilledColumn | Int32 | ターゲットテーブルの最初のターゲット列の番号を指定します。インポート開始前に列はターゲットテーブルに存在している必要があります。 |
| isLeftColumnsFilled | Boolean | 'isLeftColumnsFilled' = false の場合、2番目以降のすべての充填された行のセルは、firstFilledColumn の左側にあるものはスキップされます。 |

### 参照

* クラス [Table](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)