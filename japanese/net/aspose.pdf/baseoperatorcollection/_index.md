---
title: "クラス BaseOperatorCollection"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.BaseOperatorCollection クラス。オペレーターコレクションの基底クラスを表します"
type: docs
weight: 2940
url: /ja/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

オペレーター コレクションの基底クラスを表します。

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | コレクション内のオペレーター数を取得します。 |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | コレクションが高速テキスト抽出に限定されているかどうかを示します。 |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | コレクションが読み取り専用の場合は true を返します。 |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | インデックスでオペレーターを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | 新しいオペレーターをコレクションに追加します。 |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | 最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさないようにする必要がある場合に呼び出すことができます。 |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | コレクションをクリアします。 |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | コレクションにオペレーターが存在するか確認します。 |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | オペレーターをオペレーターリストにコピーします。 |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | コレクションの列挙子を返します。 |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | 演算子をコレクションに挿入します。 |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | コレクションからオペレーターを削除します。 |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。 |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | コンテンツデータの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツストリームは更新されません。 |

### 関連項目

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


