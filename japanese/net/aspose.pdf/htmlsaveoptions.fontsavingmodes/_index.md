---
title: "列挙型 HtmlSaveOptions.FontSavingModes"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlSaveOptionsFontSavingModes 列挙型。保存された PDF で参照されるフォントの保存に使用できるモードを列挙します"
type: docs
weight: 5760
url: /ja/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes enumeration

保存された PDF で参照されるフォントの保存に使用できるモードを列挙します。

```csharp
public enum FontSavingModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | すべての参照フォントは保存され、WOFF フォントとして参照されます。 |
| AlwaysSaveAsTTF | `1` | 参照されたすべてのフォントは保存され、TTF-fonts として参照されます。 |
| AlwaysSaveAsEOT | `2` | 参照されたすべてのフォントは保存され、EOT-fonts として参照されます。 |
| SaveInAllFormats | `3` | 参照されたすべてのフォントは、(CSS で参照されることも含めて) 3 つの独立したファイル : EOT, TTH, WOFF として保存されます。これにより出力データのサイズは増加しますが、圧倒的多数のウェブブラウザに適した出力になります。 |
| DontSave | `4` | 参照されたすべてのフォントは保存されません。 |

### 関連項目

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


