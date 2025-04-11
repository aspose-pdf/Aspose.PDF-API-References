---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FileSpecification クラス。埋め込まれたファイルを表すクラス
type: docs
weight: 4850
url: /ja/net/aspose.pdf/filespecification/
---
## FileSpecification クラス

埋め込まれたファイルを表すクラス。

```csharp
public sealed class FileSpecification : IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](filespecification/#constructor_3)(string) | FileSpecification のコンストラクタ |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | ファイル仕様のコンストラクタ。 |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | FileSpecification のコンストラクタ。 |
| [FileSpecification](filespecification/#constructor_5)(string, string) | FileSpecification のコンストラクタ。 |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | FileSpecification のコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | 関連ファイルの関係。 |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | ファイル仕様のコレクションアイテムを取得します。 |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | コンテンツファイルを取得または設定します。このプロパティはメモリに読み込まれたデータを返し、大きなデータの場合はメモリ不足の例外を引き起こす可能性があります。メモリ使用量を減らすには、StreamContents を使用してください。 |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | ファイル仕様に関連付けられたテキストを取得または設定します。 |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | エンコーディング形式を取得または設定します。可能な値: Zip - ファイルは ZIP で圧縮されています、None - ファイルは圧縮されていません。 |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | 暗号化されたペイロードを取得します。 |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | ファイルシステムの名前を取得または設定します。 |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | true の場合、ファイルの内容がファイル仕様に含まれます。 |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | 埋め込まれたファイルのサブタイプを取得します。 |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | ファイル仕様の名前を取得または設定します。 |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | ファイルパラメータを取得します。 |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | ファイルの内容をストリームとして取得します。内容はメモリに読み込まれず、メモリ使用量を減らすことができます。ただし、このストリームは位置指定と Length プロパティをサポートしていません。これらの機能が必要な場合は、代わりに Contents プロパティを使用してください。 |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | ファイル仕様の Unicode 名を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | 内容を破棄します。 |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | アプリケーション固有のパラメータを取得します。 |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | アプリケーション固有のパラメータを設定します。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)