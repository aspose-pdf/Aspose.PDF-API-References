---
title: Aspose.Pdf.Security
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security 名前空間には、暗号化およびデジタル署名に使用されるクラスが含まれています
type: docs
weight: 220
url: /ja/net/aspose.pdf.security/
---
**Aspose.Pdf.Security** 名前空間には、暗号化およびデジタル署名に使用されるクラスが含まれています。

## クラス

| クラス | 説明 |
| --- | --- |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | DSA 署名アルゴリズムに関する情報を表すクラスです。 |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | ECDSA 署名アルゴリズムに関する情報を表すクラスです。 |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | キー付き署名アルゴリズムに関する情報を表すクラスです。 |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | RSA 署名アルゴリズムに関する情報を表すクラスです。 |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | 署名アルゴリズムに関する情報を表すクラスで、そのタイプ、暗号標準、およびダイジェストハッシュアルゴリズムを含みます。 |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | PDF 署名中に発生するエラーを表します。[`SignHash`](../aspose.pdf.forms/signhash/) を使用して文書に署名し、実際の署名の長さが[`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/) オプションで指定された長さを超える場合に発生します。 |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | タイムスタンプ署名アルゴリズムに関する情報を表すクラスです。 |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | 不明な署名アルゴリズム情報を表すクラスです。 |
| [ValidationOptions](./validationoptions/) | PDF 文書内のデジタル署名を検証するためのオプションを表します。 |
| [ValidationResult](./validationresult/) | 証明書の検証プロセスの結果を表します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | PDF 文書を保護するための利用可能な暗号標準を表します。 |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | デジタル署名に使用される署名アルゴリズムのタイプを列挙します。 |
| [ValidationMethod](./validationmethod/) | 証明書検証に使用されるメソッドを定義した列挙型を表します。 |
| [ValidationMode](./validationmode/) | PDF 署名検証プロセスの検証モードを指定します。 |
| [ValidationStatus](./validationstatus/) | 証明書検証の検証ステータスを表します。 |