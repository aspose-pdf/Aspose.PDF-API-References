---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy 列挙型。一部の PDF ドキュメントには、プライベート ユース エリア （PUA） に属する特別な Unicode シンボルがあります。詳細については、https//en.wikipedia.org/wiki/Private_Use_Areas を参照してください。これらのシンボルは、「テキストが Unicode プライベート ユース エリアにマッピングされていますが、ActualText エントリが存在しません」といった PDF/A 準拠のエラーを引き起こします。この列挙型は、PUA シンボルを処理するために使用できる戦略を宣言します。
type: docs
weight: 8390
url: /ja/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy 列挙型

一部の PDF ドキュメントには、プライベート ユース エリア (PUA) に属する特別な Unicode シンボルがあります。詳細については、https://en.wikipedia.org/wiki/Private_Use_Areas を参照してください。これらのシンボルは、「テキストが Unicode プライベート ユース エリアにマッピングされていますが、ActualText エントリが存在しません」といった PDF/A 準拠のエラーを引き起こします。この列挙型は、PUA シンボルを処理するために使用できる戦略を宣言します。

```csharp
public enum PuaProcessingStrategy
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | PUA シンボル処理を無効にします。この戦略は、レベル B 準拠の PDF/A ドキュメントに対してデフォルトで使用されます。 |
| SurroundPuaTextWithEmptyActualText | `1` | 空のテキストを含む ActualText エントリを持つマークされたコンテンツブロックを挿入します。この戦略は、マークされたコンテンツブロックがないドキュメントに対して良好な結果をもたらします。レベル A 準拠の PDF/A ドキュメントに対してデフォルトで使用されます。 |
| SubstitutePuaSymbols | `2` | この戦略は「SurroundPuaTextWithEmptyActualText」よりも遅く動作しますが、SurroundPuaTextWithEmptyActualText では適切に処理できないドキュメントの PUA 準拠のエラーを削除できます。PUA シンボルは、シンボル「スペース」または特別な Unicode に置き換えられます（いくつかの PUA シンボルには Unicode の類似物があります）。置き換えはドキュメントのテキストではなく、フォントの内部データ ToUnicode に適用されるため、シンボルの視覚には影響しませんが、コピー/ペースト操作のシステムバッファ内でのシンボルの表示には影響します。 |

### 参照

* クラス [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)