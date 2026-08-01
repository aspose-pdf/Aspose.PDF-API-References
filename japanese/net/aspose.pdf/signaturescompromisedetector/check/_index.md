---
title: "SignaturesCompromiseDetector.Check"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "SignaturesCompromiseDetector メソッド。ドキュメントのデジタル署名が改ざんされていないかチェックします"
type: docs
weight: 20
url: /ja/net/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector.Check method

ドキュメントのデジタル署名が侵害されていないかチェックします。

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | ドキュメントの検証結果です。 |

### 戻り値

署名の改ざんが検出されなかった場合は True です。

## 備考

デジタル署名が存在しないドキュメントにこのメソッドを使用した場合、`True` が返されます。

### 関連項目

* class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* class [SignaturesCompromiseDetector](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


