---
title: Class KeyedSignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.KeyedSignatureAlgorithmInfo クラス。キー付き署名アルゴリズムに関する情報を表すクラス
type: docs
weight: 9980
url: /ja/net/aspose.pdf.security/keyedsignaturealgorithminfo/
---
## KeyedSignatureAlgorithmInfo クラス

キー付き署名アルゴリズムに関する情報を表すクラスです。

```csharp
public abstract class KeyedSignatureAlgorithmInfo : SignatureAlgorithmInfo
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
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 署名に使用されるダイジェストハッシュアルゴリズムを取得します。タイムスタンプの場合、これはドキュメントコンテンツのハッシュが署名されるダイジェストハッシュアルゴリズムです。 |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | 署名アルゴリズムによって使用される暗号鍵のサイズを取得します。 |

### 参照

* クラス [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* 名前空間 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* アセンブリ [Aspose.PDF](../../)