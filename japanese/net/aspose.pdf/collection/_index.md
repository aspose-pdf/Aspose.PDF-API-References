---
title: "クラス Collection"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Collection クラスです。Collection12.3.5 コレクションを表すクラスです。"
type: docs
weight: 3130
url: /ja/net/aspose.pdf/collection/
---
## Collection class

Collection (12.3.5 Collections) 用のクラスを表します。

```csharp
public class Collection : EmbeddedFileCollection
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Collection](collection/)() | 新しい Collection オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | コレクション内の埋め込みファイル数を取得します。 |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | デフォルトの埋め込みファイル名です。 |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | このコレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | インデックスで埋め込みファイルを取得します。（2 つのインデクサー） |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | ファイル添付キーのリストを返します。 |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | ドキュメントコレクションの「Schema」を取得します。 |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | このコレクションへのアクセスを同期化するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | コレクションに埋め込みファイル仕様を追加します。 |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | 指定されたキーで埋め込みファイルにファイルを追加します。 |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | FileSpecification オブジェクトの配列を colleciton にコピーします。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Document からすべての埋め込みファイルを削除します。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | 名前で埋め込みファイルを削除します。 |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | コレクション内のキーでファイルを削除します。 |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | 名前で埋め込みファイルを返します。 |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | colleciton 列挙子を返します。 |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | 仕様に従ってソートされたファイルのコレクションを取得します。 |

### 関連項目

* class [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


