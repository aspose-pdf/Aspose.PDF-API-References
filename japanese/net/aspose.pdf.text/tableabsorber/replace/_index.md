---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber メソッド。ページ上の AbsorbedTable を Table に置き換えます。
type: docs
weight: 60
url: /ja/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace メソッド

[`AbsorbedTable`](../../absorbedtable/) をページ上の [`Table`](../../../aspose.pdf/table/) に置き換えます。

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Page | Pdf ドキュメントページオブジェクト。 |
| oldTable | AbsorbedTable | 置き換えられる [`AbsorbedTable`](../../absorbedtable/) 。 |
| newTable | Table | 古いテーブルを置き換える [`Table`](../../../aspose.pdf/table/) 。 |

## 備考

TableList コレクションが変更されることに注意してください。ループ内でテーブルを削除/置き換える場合は、TableList コレクションのコピーを使用してください。

### 参照

* クラス [Page](../../../aspose.pdf/page/)
* クラス [AbsorbedTable](../../absorbedtable/)
* クラス [Table](../../../aspose.pdf/table/)
* クラス [TableAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)