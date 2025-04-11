---
title: Class CompromiseCheckResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.CompromiseCheckResult クラス。文書のデジタル署名の妥協をチェックするためのクラスを表します
type: docs
weight: 10100
url: /ja/net/aspose.pdf.signatures/compromisecheckresult/
---
## CompromiseCheckResult クラス

文書のデジタル署名の妥協をチェックするためのクラスを表します。

```csharp
public sealed class CompromiseCheckResult
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HasCompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/hascompromisedsignatures/) { get; } | 文書に妥協されたデジタル署名があるかどうかを示します。少なくとも1つの署名が妥協されている場合はtrueを返し、それ以外の場合はfalseを返します。 |
| [SignaturesCoverage](../../aspose.pdf.signatures/compromisecheckresult/signaturescoverage/) { get; } | 文書内のデジタル署名のカバレッジ状態を取得します。未定義と等しい場合は、署名の1つが妥協されています。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| readonly [CompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/compromisedsignatures/) | 妥協されたと特定されたデジタル署名のコレクションを取得します。このプロパティには、文書内で検出されたすべての妥協された署名のリストが含まれています。 |

### 参照

* 名前空間 [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* アセンブリ [Aspose.PDF](../../)