---
title: "TableAbsorber.Replace"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TableAbsorber メソッド。ページ上の AbsorbedTable を Table に置き換えます"
type: docs
weight: 60
url: /ja/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace method

ページ上で [`AbsorbedTable`](../../absorbedtable/) を [`Table`](../../../aspose.pdf/table/) に置き換えます。

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | ページ | Pdf ドキュメント ページ オブジェクト。 |
| oldTable | AbsorbedTable | 置き換える対象の [`AbsorbedTable`](../../absorbedtable/) |
| newTable | Table | 古いテーブルを置き換えるための [`Table`](../../../aspose.pdf/table/) |

## 備考

TableList コレクションが変更されることに留意してください。ループ内でテーブルを削除/置換する場合は、TableList コレクションのコピーを使用してください。

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [AbsorbedTable](../../absorbedtable/)
* class [Table](../../../aspose.pdf/table/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


