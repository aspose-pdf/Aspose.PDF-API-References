---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem クラス。エンコーディングサブテーブルを指定します。各エンコーディングサブテーブルは、パラメータ PlatformID、PlatformSpecificId のユニークな組み合わせを持っています。列挙型 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) とプロパティ [`CMapEncodingTable`](./cmapencodingtable/) は、必要なエンコーディングサブテーブルの設定を容易にするために実装されました。
type: docs
weight: 8340
url: /ja/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem クラス

エンコーディングサブテーブルを指定します。各エンコーディングサブテーブルは、パラメータ (PlatformID, PlatformSpecificId) のユニークな組み合わせを持っています。列挙型 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) とプロパティ [`CMapEncodingTable`](./cmapencodingtable/) は、必要なエンコーディングサブテーブルの設定を容易にするために実装されました。

```csharp
public class QueueItem
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | コンストラクタ、デフォルトで mac サブテーブル(1,0) を指定します |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | コンストラクタ |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | コンストラクタ |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 列挙型を介してエンコーディングサブテーブルを指定します |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | エンコーディングサブテーブルのプラットフォーム識別子 |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | エンコーディングサブテーブルのプラットフォーム固有のエンコーディング識別子 |

### 参照

* クラス [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)