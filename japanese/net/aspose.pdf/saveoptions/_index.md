---
title: "クラス SaveOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.SaveOptions クラス。SaveOptions タイプは個々の保存オプションに対する抽象化レベルを保持します。"
type: docs
weight: 10020
url: /ja/net/aspose.pdf/saveoptions/
---
## SaveOptions class

SaveOptions 型は個々の保存オプションに対する抽象化レベルを保持します。

```csharp
public abstract class SaveOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


