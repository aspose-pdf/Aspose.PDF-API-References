---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7Detached クラス。インターネット RFC 2315 PKCS 7 暗号化メッセージ構文バージョン 1.5 に準拠した PKCS7 オブジェクトを表します。ドキュメントのバイト範囲に対する元の署名済みメッセージダイジェストは、通常の PKCS7 SignedData フィールドとして組み込まれます。PKCS7 SignedData フィールドにはデータはカプセル化されません。
type: docs
weight: 5190
url: /ja/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached クラス

PKCS#7 オブジェクトを表し、インターネット RFC 2315 の PKCS#7 仕様に準拠しています。PKCS #7: 暗号化メッセージ構文、バージョン 1.5。ドキュメントのバイト範囲に対する元の署名済みメッセージダイジェストは、通常の PKCS#7 SignedData フィールドとして組み込まれます。PKCS#7 SignedData フィールドにはデータはカプセル化されません。

```csharp
public sealed class PKCS7Detached : Signature
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | `PKCS7Detached` クラスの新しいインスタンスを初期化します。 |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | `PKCS7Detached` クラスの新しいインスタンスを初期化します。 |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | `PKCS7Detached` クラスの新しいインスタンスを初期化します。 |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | `PKCS7Detached` クラスの新しいインスタンスを初期化します。 |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | `PKCS7Detached` クラスの新しいインスタンスを初期化します。 |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | `PKCS7Detached` クラスの新しいインスタンスを初期化します。 |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | `PKCS7Detached` クラスの新しいインスタンスを初期化します。 |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | `PKCS7Detached` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | ドキュメントに署名した人物または権限の名前。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 署名の長さを推定しないかどうかを示すオプションを取得および設定します。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | ダイジェスト計算のための正確なバイト範囲を記述する整数のペアの配列 (開始バイトオフセット、バイト数) です。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 署名者が署名を確認するために受取人が署名者に連絡できるように提供する情報、例: 電話番号。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | カスタム外観を取得/設定します。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | ドキュメントハッシュをカスタム署名するためのデリゲート。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 署名の時間。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | バイト単位で署名データのデフォルトの長さを取得または設定します。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 署名の CPU ホスト名または物理的な場所。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | ocsp 設定を取得/設定します。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 署名の理由、例: (同意します、Pip B.)。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 署名プロパティを表示/非表示にすることを強制します。ShowProperties が true の場合、署名フィールドには次のような外観の事前定義された形式があります (表現する文字列): ------------------------------------------- {証明書の件名} によってデジタル署名されました 日付: {signature.Date} 理由: {signature.Reason} 場所: {signature.Location} ------------------------------------------- ここで {X} は X 値のプレースホルダーです。また、署名には画像を含めることができ、この場合、リストされた文字列は画像の上に配置されます。ShowProperties はデフォルトで true です。 |
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