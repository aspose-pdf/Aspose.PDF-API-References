---
title: "クラス SignatureAlgorithmInfo"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Security.SignatureAlgorithmInfo クラス。署名アルゴリズムの種類、暗号標準、ダイジェストハッシュアルゴリズムなどに関する情報を表すクラスです。"
type: docs
weight: 10180
url: /ja/net/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo class

署名アルゴリズムに関する情報（タイプ、暗号標準、ダイジェストハッシュアルゴリズムを含む）を表すクラスです。

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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | PDF ドキュメントの署名に使用される署名アルゴリズムのタイプを取得します。 |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | PDF ドキュメントの署名に使用される暗号標準を取得します。 |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 署名に使用されるダイジェストハッシュアルゴリズムを取得します。タイムスタンプの場合、これは文書内容のハッシュが署名されるダイジェストハッシュアルゴリズムです。 |

### 関連項目

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


