---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "証明書で PDF ファイルに署名するクラスを表します。"
type: docs
weight: 530
url: /ja/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

証明書で PDF ファイルに署名するクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | PdfFileSignature クラスのコンストラクタです。 |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | PdfFileSignature クラスのコンストラクタです。 |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | PdfFileSignature クラスのコンストラクタです。 |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | PdfFileSignature クラスのコンストラクタです。 |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | PdfFileSignature クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Pdf ストリームを編集用にバインドします。 |
| [bindPdf](#bindPdf-java.lang.String-) | Pdf ファイルを編集用にバインドします。 |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | MDP 署名でドキュメントを認証します。 |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | 既に存在する署名フィールドに配置された MDP 署名でドキュメントを認証します。署名を行う前に署名フィールドは空である必要があります。つまり、フィールドに署名ディクショナリが含まれていてはなりません。そのため、PDF ドキュメントに署名フィールドが既にある場合、署名をスタンプする場所を指定する必要はなく、対応するページと矩形は署名名（sigName パラメータを参照）で見つかる署名フィールドから取得されます。 |
| [close](#close--) | ファサードを閉じます。 |
| [containsSignature](#containsSignature--) | PDF にデジタル署名があるかどうかを確認します。 |
| [containsUsageRights](#containsUsageRights--) | PDF に使用権があるかどうかを確認します。 |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | 署名がドキュメント全体をカバーしているかどうかを確認します。 |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | 署名がドキュメント全体をカバーしているかどうかを確認します。 |
| [dispose](#dispose--) | ファサードを閉じます。このメソッドは廃止予定で、代わりに close() を使用してください。 |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | 署名の単一 X.509 証明書をストリームとして抽出します。 |
| [extractCertificate](#extractCertificate-java.lang.String-) | 署名の単一 X.509 証明書をストリームとして抽出します。 |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | 署名の画像を抽出します。 |
| [extractImage](#extractImage-java.lang.String-) | 署名の画像を抽出します。 |
| [getAccessPermissions](#getAccessPermissions--) | MDP 署名タイプによって認証されたドキュメントのアクセス許可値を返します。 |
| [getBlankSignNames](#getBlankSignNames--) | 空の署名フィールドのすべての名前を取得します。 |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | 署名の連絡先情報を取得します。 |
| [getContactInfo](#getContactInfo-java.lang.String-) | 署名の連絡先情報を取得します。 |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | 署名の日付と時刻を取得します。 |
| [getDateTime](#getDateTime-java.lang.String-) | 署名の日付と時刻を取得します。 |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | 署名の場所を取得します。 |
| [getLocation](#getLocation-java.lang.String-) | 署名の場所を取得します。 |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | 署名の理由を取得します。 |
| [getReason](#getReason-java.lang.String-) | 署名の理由を取得します。 |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | 署名のリビジョンを取得します。 |
| [getRevision](#getRevision-java.lang.String-) | 署名のリビジョンを取得します。 |
| [getSignatureAppearance](#getSignatureAppearance--) | 署名のグラフィック外観を取得します。プロパティ値は画像ファイル名を表します。 |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | 署名のグラフィック外観を取得します。プロパティ値は画像ストリームを表します。 |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * 空でないすべての署名の名前を取得します。 / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | 空でないすべての署名の名前を取得します。 string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | PDFドキュメントに存在するすべての署名アルゴリズムに関する情報を取得します。 |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | PDFドキュメントに署名する人物または組織の名前を取得します。 |
| [getSignerName](#getSignerName-java.lang.String-) | PDFドキュメントに署名する人物または組織の名前を取得します。 |
| [getSignNames](#getSignNames--) | <p> 空でないすべての署名の名前を取得します。 </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> 空でないすべての署名の名前を取得します。 </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | 総リビジョンを取得します。 |
| [isCertified](#isCertified--) | ドキュメントが認証されているかどうかを示すフラグを取得します。 |
| [isContainSignature](#isContainSignature--) | PDF にデジタル署名があるかどうかを確認します。 |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | 署名がドキュメント全体をカバーしているかどうかを確認します。 |
| [isLtvEnabled](#isLtvEnabled--) | LTV有効フラグを取得します。 |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | 署名の名前に従って署名を削除します。 string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | 署名の名前に従って署名を削除します。 string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> 署名の名前に従って署名を削除します。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> 署名の名前に従って署名を削除します。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | すべての署名を削除します。 string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | 使用権エントリを削除します。 |
| [save](#save--) | 署名済みPDFファイルを保存します。出力ファイル名は、対応するPdfFileSignatureコンストラクタを使用して事前に指定する必要があります。 |
| [save](#save-java.io.OutputStream-) | 署名済みPDFファイルを保存します。出力ファイル名は、対応するPdfFileSignatureコンストラクタを使用して事前に指定する必要があります。 |
| [save](#save-java.lang.String-) | 署名済みPDFファイルを保存します。出力ファイル名は、対応するPdfFileSignatureコンストラクタを使用して事前に指定する必要があります。 |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | 署名処理のために証明書ファイルとパスワードを設定します。 |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | 署名のグラフィック外観を設定します。プロパティ値は画像ファイル名を表します。 |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | 署名のグラフィック外観を設定します。プロパティ値は画像ストリームを表します。 |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 指定されたタイプの署名でドキュメントに署名します。 |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | PDFドキュメントに署名を作成します。 |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 指定されたタイプの署名でドキュメントに署名します。 |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 既に提示されている署名フィールドに配置された指定タイプの署名でドキュメントに署名します。 |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> 既に提示されている署名フィールドに配置された指定タイプの署名でドキュメントに署名します。署名を行う前に署名フィールドは空である必要があります。つまり、フィールドに署名ディクショナリが含まれていてはいけません。そのため、PDFドキュメントにはすでに署名フィールドがあり、署名を配置する場所やページ、矩形を指定する必要はありません。これらは署名名（SigName パラメータ参照）で見つかる署名フィールドから取得されます。署名の理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティで提供する必要があります。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> 既に提示されている署名フィールドに配置された指定タイプの署名でドキュメントに署名します。署名を行う前に署名フィールドは空である必要があります。つまり、フィールドに署名ディクショナリが含まれていてはいけません。そのため、PDFドキュメントにはすでに署名フィールドがあり、署名を配置する場所やページ、矩形を指定する必要はありません。これらは署名名（SigName パラメータ参照）で見つかる署名フィールドから取得されます。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | 署名の単一 X.509 証明書をストリームとして抽出します。 |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | 署名の単一 X.509 証明書を抽出します。 |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | 署名の有効性をチェックします。 |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | 署名の有効性をチェックします。 |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | 署名の有効性をチェックします。 |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | 署名の有効性をチェックします。 |
| [verifySignature](#verifySignature-java.lang.String-) | 署名の有効性をチェックします。 |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | 署名の有効性をチェックします。 |
| [verifySigned](#verifySigned-java.lang.String-) | 署名の有効性をチェックします。このメソッドは非推奨で、バージョン 25.1 で削除されます。代わりに VerifySignature メソッドを使用してください。 |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

PdfFileSignature クラスのコンストラクタです。

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
PdfFileSignature クラスのコンストラクタです。

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
PdfFileSignature クラスのコンストラクタです。

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
PdfFileSignature クラスのコンストラクタです。

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
PdfFileSignature クラスのコンストラクタです。

### bindPdf {#bindPdf-java.io.InputStream-}
Pdf ストリームを編集用にバインドします。

### bindPdf {#bindPdf-java.lang.String-}
Pdf ファイルを編集用にバインドします。

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
MDP 署名でドキュメントを認証します。

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
既に存在する署名フィールドに配置された MDP 署名でドキュメントを認証します。署名を行う前に署名フィールドは空である必要があります。つまり、フィールドに署名ディクショナリが含まれていてはなりません。そのため、PDF ドキュメントに署名フィールドが既にある場合、署名をスタンプする場所を指定する必要はなく、対応するページと矩形は署名名（sigName パラメータを参照）で見つかる署名フィールドから取得されます。

### close {#close--}
```
public void close()
```

ファサードを閉じます。

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

PDF にデジタル署名があるかどうかを確認します。

**Returns:**
bool 型の結果を返します。

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

PDF に使用権があるかどうかを確認します。

**Returns:**
bool 型の結果を返します。

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
署名がドキュメント全体をカバーしているかどうかを確認します。

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
署名がドキュメント全体をカバーしているかどうかを確認します。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

ファサードを閉じます。このメソッドは廃止予定で、代わりに close() を使用してください。

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
署名の単一 X.509 証明書をストリームとして抽出します。

### extractCertificate {#extractCertificate-java.lang.String-}
署名の単一 X.509 証明書をストリームとして抽出します。

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
署名の画像を抽出します。

### extractImage {#extractImage-java.lang.String-}
署名の画像を抽出します。

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

MDP 署名タイプによって認証されたドキュメントのアクセス許可値を返します。

**Returns:**
PdfException ドキュメントが認証されている場合はアクセス権限の値を返し、そうでない場合は例外がスローされます。 @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

空の署名フィールドのすべての名前を取得します。

**Returns:**
arrayList を返します。 @deprecated 代わりに GetBlankSignatureNames() を使用してください。

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
署名の連絡先情報を取得します。

### getContactInfo {#getContactInfo-java.lang.String-}
署名の連絡先情報を取得します。

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
署名の日付と時刻を取得します。

### getDateTime {#getDateTime-java.lang.String-}
署名の日付と時刻を取得します。

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
署名の場所を取得します。

### getLocation {#getLocation-java.lang.String-}
署名の場所を取得します。

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
署名の理由を取得します。

### getReason {#getReason-java.lang.String-}
署名の理由を取得します。

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
署名のリビジョンを取得します。

### getRevision {#getRevision-java.lang.String-}
署名のリビジョンを取得します。

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

署名のグラフィック外観を取得します。プロパティ値は画像ファイル名を表します。

**Returns:**
文字列値

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

署名のグラフィック外観を取得します。プロパティ値は画像ストリームを表します。

**Returns:**
InputStream 要素

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * 空でないすべての署名の名前を取得します。 / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
IList<SignatureName> を返します。 /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

空でないすべての署名の名前を取得します。 string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| onlyActive |  | true の場合はアクティブな署名のみを返し、false の場合はすべての署名を返します。 |

**Returns:**
IList<SignatureName> を返します。

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

PDFドキュメントに存在するすべての署名アルゴリズムに関する情報を取得します。

**Returns:**
各署名に関する情報を含む {@link SignatureAlgorithmInfo} インスタンスのリストです。

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
PDFドキュメントに署名する人物または組織の名前を取得します。

### getSignerName {#getSignerName-java.lang.String-}
PDFドキュメントに署名する人物または組織の名前を取得します。

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> 空でないすべての署名の名前を取得します。 </p> <hr>

**Returns:**
arrayList を返します。

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> 空でないすべての署名の名前を取得します。 </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| onlyActive |  | boolean 値。true の場合はアクティブな署名のみを返し、false の場合はすべての署名を返します。 |

**Returns:**
arrayList を返します。 @deprecated このメソッドは同じ署名名を生成する可能性があり、検証時に区別できません。代わりに getSignatureNames(boolean onlyActive) を使用してください。

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

総リビジョンを取得します。

**Returns:**
署名リビジョンの総数を返します。

### isCertified {#isCertified--}
```
public boolean isCertified()
```

ドキュメントが認証されているかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

PDF にデジタル署名があるかどうかを確認します。

**Returns:**
bool 型の結果を返します。

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
署名がドキュメント全体をカバーしているかどうかを確認します。

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

LTV有効フラグを取得します。

**Returns:**
ブール値

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
署名の名前に従って署名を削除します。 string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
署名の名前に従って署名を削除します。 string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> 署名の名前に従って署名を削除します。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> 署名の名前に従って署名を削除します。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

すべての署名を削除します。 string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

使用権エントリを削除します。

### save {#save--}
```
@Deprecated public void save()
```

署名済みPDFファイルを保存します。出力ファイル名は、対応するPdfFileSignatureコンストラクタを使用して事前に指定する必要があります。

### save {#save-java.io.OutputStream-}
署名済みPDFファイルを保存します。出力ファイル名は、対応するPdfFileSignatureコンストラクタを使用して事前に指定する必要があります。

### save {#save-java.lang.String-}
署名済みPDFファイルを保存します。出力ファイル名は、対応するPdfFileSignatureコンストラクタを使用して事前に指定する必要があります。

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
署名処理のために証明書ファイルとパスワードを設定します。

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
署名のグラフィック外観を設定します。プロパティ値は画像ファイル名を表します。

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
署名のグラフィック外観を設定します。プロパティ値は画像ストリームを表します。

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
指定されたタイプの署名でドキュメントに署名します。

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
PDFドキュメントに署名を作成します。

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
指定されたタイプの署名でドキュメントに署名します。

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
既に提示されている署名フィールドに配置された指定タイプの署名でドキュメントに署名します。

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> 既に提示されている署名フィールドに配置された指定タイプの署名でドキュメントに署名します。署名を行う前に署名フィールドは空である必要があります。つまり、フィールドに署名ディクショナリが含まれていてはいけません。そのため、PDFドキュメントにはすでに署名フィールドがあり、署名を配置する場所やページ、矩形を指定する必要はありません。これらは署名名（SigName パラメータ参照）で見つかる署名フィールドから取得されます。署名の理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティで提供する必要があります。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> 既に提示されている署名フィールドに配置された指定タイプの署名でドキュメントに署名します。署名を行う前に署名フィールドは空である必要があります。つまり、フィールドに署名ディクショナリが含まれていてはいけません。そのため、PDFドキュメントにはすでに署名フィールドがあり、署名を配置する場所やページ、矩形を指定する必要はありません。これらは署名名（SigName パラメータ参照）で見つかる署名フィールドから取得されます。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
署名の単一 X.509 証明書をストリームとして抽出します。

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
署名の単一 X.509 証明書を抽出します。

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
署名の有効性をチェックします。

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
署名の有効性をチェックします。

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
署名の有効性をチェックします。

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
署名の有効性をチェックします。

### verifySignature {#verifySignature-java.lang.String-}
署名の有効性をチェックします。

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
署名の有効性をチェックします。

### verifySigned {#verifySigned-java.lang.String-}
署名の有効性をチェックします。このメソッドは非推奨で、バージョン 25.1 で削除されます。代わりに VerifySignature メソッドを使用してください。
