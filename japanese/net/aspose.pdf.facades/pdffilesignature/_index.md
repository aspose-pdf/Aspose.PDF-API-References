---
title: "クラス PdfFileSignature"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfFileSignature クラス。証明書で PDF ファイルに署名するクラスを表します。"
type: docs
weight: 4680
url: /ja/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

証明書で PDF ファイルに署名するクラスを表します。

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | PdfFileSignature クラスのコンストラクタ。 |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | 新しい `PdfFileSignature` オブジェクトを *document* を基に初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | ドキュメントが認証されているかどうかを決定するフラグを取得します。 |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | LTV が有効かどうかのフラグを取得します。 |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | 署名のグラフィック外観を設定または取得します。プロパティ値は画像ファイル名を表します。 |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | 署名のグラフィック外観を設定または取得します。プロパティ値は画像ストリームを表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | 編集用に Pdf ストリームをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | 編集用に Pdf ファイルをバインドします。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | 既に存在する署名フィールドに配置された MDP 署名でドキュメントを認証します。署名を行う前に署名フィールドは空である必要があります。つまり、フィールドに署名ディクショナリが含まれていてはいけません。そのため、pdf ドキュメントにはすでに署名フィールドがあり、署名をスタンプする場所、対応するページおよび矩形は、署名名（sigName パラメータを参照）で見つかる署名フィールドから取得されます。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | MDP 署名でドキュメントを認証します。署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティで提供する必要があります。 |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | ファサードを閉じます。 |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | PDF にデジタル署名があるかどうかを確認します。 |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | PDF に使用権があるかどうかを確認します。 |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | 署名が文書全体をカバーしているかどうかを確認します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | 署名の単一 X.509 証明書をストリームとして抽出します。 |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | 署名の画像を抽出します。 |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | MDP 署名タイプによる認証済み文書のアクセス許可値を返します。 |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | すべての空の署名フィールドの名前を取得します。 |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | 署名の連絡先情報を取得します。 |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | 署名の日付時刻を取得します。 |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | 署名の場所を取得します。 |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | 署名の理由を取得します。 |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | 署名のリビジョンを取得します。 |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | 空でないすべての署名の名前を取得します。 |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | PDF 文書に存在するすべての署名アルゴリズムに関する情報を取得します。 |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | PDF 文書に署名した人物または組織の名前を取得します。 |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | 総リビジョンを取得します。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | 署名名に基づいて署名を削除します。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | 署名名に基づいて署名を削除します。 |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | すべての署名を削除します。 |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | 使用権エントリを削除します。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | 結果の PDF をストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | 結果の PDF をファイルに保存します。 |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | 署名処理のために証明書ファイルとパスワードを設定します。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | 既に配置されている署名フィールドに配置された指定タイプの署名で文書に署名します。署名を行う前に署名フィールドは空である必要があり、つまりフィールドに署名ディクショナリが含まれていてはなりません。そのため、PDF 文書にはすでに署名フィールドが存在し、署名をスタンプする場所を指定する必要はなく、対応するページと矩形は署名名で見つかる署名フィールドから取得されます（SigName パラメータ参照）。署名の理由、連絡先、場所などのデータは Signature オブジェクト sig の対応するプロパティで提供する必要があります。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | 指定されたタイプの署名で文書に署名します。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | 既に配置されている署名フィールドに配置された指定タイプの署名で文書に署名します。署名を行う前に署名フィールドは空である必要があり、つまりフィールドに署名ディクショナリが含まれていてはなりません。そのため、PDF 文書にはすでに署名フィールドが存在し、署名をスタンプする場所を指定する必要はなく、対応するページと矩形は署名名で見つかる署名フィールドから取得されます（SigName パラメータ参照）。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | PDF 文書に署名を作成します。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | 指定されたタイプの署名で文書に署名します。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | 既に表示されている署名フィールドに配置された指定されたタイプの署名でドキュメントに署名します。署名を行う前に、pdf ドキュメントには署名フィールドが既に存在している必要があり、対応するページと矩形は署名名で見つかる署名フィールドから取得されます（SigName パラメータを参照）。 |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | 署名の単一 X.509 証明書をストリームとして抽出します。 |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | 署名の単一 X.509 証明書を抽出します。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | 署名の有効性をチェックします。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | 署名の有効性をチェックします。検証は外部の公開鍵証明書を使用して実行されます。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | 署名の有効性をチェックします。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | 署名の有効性をチェックします。検証は外部の公開鍵証明書を使用して実行されます。 |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


