---
title: "Table.ImportArray"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Table メソッド。データの一次元配列をテーブルにインポートします。インポートは配列の各項目につき1セルずつ行い、パラメータで指定された行と列から開始します。インポート中に必要な行が不足していることが検出された場合（つまり、対象テーブルがすべてのデータを収めるには小さすぎる）、必要な行が作成されます"
type: docs
weight: 250
url: /ja/net/aspose.pdf/table/importarray/
---
## Table.ImportArray method

データの一次元配列をテーブルにインポートします。インポートは配列の各項目につき 1 つのセルに対応し、パラメータで定義された行と列から開始します。インポート中に、必要な行がまだ存在しないことが検出された場合（つまり、対象テーブルがすべてのデータを収めるには小さすぎる場合）、必要な行が作成されます。

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| importedArray | Object[] | インポートされたデータ、null は空文字列としてインポートされます |
| firstFilledRow | Int32 | インポート開始位置となる対象テーブルの最初の行番号を定義します。対象テーブルの行数が必要な数未満の場合、欠落している行が先に作成されます |
| firstFilledColumn | Int32 | 対象テーブルの最初の対象列番号を指定します。インポート開始前に、その列が対象テーブルに存在している必要があります |
| isLeftColumnsFilled | Boolean | もし 'isLeftColumnsFilled' が false の場合、2 行目以降のすべての埋められた行において、firstFilledColumn の左側にあるセルはスキップされます |

### 関連項目

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


