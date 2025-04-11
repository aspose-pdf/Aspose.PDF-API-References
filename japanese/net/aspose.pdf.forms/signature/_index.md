---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Signatureクラス。PDFドキュメント内の署名オブジェクトを表す抽象クラス。署名は、署名オブジェクトの値を持つフィールドであり、最後のものはドキュメントの有効性を確認するために使用されるデータを含む。
type: docs
weight: 5270
url: /ja/net/aspose.pdf.forms/signature/
---
## Signatureクラス

PDFドキュメント内の署名オブジェクトを表す抽象クラス。署名は、署名オブジェクトの値を持つフィールドであり、最後のものはドキュメントの有効性を確認するために使用されるデータを含む。

```csharp
public abstract class Signature
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Signature](signature/#constructor)() | `Signature`クラスの新しいインスタンスを初期化します。 |
| [Signature](signature/#constructor_1)(Stream, string) | `Signature`クラスの新しいインスタンスを初期化します。 |
| [Signature](signature/#constructor_2)(string, string) | `Signature`クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | ドキュメントに署名する人または権限の名前。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 署名の長さを推定しないかどうかを示すオプションを取得および設定します。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | ダイジェスト計算のための正確なバイト範囲を記述する整数のペアの配列（開始バイトオフセット、バイト数）。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 署名者が署名を確認するために受取人が署名者に連絡できるように提供する情報（例：電話番号）。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | カスタム外観を取得/設定します。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | ドキュメントハッシュをカスタム署名するためのデリゲート。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 署名の時間。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | バイト単位での署名データのデフォルトの長さを取得または設定します。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 署名のCPUホスト名または物理的な場所。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | ocsp設定を取得/設定します。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 署名の理由（例：同意します、Pip B.）。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 署名プロパティを強制的に表示/非表示にします。ShowPropertiesがtrueの場合、署名フィールドには次のような外観の事前定義された形式があります（表現する文字列）： ------------------------------------------- {certificate subject}によってデジタル署名 日付：{signature.Date} 理由：{signature.Reason} 場所：{signature.Location} ------------------------------------------- ここで、{X}はX値のプレースホルダーです。また、署名には画像を含めることができ、この場合、リストされた文字列は画像の上に配置されます。ShowPropertiesはデフォルトでtrueです。 |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | タイムスタンプ設定を取得/設定します。 |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | ltv検証フラグを取得/設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 署名に使用される署名アルゴリズムに関する情報を取得します。 |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | この署名に関してドキュメントを検証し、ドキュメントが有効な場合はtrueを、そうでない場合はfalseを返します。 |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | この署名に関してドキュメントを検証し、ドキュメントが有効な場合はtrueを、そうでない場合はfalseを返します。 |

### 参照

* 名前空間 [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../)