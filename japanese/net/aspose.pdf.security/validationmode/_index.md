---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMode 列挙型。PDF 署名検証プロセスの検証モードを指定します
type: docs
weight: 10060
url: /ja/net/aspose.pdf.security/validationmode/
---
## ValidationMode 列挙型

PDF 署名検証プロセスの検証モードを指定します。

```csharp
public enum ValidationMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | 検証が行われないモードを表します。 |
| OnlyCheck | `1` | 検証が行われるモードを表しますが、その結果はデジタル署名の検証には影響しません。検証の結果を自分で確認できます。 |
| Strict | `2` | 検証が行われ、その結果がデジタル署名の検証に影響するモードを表します。証明書が確認できなかった場合、デジタル署名は無効と見なされます。検証の結果を自分で確認できます。 |

### 参照

* 名前空間 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* アセンブリ [Aspose.PDF](../../)