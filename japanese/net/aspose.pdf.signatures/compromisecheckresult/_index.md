---
title: "クラス CompromiseCheckResult"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Signatures.CompromiseCheckResult クラス。ドキュメントのデジタル署名の改ざんをチェックするクラスを表します"
type: docs
weight: 10280
url: /ja/net/aspose.pdf.signatures/compromisecheckresult/
---
## CompromiseCheckResult class

ドキュメントのデジタル署名が改ざんされていないか確認するクラスを表します。

```csharp
public sealed class CompromiseCheckResult
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HasCompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/hascompromisedsignatures/) { get; } | ドキュメントに改ざんされたデジタル署名があるかどうかを示します。少なくとも1つの署名が改ざんされている場合は true を返し、そうでない場合は false を返します。 |
| [SignaturesCoverage](../../aspose.pdf.signatures/compromisecheckresult/signaturescoverage/) { get; } | Document のデジタル署名のカバレッジ状態を取得します。Undefined と等しい場合、署名のいずれかが破損しています。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| readonly [CompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/compromisedsignatures/) | 破損したと判定されたデジタル署名のコレクションを取得します。このプロパティには、Document で検出されたすべての破損署名のリストが含まれます。 |

### 関連項目

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)


