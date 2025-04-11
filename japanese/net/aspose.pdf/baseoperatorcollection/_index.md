---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseOperatorCollection クラス。オペレーターコレクションのベースクラスを表します
type: docs
weight: 2830
url: /ja/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection クラス

オペレーターコレクションのベースクラスを表します。

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | コレクション内のオペレーターの数を取得します。 |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | コレクションが高速テキスト抽出に制限されているかどうかを示します。 |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | コレクションが読み取り専用の場合は true を返します。 |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | インデックスによってオペレーターを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | 新しいオペレーターをコレクションに追加します。 |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | 最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさない場合に呼び出されることがあります。 |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | コレクションをクリアします。 |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | コレクションにオペレーターが存在するかどうかを確認します。 |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | オペレーターをオペレーターリストにコピーします。 |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | コレクションの列挙子を返します。 |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | コレクションにオペレーターを挿入します。 |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | コレクションからオペレーターを削除します。 |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | ドキュメントの更新を再開します。保留中の変更がある場合は、コンテンツストリームを更新します。 |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | コンテンツデータの更新を抑制します。ResumeUpdate が呼び出されるまで、コンテンツストリームは更新されません。 |

### 参照

* クラス [Operator](../operator/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)