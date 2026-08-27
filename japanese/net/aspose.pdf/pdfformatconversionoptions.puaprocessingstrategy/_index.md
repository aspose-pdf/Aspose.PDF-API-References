---
title: "列挙体 PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy 列挙体。いくつかの PDF ドキュメントには、Private Use Area (PUA) に属する特殊な Unicode 記号があります。詳細は https//en.wikipedia.org/wiki/Private_Use_Areas を参照してください。これらの記号は、Text が Unicode Private Use Area にマッピングされているが ActualText エントリが存在しないという PDF/A 準拠エラーを引き起こします。この列挙体は PUA 記号を処理するために使用できる戦略を宣言します。"
type: docs
weight: 8530
url: /ja/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

いくつかの PDF ドキュメントには、Private Use Area (PUA) に属する特殊な Unicode 記号があります。詳細は https://en.wikipedia.org/wiki/Private_Use_Areas を参照してください。これらの記号は「Text is mapped to Unicode Private Use Area but no ActualText entry is present」という PDF/A 準拠エラーを引き起こします。この列挙体は PUA 記号を処理するために使用できる戦略を宣言します。

```csharp
public enum PuaProcessingStrategy
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | PUA 記号の処理を無効にします。この戦略はレベル B 準拠の PDF/A ドキュメントでデフォルトで使用されます。 |
| SurroundPuaTextWithEmptyActualText | `1` | 空のテキストを含む ActualText エントリを持つマークドコンテンツブロックを挿入します。この戦略はマークドコンテンツブロックがないドキュメントで良好な結果をもたらします。レベル A 準拠の PDF/A ドキュメントでデフォルトで使用されます。 |
| SubstitutePuaSymbols | `2` | この戦略は 'SurroundPuaTextWithEmptyActualText' より遅く動作しますが、SurroundPuaTextWithEmptyActualText では適切に処理できないドキュメントの PUA 準拠エラーを除去できます。PUA 記号は 'space' 記号または特殊な Unicode に置き換えられます（一部の PUA 記号には Unicode の類似が存在します）。置換はドキュメントのテキストではなく、フォントの内部データである ToUnicode に適用されるため、記号の表示には影響せず、コピー/貼り付け操作のシステムバッファでの記号の表現に影響します。 |

### 関連項目

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


