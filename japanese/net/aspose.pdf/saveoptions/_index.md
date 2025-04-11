---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptions クラス。SaveOptions タイプは個々の保存オプションの抽象レベルを保持します
type: docs
weight: 9870
url: /ja/net/aspose.pdf/saveoptions/
---
## SaveOptions クラス

SaveOptions タイプは個々の保存オプションの抽象レベルを保持します

```csharp
public abstract class SaveOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントのグリフが aps ページを準備する際にキャッシュされるかどうかを示すブール値を取得または設定します。PDFを他の形式に変換する際のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データの保存形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションであり、保存操作は続行されますが、ユーザーは Abort を返すこともでき、その場合は保存操作を中止する必要があります。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)