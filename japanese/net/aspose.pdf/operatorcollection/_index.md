---
title: "OperatorCollection クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.OperatorCollection クラス。クラスはオペレーターのコレクションを表します。"
type: docs
weight: 7220
url: /ja/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

クラスは演算子のコレクションを表します。

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | コレクション内のオペレーター数を取得します。 |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | コレクションが高速テキスト抽出に限定されているかどうかを示します。 |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | インデックスでオペレーターを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | IOperatorSelector ビジターオブジェクトを受け入れ、オペレーターを処理します。 |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | 他のコレクションからすべてのオペレーターをコレクションに追加します。 |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | 新しいオペレーターをコレクションに追加します。 |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | コンテンツオペレーターの末尾にオペレーターを追加します。 |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | 最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさないようにする必要がある場合に呼び出すことができます。 |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | リストからすべてのオペレーターを削除します。 |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | コレクションが指定されたオペレーターを含む場合は true を返します。 |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | オペレーターをオペレーターリストにコピーします。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | コレクションからオペレーターを削除します。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | コレクションからオペレーターを削除します。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | コレクションからオペレーターを削除します。 |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | コレクションの列挙子を返します。 |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | 指定された位置に演算子を挿入します。 |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | 演算子をコレクションに挿入します。 |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | 指定された位置に演算子を挿入します。 |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | コレクションから演算子を削除します。 |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | コレクション内の演算子を他の演算子に置き換えます。 |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。 |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。invalidate パラメータが true の場合、すべての演算子を "changed" とマークします。 |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | コンテンツデータの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツストリームは更新されません。 |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | 演算子のテキスト表現を返します。 |

### 関連項目

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


