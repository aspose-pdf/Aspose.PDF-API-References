---
title: Class EmbeddedFileCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EmbeddedFileCollection クラス。埋め込まれたファイルのコレクションを表すクラス
type: docs
weight: 4010
url: /ja/net/aspose.pdf/embeddedfilecollection/
---
## EmbeddedFileCollection クラス

埋め込まれたファイルのコレクションを表すクラス。

```csharp
public class EmbeddedFileCollection : ICollection<FileSpecification>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | コレクション内の埋め込まれたファイルの数を取得します。 |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | このコレクションへのアクセスが同期されているかどうかを示す値を取得します（スレッドセーフ）。 |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | インデックスによって埋め込まれたファイルを取得します。（2つのインデクサ） |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | ファイル添付キーのリストを返します。 |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | このコレクションへのアクセスを同期するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add)(FileSpecification) | 埋め込まれたファイル仕様をコレクションに追加します。 |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add_1)(string, FileSpecification) | 指定されたキーで埋め込まれたファイルにファイルを追加します。 |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | FileSpecification オブジェクトの配列をコレクションにコピーします。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete)() | ドキュメントからすべての埋め込まれたファイルを削除します。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete_1)(string) | 名前によって埋め込まれたファイルを削除します。 |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | コレクション内のキーによってファイルを削除します。 |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | 名前によって埋め込まれたファイルを返します。 |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | コレクションの列挙子を返します。 |

### 参照

* クラス [FileSpecification](../filespecification/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)