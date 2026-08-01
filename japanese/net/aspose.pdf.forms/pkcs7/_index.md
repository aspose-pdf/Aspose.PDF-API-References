---
title: "クラス PKCS7"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Forms.PKCS7 クラス。インターネット RFC 2315 PKCS 7 暗号メッセージ構文バージョン 1.5 の PKCS7 仕様に準拠した PKCS7 オブジェクトを表します。ドキュメントのバイト範囲の SHA1 ダイジェストが PKCS7 SignedData フィールドにカプセル化されます。"
type: docs
weight: 5300
url: /ja/net/aspose.pdf.forms/pkcs7/
---
## PKCS7 class

Internet RFC 2315、PKCS #7: Cryptographic Message Syntax、Version 1.5 の PKCS#7 仕様に準拠した PKCS#7 オブジェクトを表します。ドキュメントのバイト範囲の `SHA1 digest` が PKCS#7 SignedData フィールドにカプセル化されます。

```csharp
public sealed class PKCS7 : Signature
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PKCS7](pkcs7/#constructor)() | `PKCS7` クラスの新しいインスタンスを初期化します。 |
| [PKCS7](pkcs7/#constructor_1)(Stream, string) | `PKCS7` クラスの新しいインスタンスを初期化します。 |
| [PKCS7](pkcs7/#constructor_2)(string, string) | `PKCS7` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | 文書に署名する人物または機関の名前。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 署名の長さの推定を回避するかどうかを示すオプションを取得および設定します。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | ダイジェスト計算の正確なバイト範囲を記述する整数のペア（開始バイトオフセット、バイト単位の長さ）の配列。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 署名者が提供する情報で、受取人が署名者に連絡して署名を検証できるようにするもの（例：電話番号）。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | カスタム外観を取得/設定します。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | ドキュメントハッシュをカスタム署名するためのデリゲート。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 署名時刻。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 署名データのデフォルト長さ（バイト単位）を取得または設定します。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 署名の CPU ホスト名または物理的な場所。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | OCSP 設定を取得/設定します。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 署名の理由（例：I agree, Pip B.）。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 署名プロパティの表示/非表示を強制します。ShowProperties が true の場合、署名フィールドは外観の事前定義フォーマット（文字列で表現）を持ちます： ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- ここで {X} は X の値のプレースホルダーです。また、署名に画像がある場合、これらの文字列は画像上に配置されます。ShowProperties はデフォルトで true です。 |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | タイムスタンプ設定を取得/設定します。 |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | LTV 検証フラグを取得/設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 署名で使用されている署名アルゴリズムに関する情報を取得します。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | この署名に関して文書を検証し、文書が有効な場合は true、そうでない場合は false を返します。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | この署名に関して文書を検証し、文書が有効な場合は true、そうでない場合は false を返します。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)(X509Certificate2, ValidationOptions, out ValidationResult) | この署名に関して文書を検証し、文書が有効な場合は true、そうでない場合は false を返します。検証は外部の公開鍵証明書を使用して実行されます。 |

### 関連項目

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


