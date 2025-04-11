---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Collection クラス。Collection12.3.5 コレクションのクラスを表します。
type: docs
weight: 3020
url: /ja/net/aspose.pdf/collection/
---
## コレクションクラス

Collection(12.3.5 コレクション)のクラスを表します。

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
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | コレクション内の埋め込みファイルの数を取得します。 |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | デフォルトの埋め込みファイル名。 |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | このコレクションへのアクセスが同期されているかどうかを示す値を取得します（スレッドセーフ）。 |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | インデックスによって埋め込みファイルを取得します。（2 つのインデクサ） |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | ファイル添付キーのリストを返します。 |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | ドキュメントコレクションの「スキーマ」を取得します。 |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | このコレクションへのアクセスを同期するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | 埋め込みファイル仕様をコレクションに追加します。 |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | 指定されたキーで埋め込みファイルにファイルを追加します。 |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | FileSpecification オブジェクトの配列をコレクションにコピーします。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | ドキュメントからすべての埋め込みファイルを削除します。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | 名前で埋め込みファイルを削除します。 |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | コレクション内のキーによってファイルを削除します。 |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | 名前によって埋め込みファイルを返します。 |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | コレクションの列挙子を返します。 |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | 仕様に従ってソートされたファイルのコレクションを取得します。 |

### 参照

* クラス [EmbeddedFileCollection](../embeddedfilecollection/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)