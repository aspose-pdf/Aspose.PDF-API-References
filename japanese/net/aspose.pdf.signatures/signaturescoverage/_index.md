---
title: "列挙体 SignaturesCoverage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Signatures.SignaturesCoverage 列挙体。ドキュメント内のデジタル署名が提供するカバレッジレベルを表す列挙体です。"
type: docs
weight: 10290
url: /ja/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enumeration

ドキュメント内のデジタル署名が提供するカバレッジレベルを示す列挙型を表します。

```csharp
public enum SignaturesCoverage
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Undefined | `0` | Document のデジタル署名のカバレッジ状態が未定義であることを示します。この値は、Document 内の1つ以上の署名が破損しているか検証できない場合に使用され、署名カバレッジの明確な評価を妨げます。 |
| EntirelySigned | `1` | Document がデジタル署名で完全にカバーされていることを示します。この値は、Document のすべての必須部分が署名され、署名が破損していないことを意味します。 |
| PartiallySigned | `2` | Document が部分的に署名されていることを示します。つまり、コンテンツの一部はデジタル署名でカバーされていますが、すべてではありません。この値は、Document の特定の部分が未署名のままであるか、署名カバレッジから除外されている場合に使用されます。 |

### 関連項目

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)


