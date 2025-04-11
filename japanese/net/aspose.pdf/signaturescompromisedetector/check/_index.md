---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: SignaturesCompromiseDetector メソッド。文書のデジタル署名が妥協されているかどうかを確認します
type: docs
weight: 20
url: /ja/net/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector.Check メソッド

文書のデジタル署名が妥協されているかどうかを確認します。

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | 文書の検証結果。 |

### 戻り値

署名の妥協が検出されない場合は True を返します。

## 備考

デジタル署名がない文書に対してこのメソッドを使用すると、`True` が返されます。

### 参照

* クラス [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* クラス [SignaturesCompromiseDetector](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)