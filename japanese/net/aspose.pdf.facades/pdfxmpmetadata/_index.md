---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfXmpMetadata クラス。XMP メタデータを操作するためのクラス
type: docs
weight: 4640
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata クラス

XMP メタデータを操作するためのクラス。

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | PdfXmpMetadata のコンストラクタ。 |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | *document* に基づいて新しい `PdfXmpMetadata` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | コレクション内のアイテムの数を取得します。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | 拡張フィールドの辞書を取得します。 |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | コレクションが固定サイズである場合は true を返します。 |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | コレクションが読み取り専用である場合は true を返します。 |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | コレクションが同期されている場合は true を返します。 |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | キーによって値を取得または設定します。 (2 つのインデクサ) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | 辞書からキーを取得します。 |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | コレクションの同期オブジェクトを取得します。 |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | 辞書内の値のコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | 辞書にキーと値のペアを追加します。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | XMP メタデータに値を追加します。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | 辞書オブジェクトに新しい要素を追加します。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | 辞書オブジェクトに新しい要素を追加します。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | メタデータに拡張フィールドを追加します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | オブジェクトからすべての要素を削除します。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | 辞書に指定されたプロパティが含まれているかを確認します。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | 指定されたキーと値のペアが辞書に含まれているかを確認します。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | 辞書に指定されたキーが含まれているかを確認します。 |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | この辞書に指定されたキーが含まれているかを判断します。 |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | 辞書の列挙子オブジェクトを取得します。 |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | プレフィックスによって名前空間 URI を取得します。 |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | 名前空間 URI によってプレフィックスを取得します。 |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | 入力 PDF の XmpMetadata を XML 形式で取得します。 |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | メタ名に従って入力 PDF の XmpMetadata の一部を取得します。 |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | 名前空間 URI を登録します。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | 指定されたキーの要素を削除します。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | コレクションからキー/値のペアを削除します。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | 辞書からキーを削除します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF ドキュメントを指定されたファイルに保存します。 |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | 辞書内のキーを探し、見つかった場合は値を取得します。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* クラス [XmpValue](../../aspose.pdf/xmpvalue/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)