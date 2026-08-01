---
title: "Aspose.Pdf.Security"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Security 名前空間には、暗号化とデジタル署名に使用されるクラスが含まれています。"
type: docs
weight: 210
url: /ja/net/aspose.pdf.security/
---
**Aspose.Pdf.Security** 名前空間には、暗号化とデジタル署名に使用されるクラスが含まれています。

## クラス

| クラス | 説明 |
| --- | --- |
| [CertificateEncryptionOptions](./certificateencryptionoptions/) | 証明書ベースの暗号化方式を使用して PDF ドキュメントの暗号化オプションを表すクラスです。暗号化された PDF ドキュメントを開くために使用されます。 |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | DSA 署名アルゴリズムに関する情報を表すクラスです。 |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | ECDSA 署名アルゴリズムに関する情報を表すクラスです。 |
| [EncryptionParameters](./encryptionparameters/) | 暗号化パラメータクラスを表します。 |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | キー付き署名アルゴリズムに関する情報を表すクラスです。 |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | RSA 署名アルゴリズムに関する情報を表すクラスです。 |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | 署名アルゴリズムに関する情報（タイプ、暗号標準、ダイジェストハッシュアルゴリズムを含む）を表すクラスです。 |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | PDF 署名中に発生するエラーを表します。もし [`SignHash`](../aspose.pdf.forms/signhash/) がドキュメントに署名するために使用され、実際の署名長が [`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/) オプションで指定された長さを超える場合に発生します。 |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | タイムスタンプ署名アルゴリズムに関する情報を表すクラスです。 |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | 不明な署名アルゴリズム情報を表すクラスです。 |
| [ValidationOptions](./validationoptions/) | PDF ドキュメント内のデジタル署名を検証するためのオプションを表します。 |
| [ValidationResult](./validationresult/) | 証明書の検証プロセスの結果を表します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [ICustomSecurityHandler](./icustomsecurityhandler/) | カスタム セキュリティ ハンドラ インターフェイスです。 |
## 列挙体

| 列挙体 | 説明 |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | PDF ドキュメントの保護に利用できる暗号標準を表します。 |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | デジタル署名で使用される署名アルゴリズムの種類を列挙します。 |
| [ValidationMethod](./validationmethod/) | 証明書検証に使用される方法を定義した列挙型を表します。 |
| [ValidationMode](./validationmode/) | PDF 署名検証プロセスの検証モードを指定します。 |
| [ValidationStatus](./validationstatus/) | 証明書検証の検証ステータスを表します。 |


