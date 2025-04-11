---
title: Class PKCS7
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7 クラス。インターネット RFC 2315 PKCS 7 暗号化メッセージ構文バージョン 1.5 に準拠した PKCS7 オブジェクトを表します。ドキュメントのバイト範囲の SHA1 ダイジェストは、PKCS7 SignedData フィールドにカプセル化されています。
type: docs
weight: 5180
url: /ja/net/aspose.pdf.forms/pkcs7/
---
## PKCS7 クラス

インターネット RFC 2315 の PKCS#7 仕様に準拠した PKCS#7 オブジェクトを表します。ドキュメントのバイト範囲の `SHA1 ダイジェスト` は、PKCS#7 SignedData フィールドにカプセル化されています。

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
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | ドキュメントに署名する人または権限の名前。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 署名の長さを推定しないかどうかを示すオプションを取得および設定します。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | ダイジェスト計算のための正確なバイト範囲を記述する整数のペアの配列 (開始バイトオフセット、バイト数) です。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 署名者が署名を確認するために受取人が署名者に連絡できるように提供する情報、例えば電話番号。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | カスタム外観を取得/設定します。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | ドキュメントハッシュをカスタム署名するためのデリゲート。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 署名の時間。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 署名データのデフォルトの長さをバイト単位で取得または設定します。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 署名の CPU ホスト名または物理的な場所。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | ocsp 設定を取得/設定します。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 署名の理由、例えば (同意します、Pip B.)。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 署名プロパティを表示/非表示にすることを強制します。ShowProperties が true の場合、署名フィールドには次のような事前定義された外観形式があります (表現する文字列): ------------------------------------------- {certificate subject} によってデジタル署名 日付: {signature.Date} 理由: {signature.Reason} 場所: {signature.Location} ------------------------------------------- ここで {X} は X 値のプレースホルダーです。また、署名には画像を含めることができ、この場合、リストされた文字列は画像の上に配置されます。ShowProperties はデフォルトで true です。 |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | タイムスタンプ設定を取得/設定します。 |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | ltv 検証フラグを取得/設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 署名に使用される署名アルゴリズムに関する情報を取得します。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true を返し、そうでない場合は false を返します。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true を返し、そうでない場合は false を返します。 |

### 参照

* クラス [Signature](../signature/)
* 名前空間 [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../)