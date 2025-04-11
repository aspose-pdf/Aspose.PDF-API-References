---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSignature クラス。証明書を使用して PDF ファイルに署名するクラスを表します。
type: docs
weight: 4560
url: /ja/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature クラス

証明書を使用して PDF ファイルに署名するクラスを表します。

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | PdfFileSignature クラスのコンストラクタ。 |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | *document* に基づいて新しい `PdfFileSignature` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | ドキュメントが認証されているかどうかを示すフラグを取得します。 |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | LTV 有効フラグを取得します。 |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | 署名のグラフィック外観を設定または取得します。プロパティ値は画像ファイル名を表します。 |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | 署名のグラフィック外観を設定または取得します。プロパティ値は画像ストリームを表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | 編集のために PDF ストリームをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | 編集のために PDF ファイルをバインドします。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | 既に提示された署名フィールドに配置された MDP 署名でドキュメントを認証します。署名する前に署名フィールドは空でなければなりません。すなわち、フィールドには署名辞書が含まれていない必要があります。したがって、PDF ドキュメントにはすでに署名フィールドがあり、署名を押す場所を提供する必要はありません。対応するページと矩形は、署名名によって見つけられた署名フィールドから取得されます（sigName パラメータを参照）。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | MDP 署名でドキュメントを認証します。署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティによって提供される必要があります。 |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | ファサードを閉じます。 |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | PDF にデジタル署名があるかどうかを確認します。 |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | PDF に使用権があるかどうかを確認します。 |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | 署名が文書全体をカバーしているかどうかを確認します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | 署名の単一の X.509 証明書をストリームとして抽出します。 |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | 署名の画像を抽出します。 |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | MDP 署名タイプによる認証済みドキュメントのアクセス許可値を返します。 |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | すべての空の署名フィールドの名前を取得します。 |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | 署名の連絡先情報を取得します。 |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | 署名の日時を取得します。 |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | 署名の場所を取得します。 |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | 署名の理由を取得します。 |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | 署名の改訂を取得します。 |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | すべての空でない署名の名前を取得します。 |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | PDF ドキュメントに存在するすべての署名アルゴリズムに関する情報を取得します。 |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | PDF ドキュメントに署名している人または組織の名前を取得します。 |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | 総改訂を取得します。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | 署名の名前に従って署名を削除します。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | 署名の名前に従って署名を削除します。 |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | すべての署名を削除します。 |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | 使用権エントリを削除します。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | 結果の PDF をストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | 結果の PDF をファイルに保存します。 |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | 署名ルーチンのために証明書ファイルとパスワードを設定します。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | 既に提示された署名フィールドに配置された指定されたタイプの署名でドキュメントに署名します。署名する前に署名フィールドは空でなければなりません。すなわち、フィールドには署名辞書が含まれていない必要があります。したがって、PDF ドキュメントにはすでに署名フィールドがあり、署名を押す場所を提供する必要はありません。対応するページと矩形は、署名名によって見つけられた署名フィールドから取得されます（SigName パラメータを参照）。署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティによって提供される必要があります。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | 指定されたタイプの署名でドキュメントに署名します。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | 既に提示された署名フィールドに配置された指定されたタイプの署名でドキュメントに署名します。署名する前に署名フィールドは空でなければなりません。すなわち、フィールドには署名辞書が含まれていない必要があります。したがって、PDF ドキュメントにはすでに署名フィールドがあり、署名を押す場所を提供する必要はありません。対応するページと矩形は、署名名によって見つけられた署名フィールドから取得されます（SigName パラメータを参照）。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | PDF ドキュメントに署名を作成します。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | 指定されたタイプの署名でドキュメントに署名します。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | 既に提示された署名フィールドに配置された指定されたタイプの署名でドキュメントに署名します。署名する前に PDF ドキュメントにはすでに署名フィールドが必要であり、対応するページと矩形は、署名名によって見つけられた署名フィールドから取得されます（SigName パラメータを参照）。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | 署名の有効性を確認します。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | 署名の有効性を確認します。 |

### 参照

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)