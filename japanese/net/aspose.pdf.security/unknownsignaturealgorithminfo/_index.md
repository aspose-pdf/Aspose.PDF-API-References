---
title: Class UnknownSignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.UnknownSignatureAlgorithmInfo クラス。未知の署名アルゴリズム情報のためのクラスを表します
type: docs
weight: 10040
url: /ja/net/aspose.pdf.security/unknownsignaturealgorithminfo/
---
## UnknownSignatureAlgorithmInfo クラス

未知の署名アルゴリズム情報のためのクラスを表します。

```csharp
public sealed class UnknownSignatureAlgorithmInfo : SignatureAlgorithmInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | 署名フィールドの名前を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | 現在の情報オブジェクトを文字列表現に変換します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | PDF ドキュメントに署名するために使用される署名アルゴリズムのタイプを取得します。 |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | PDF ドキュメントに署名するために使用される暗号標準を取得します。 |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 署名に使用されるダイジェストハッシュアルゴリズムを取得します。タイムスタンプの場合、これはドキュメント内容のハッシュに署名されるダイジェストハッシュアルゴリズムです。 |

### 参照

* クラス [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* 名前空間 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* アセンブリ [Aspose.PDF](../../)