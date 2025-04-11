---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage 列挙型。ドキュメント内のデジタル署名によって提供されるカバレッジのレベルを表す列挙型
type: docs
weight: 10110
url: /ja/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage 列挙型

ドキュメント内のデジタル署名によって提供されるカバレッジのレベルを表す列挙型です。

```csharp
public enum SignaturesCoverage
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Undefined | `0` | ドキュメント内のデジタル署名のカバレッジの状態が未定義であることを示します。この値は、ドキュメント内の1つ以上の署名が侵害されているか、検証できない場合に通常使用され、ドキュメントの署名カバレッジの明確な評価を妨げます。 |
| EntirelySigned | `1` | ドキュメントがデジタル署名によって完全にカバーされていることを示します。この値は、ドキュメントのすべての必要な部分が署名されており、侵害された署名がないことを示します。 |
| PartiallySigned | `2` | ドキュメントが部分的に署名されていることを示します。つまり、一部の内容はデジタル署名でカバーされていますが、すべてではありません。この値は、ドキュメントの特定の部分が未署名であるか、署名カバレッジから除外されている場合に使用されます。 |

### 参照

* 名前空間 [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* アセンブリ [Aspose.PDF](../../)