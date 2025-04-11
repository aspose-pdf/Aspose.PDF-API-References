---
title: Enum HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontSavingModes 列挙型。保存された PDF に参照されるフォントの保存に使用できるモードを列挙します。
type: docs
weight: 5630
url: /ja/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes 列挙型

保存された PDF に参照されるフォントの保存に使用できるモードを列挙します。

```csharp
public enum FontSavingModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | すべての参照されたフォントは保存され、WOFFフォントとして参照されます。 |
| AlwaysSaveAsTTF | `1` | すべての参照されたフォントは保存され、TTFフォントとして参照されます。 |
| AlwaysSaveAsEOT | `2` | すべての参照されたフォントは保存され、EOTフォントとして参照されます。 |
| SaveInAllFormats | `3` | すべての参照されたフォントは保存され（CSSで参照され）、3つの独立したファイルとして保存されます：EOT、TTH、WOFF。出力データのサイズは増加しますが、出力は圧倒的多数のウェブブラウザに適したものになります。 |
| DontSave | `4` | すべての参照されたフォントは保存されません。 |

### 参照

* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)