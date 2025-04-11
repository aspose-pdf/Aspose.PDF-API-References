---
title: Class SignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.SignatureAlgorithmInfo クラス。署名アルゴリズムに関する情報を表すクラスで、そのタイプ、暗号標準、およびダイジェストハッシュアルゴリズムを含みます。
type: docs
weight: 10000
url: /ja/net/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo クラス

署名アルゴリズムに関する情報を表すクラスで、そのタイプ、暗号標準、およびダイジェストハッシュアルゴリズムを含みます。

```csharp
public abstract class SignatureAlgorithmInfo
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
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 署名に使用されるダイジェストハッシュアルゴリズムを取得します。タイムスタンプの場合、これはドキュメントコンテンツのハッシュに署名されるダイジェストハッシュアルゴリズムです。 |

### 参照

* 名前空間 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* アセンブリ [Aspose.PDF](../../)