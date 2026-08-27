---
title: "クラス Metadata"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Metadata クラス。XMP メタデータストリームへのアクセスを提供します。"
type: docs
weight: 7090
url: /ja/net/aspose.pdf/metadata/
---
## Metadata class

XMP メタデータストリームへのアクセスを提供します。

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | コレクション内の要素数を取得します。 |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | 拡張フィールドの辞書を取得します。 |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | コレクションが固定サイズかどうかを確認します。 |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | コレクションが読み取り専用かどうかを確認します。 |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | コレクションが同期化されているかどうかを確認します。 |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | メタデータからのデータを取得または設定します。 |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | メタデータキーのコレクションを取得します。 |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | 名前空間マネージャーを取得します。 |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | コレクションの同期オブジェクトを取得します。 |
| [Values](../../aspose.pdf/metadata/values/) { get; } | メタデータ内の値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | 辞書にキーと値のペアを追加します。 |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | メタデータに値を追加します。 |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | メタデータに pdf 拡張子を追加します。 |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | メタデータに値を追加します。 |
| [Clear](../../aspose.pdf/metadata/clear/)() | メタデータをクリアします。 |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | 指定されたキーと値のペアが辞書に含まれているか確認します。 |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | キーがメタデータに含まれているかどうかを確認します。 |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | この辞書が指定されたキーを含んでいるか判断します。 |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | 辞書の列挙子を返します。 |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | プレフィックスから名前空間 URI を返します。 |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | 名前空間 URI からプレフィックスを返します。 |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | 名前空間 URI を登録します。 |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | 名前空間 URI を登録します。 |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | コレクションからキー/値のペアを削除します。 |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | メタデータからエントリを削除します。 |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |

### 関連項目

* class [XmpValue](../xmpvalue/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


