---
title: "列挙型 ValidationMode"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Security.ValidationMode 列挙型。PDF 署名検証プロセスの検証モードを指定します。"
type: docs
weight: 10240
url: /ja/net/aspose.pdf.security/validationmode/
---
## ValidationMode enumeration

PDF 署名検証プロセスの検証モードを指定します。

```csharp
public enum ValidationMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | 検証が実行されないモードを表します。 |
| OnlyCheck | `1` | 検証が行われるが、その結果がデジタル署名の検証に影響しないモードを表します。検証結果は自分で確認できます。 |
| Strict | `2` | 検証が行われ、その結果がデジタル署名の検証に影響するモードを表します。証明書が検証できない場合、デジタル署名は無効とみなされます。検証結果は自分で確認できます。 |

### 関連項目

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


