---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "一部の PDF ドキュメントには、プライベート使用領域 (PUA) に属する特殊な Unicode 記号が含まれています。詳細は https://en.wikipedia.org/wiki/Private_Use_Areas を参照してください。これらの記号。"
type: docs
weight: 3750
url: /ja/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

一部の PDF ドキュメントには、プライベートユース領域 (PUA) に属する特殊な Unicode シンボルが含まれます。詳細は https://en.wikipedia.org/wiki/Private_Use_Areas を参照してください。これらのシンボルは "Text is mapped to Unicode Private Use Area but no ActualText entry is present" という PDF/A 準拠エラーを引き起こします。この列挙型は、PUA シンボルを処理するために使用できる戦略を宣言します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [None](#None) | PUA シンボルの処理を無効にします。この戦略は、レベル B 準拠の PDF/A ドキュメントでデフォルトで使用されます。 |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | この戦略は 'SurroundPuaTextWithEmptyActualText' より遅く動作しますが、SurroundPuaTextWithEmptyActualText では適切に処理できないドキュメントの PUA 準拠エラーを除去できます。PUA シンボルはシンボル 'space' または特殊な Unicode に置き換えられます（一部の PUA シンボルには Unicode の類似物があります）。置き換えはドキュメントのテキストではなく、フォントの内部データ ToUnicode に対して適用されるため、シンボルの表示には影響せず、コピー/貼り付け操作のシステムバッファでのシンボルの提示に影響します。 |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | 空のテキストを含む ActualText エントリを持つマークドコンテンツブロックを挿入します。この戦略はマークドコンテンツブロックがないドキュメントで良好な結果をもたらします。レベル A 準拠の PDF/A ドキュメントでデフォルトで使用されます。 |

### None {#None}
```
public static final int None
```

PUA シンボルの処理を無効にします。この戦略は、レベル B 準拠の PDF/A ドキュメントでデフォルトで使用されます。

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

この戦略は 'SurroundPuaTextWithEmptyActualText' より遅く動作しますが、SurroundPuaTextWithEmptyActualText では適切に処理できないドキュメントの PUA 準拠エラーを除去できます。PUA シンボルはシンボル 'space' または特殊な Unicode に置き換えられます（一部の PUA シンボルには Unicode の類似物があります）。置き換えはドキュメントのテキストではなく、フォントの内部データ ToUnicode に対して適用されるため、シンボルの表示には影響せず、コピー/貼り付け操作のシステムバッファでのシンボルの提示に影響します。

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

空のテキストを含む ActualText エントリを持つマークドコンテンツブロックを挿入します。この戦略はマークドコンテンツブロックがないドキュメントで良好な結果をもたらします。レベル A 準拠の PDF/A ドキュメントでデフォルトで使用されます。
