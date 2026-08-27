---
title: "ドキュメント"
linktitle: "ドキュメント"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF 文書を表すクラス。"
type: docs
weight: 1060
url: /ja/java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Document

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class Document extends Object implements IDocument
```

PDF 文書を表すクラス。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | フォントが文書内で別のフォントに置き換えられたときに発生します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Document](#Document--) | 空のドキュメントを初期化します。 |
| [Document](#Document-byte:A-) | バイト配列 {@code input} から新しい Document インスタンスを初期化します。 |
| [Document](#Document-java.io.InputStream-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.io.InputStream-boolean-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.io.InputStream-java.lang.String-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 空のドキュメントを初期化します。 |
| [Document](#Document-com.aspose.pdf.PdfVersion-) | 空のドキュメントを初期化します。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-) | 空のドキュメントを初期化します。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-) | 空のドキュメントを初期化します。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | 空のドキュメントを初期化します。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 空のドキュメントを初期化します。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-boolean-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-java.lang.String-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-java.lang.String-boolean-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 空のドキュメントを初期化します。 |
| [Document](#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 空のドキュメントを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [afterImport](#afterImport--) | 登録されているすべてのアノテーションを列挙し、それぞれに対して AfterImport を呼び出します。 |
| [bindXml](#bindXml-java.io.InputStream-) | XML をドキュメントにバインドします |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | XML/XSL をドキュメントにバインドする |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | XML/XSL をドキュメントにバインドする |
| [bindXml](#bindXml-java.lang.String-) | XML をドキュメントにバインドします |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | XML/XSL をドキュメントにバインドする |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | ドキュメントのパスワードを変更します。この操作は所有者パスワードを使用してのみ実行できます。 |
| [check](#check-boolean-) | ドキュメントを検証する。 |
| [close](#close--) | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | ドキュメント内の画像を認識し、その上に hocr 文字列を追加します。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Fixup を適用してドキュメントを変換します。 |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Fixup を適用してドキュメントを変換します。 |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Fixup を適用してドキュメントを変換します。 |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Fixup を適用してドキュメントを変換します。 |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | ソース形式のストリームを宛先形式のストリームに変換します。 |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | ソース形式のストリームを宛先形式のファイルに変換します。 |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | ドキュメントを変換し、エラーを指定されたストリームに保存します。 |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | 指定された変換オプションを使用してドキュメントを変換する |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | ソース形式のソースファイルを宛先形式のストリームに変換します。 |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | ソース形式のソースファイルを宛先形式のファイルに変換します。 |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | ドキュメントを変換し、エラーを指定されたストリームに保存します。 |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | DSR、OMR、OCR 画像ストリーム用にページを PNG に変換します。 |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。 |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。 |
| [decrypt](#decrypt--) | ドキュメントを復号化します。次に Save を呼び出して、復号化されたバージョンのドキュメントを取得します。 |
| [dispose](#dispose--) | このドキュメントで使用されているすべてのリソースを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。 |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | ドキュメントを暗号化します。次に Save を呼び出して、暗号化されたバージョンのドキュメントを取得します。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | ドキュメントを暗号化します。次に Save を呼び出して、暗号化されたバージョンのドキュメントを取得します。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | ドキュメントを暗号化します。次に Save を呼び出して、暗号化されたバージョンのドキュメントを取得します。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | ドキュメントを暗号化する。 |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | すべてのドキュメント注釈をストリームにエクスポートします。 |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | すべてのドキュメント注釈を XFDF ファイルにエクスポートする |
| [flatten](#flatten--) | ドキュメントからすべてのフィールド（および注釈）を削除し、代わりにその値を配置する。 |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | ドキュメントからすべてのフィールド（および注釈）を削除し、代わりにその値を配置する。 |
| [flattenTransparency](#flattenTransparency--) | 透明なコンテンツを非透明のラスタおよびベクターグラフィックに置き換える。 |
| [freeMemory](#freeMemory--) | メモリをクリアする |
| [getAbsentFontHandler](#getAbsentFontHandler--) | ドキュメント処理中にフォントが見つからないことを通知します。 |
| [getActions](#getActions--) | <p> ドキュメントのアクションを取得します。このプロパティは DocumentActions クラスのインスタンスで、BeforClosing、BeforSaving などのアクションを取得/設定できます。 </p> |
| [getAllowReusePageContent](#getAllowReusePageContent--) | ページ内容をマージしてドキュメントサイズを最適化できるようにします。 |
| [getBackground](#getBackground--) | ドキュメントの背景色を取得する。 |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | カタログ辞書から項目の値を返す。 |
| [getCollection](#getCollection--) | ドキュメントのコレクションを取得する。 |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | ドキュメントが暗号化されている場合、セキュリティ設定を取得します。ドキュメントが暗号化されていない場合、.net 1.1 では対応する例外がスローされ、他の .net バージョンでは CryptoAlgorithm が null になります。 |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | カスタムセキュリティハンドラを取得する。 |
| [getDefaultCopier](#getDefaultCopier--) | このドキュメントにページをコピーするために使用されるコピー機能を返す。 |
| [getDestinations](#getDestinations--) | 宛先のコレクションを取得する。 |
| [getDirection](#getDirection--) | テキストの読み順を取得する：L2R（左から右）または R2L（右から左）。 |
| [getDuplex](#getDuplex--) | 印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。 |
| [getEmbeddedFiles](#getEmbeddedFiles--) | ドキュメントに埋め込まれたファイルのコレクションを取得します。 |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。 |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | 署名フィールドのサニタイズを管理するフラグを取得または設定します。 |
| [getEngineDoc](#getEngineDoc--) | 内部ドキュメント構造にアクセスするために使用される IPdfDocument のインスタンスです。内部専用です。 |
| [getFileName](#getFileName--) | このドキュメントを引き起こした PDF ファイルの名前 |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | ファイル全体をメモリにロードする際のファイルサイズ上限を取得および設定します。 |
| [getFontUtilities](#getFontUtilities--) | IDocumentFontUtilities のインスタンス |
| [getForm](#getForm--) | ドキュメントの Acro Form を取得します。 |
| [getId](#getId--) | ID を取得します。 |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | ソースファイルのエラーを無視するかどうかのフラグを取得または設定します。このフラグが false の場合、ソースドキュメントからページが宛先ドキュメントにコピーされる際に、ソースファイル内のオブジェクトが破損していると例外でコピー処理が中止されます。例: dest.Pages.Add(src.Pages); フラグが true に設定されていると、破損したオブジェクトは空の値で置き換えられます。デフォルト: true。 |
| [getInfo](#getInfo--) | ドキュメント情報を取得します。 |
| [getJavaScript](#getJavaScript--) | ドキュメントレベルの JavaScript コレクションです。 |
| [getLogicalStructure](#getLogicalStructure--) | ドキュメントの論理構造を取得します。 |
| [getMetadata](#getMetadata--) | ドキュメントのメタデータです。（PDF ドキュメントには、タイトル、著者、作成日や変更日などの一般情報が含まれることがあります。このようなドキュメントに関する全体的な情報（コンテンツや構造とは対照的に）はメタデータと呼ばれ、外部データベースでのカタログ化や検索を支援することを目的としています。） |
| [getMetadataStream](#getMetadataStream--) | 生のメタデータストリームを返します |
| [getNamedDestinations](#getNamedDestinations--) | ドキュメント内の名前付きデスティネーションのコレクションです。 |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | 全画面モードを終了したときにドキュメントを表示する方法を指定するページモードを取得します。 |
| [getObjectById](#getObjectById-java.lang.String-) | ドキュメント内で指定された ID を持つオブジェクトを取得します。 |
| [getOpenAction](#getOpenAction--) | <p> ドキュメントを開く際に実行されるアクションを取得します。 </p> <hr> <pre> 例では CenterWindow フラグの取得方法を示しています: Document document = new Document(\"sample.pdf\"); IAppointment value = document.getOpenAction(); </pre> |
| [getOptimizeSize](#getOptimizeSize--) | 最適化フラグを取得します。ページがドキュメントに追加されるとき、このフラグが設定されている場合、結果ファイル内の同一リソースストリームが 1 つの PDF オブジェクトにマージされます。これにより結果ファイルのサイズを減らすことができますが、実行が遅くなりメモリ使用量が増える可能性があります。デフォルト値: false。 |
| [getOutlines](#getOutlines--) | ドキュメントのアウトラインを取得します。 |
| [getOutputIntents](#getOutputIntents--) | ドキュメント内の Output intents コレクションを取得します。 |
| [getPageInfo](#getPageInfo--) | ページ情報を取得します。（生成時のみ、ドキュメント読み取り時には設定されません） |
| [getPageLabels](#getPageLabels--) | ドキュメント内のページラベルを取得します。 |
| [getPageLayout](#getPageLayout--) | ドキュメントが開かれたときに使用されるページレイアウトを取得します。 |
| [getPageMode](#getPageMode--) | ドキュメントが開かれたときにどのように表示されるかを指定するページモードを取得します。 |
| [getPages](#getPages--) | <p> ドキュメントページのコレクションを取得します。コレクション内のページは 1 から番号付けされていることに注意してください。 </p> |
| [getPdfFormat](#getPdfFormat--) | PDF/A 形式を取得します |
| [getPermissions](#getPermissions--) | ドキュメントの権限を取得します。 |
| [getPrintScaling](#getPrintScaling--) | 印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを取得します。 |
| [getTaggedContent](#getTaggedContent--) | TaggedPdf コンテンツへのアクセスを取得します。以下の例は、ヘッダー、段落、画像を含む新しいドキュメントを作成するためにタグ付けされたコンテンツを使用する方法を示しています。 // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage(\"en-US\"); // Set title for PDF document taggedContent.setTitle(\"Example document\"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText(\"The Header\"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag(\"Paragraph\"); p.setText(\"The text of paragraph.\"); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText(\"Figure 1\"); figure1.setTitle(\"Image 1\"); figure1.setTag(\"Fig\"); figure1.setImage(\"path/of/image.jpg\"); // Save document document.save(\"example.pdf\"); |
| [getVersion](#getVersion--) | Pdf ファイルヘッダーから Pdf のバージョンを取得します。 |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | ドキュメントから XMP メタデータを取得します。 |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | 現在の PDF ドキュメントが増分更新で保存されているかどうかを確認します。 |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | ストリームからドキュメントへ注釈をインポートします。 |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | XFDF ファイルからドキュメントへ注釈をインポートします。 |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | 欠落フォントの置換について通知するフラグです。 |
| [isCenterWindow](#isCenterWindow--) | <p> ドキュメントウィンドウの位置が画面の中央に配置されるかどうかを指定するフラグを取得します。 </p> |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。 |
| [isDisplayDocTitle](#isDisplayDocTitle--) | <p> ドキュメントのウィンドウタイトルバーにドキュメントタイトルを表示するかどうかを指定するフラグを取得します。 </p> |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | 通知のロギングを有効にするかどうかを示す値を取得または設定します。 |
| [isEnableObjectUnload](#isEnableObjectUnload--) | ドキュメントをメモリから部分的にアンロードできるようにするフラグを取得または設定します。 |
| [isEncrypted](#isEncrypted--) | ドキュメントの暗号化ステータスを取得します。暗号化されている場合は true です。 |
| [isFitWindow](#isFitWindow--) | <p> 最初に表示されるページに合わせてドキュメントウィンドウのサイズを変更するかどうかを指定するフラグを取得します。 </p> |
| [isHandleSignatureChange](#isHandleSignatureChange--) | 変更が加えられ、署名がある状態でドキュメントを保存しようとした場合、例外をスローします。 |
| [isHideMenubar](#isHideMenubar--) | <p> ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを指定するフラグを取得します。 </p> |
| [isHideToolBar](#isHideToolBar--) | <p> ドキュメントがアクティブなときにツールバーを非表示にするかどうかを指定するフラグを取得します。 </p> |
| [isHideWindowUI](#isHideWindowUI--) | <p> ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを指定するフラグを取得します。 </p> |
| [isLicensed](#isLicensed--) | システムのライセンス状態を取得します。 |
| [isLinearized](#isLinearized--) | ドキュメントがリニアライズされているかどうかを示す値を取得します。 |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | デフォルトでは、save メソッドは内部ストリームを閉じ、メモリリソースを解放します。この ManualDispose パラメータが有効な場合、save メソッドの後でもいくつかの操作を行い、ドキュメントの作業を続行できます。 |
| [isPdfaCompliant](#isPdfaCompliant--) | ドキュメントが PDF/A に準拠しているかどうかを取得します。 |
| [isPdfUaCompliant](#isPdfUaCompliant--) | ドキュメントが PDF/UA に準拠しているかどうかを取得します。 |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | PDF ページサイズを入力用紙トレイの選択に使用するかどうかを示すフラグを取得します。 |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | ドキュメントが Repair メソッドの呼び出しを必要とするかどうかをチェックします。 |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | デフォルトでは、いくつかの規則が破られた場合に PDF/A 準拠データを更新または削除するために PDF/A 検証プロセスが必要です。 |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | ドキュメントが PDF/A に準拠しているかどうかを取得または設定します。 |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | ファイルを読み込み、PDF に変換します。 |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | ドキュメントを結合します。 |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | ドキュメントを結合します。 |
| [merge](#merge-com.aspose.pdf.Document...-) | ドキュメントを結合します。 |
| [merge](#merge-java.lang.String...-) | PDF ファイルを結合します。 |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | ドキュメントを結合します。 |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | ドキュメントを結合します。 |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | ドキュメントを結合します。 |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | PDF ファイルを結合します。 |
| [optimize](#optimize--) | ドキュメントをリニアライズする目的は、- 最初のページをできるだけ早く開くこと、- 次のページや次のページへのリンクをできるだけ早く表示すること、- ページデータが遅いチャネルで届く際にページを段階的に表示すること（最も有用なデータを先に表示）、- リンクのクリックなどのユーザー操作を、ページ全体が受信・表示される前に実行できるようにすることです。このメソッドを呼び出しても実際にはドキュメントは保存されません。むしろ、ドキュメントは最適化された構造になるように準備されるだけです。最適化されたドキュメントを取得するには、Save を呼び出してください。 |
| [optimizeResources](#optimizeResources--) | ドキュメント内のリソースを最適化します：1. ドキュメントページで使用されていないリソースは削除されます；2. 同一のリソースは1つのオブジェクトに結合されます；3. 未使用のオブジェクトは削除されます。 |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | ドキュメント内のリソースを最適化します：1. ドキュメントページで使用されていないリソースは削除されます；2. 同一のリソースは1つのオブジェクトに結合されます；3. 未使用のオブジェクトは削除されます。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | ドキュメント内のページツリーノードをバランスツリーに整理します。ドキュメントが nodesNumInSubtrees 以上のページオブジェクトを持つ場合にのみ実行され、そうでなければ何もしません。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | ドキュメント内のページツリーノードをバランスツリーに整理します。ドキュメントが nodesNumInSubtrees 以上のページオブジェクトを持つ場合にのみ実行され、そうでなければ何もしません。 |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | 内部メソッド |
| [processParagraphs](#processParagraphs--) | ドキュメントをストリームに保存します。 |
| [removeMetadata](#removeMetadata--) | ドキュメントからメタデータを削除します。 |
| [removePdfaCompliance](#removePdfaCompliance--) | ドキュメントから PDF/A 準拠を削除します |
| [removePdfUaCompliance](#removePdfUaCompliance--) | ドキュメントから PDF/UA 準拠を削除します |
| [repair](#repair--) | 破損したドキュメントを修復します。 |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | 破損したドキュメントを修復します。 |
| [resumeUpdate](#resumeUpdate--) | ドキュメントの更新を再開します |
| [save](#save--) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [save](#save-java.io.OutputStream-) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [save](#save-com.aspose.pdf.SaveOptions-) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [save](#save-com.aspose.ms.System.IO.Stream-) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [save](#save-java.lang.String-) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | <p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。 |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveXml](#saveXml-java.lang.String-) | ドキュメントを XML に保存します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | ドキュメントの特定のページを処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | ドキュメント処理中にフォントが見つからないことを通知します。 |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | フォントが存在しない場合にプログラムが決定したフォントを設定するフラグを設定します。 |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | ページ内容をマージしてドキュメントサイズを最適化できるようにします。 |
| [setBackground](#setBackground-java.awt.Color-) | ドキュメントの背景色を設定します。 |
| [setCenterWindow](#setCenterWindow-boolean-) | ドキュメントウィンドウの位置を画面の中央に配置するかどうかを指定するフラグを設定します。 |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | ドキュメントのコレクションを設定します。 |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | pdf/ua コンバータの変換パラメータを取得します（true に設定するとメタデータとドキュメントカタログのみ変換します） |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | メモリにファイル全体をロードする際のファイルサイズ上限をデフォルト値の210 MBに設定します。 |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | テキストの読み順を設定します：L2R（左から右）または R2L（右から左）。 |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。 |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | ドキュメントウィンドウのタイトルバーにドキュメントタイトルを表示するかどうかを指定するフラグを設定します。 |
| [setDuplex](#setDuplex-int-) | 印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。 |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。 |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | 通知のロギングを有効にするかどうかを示す値を取得または設定します。 |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | ドキュメントをメモリから部分的にアンロードできるようにするフラグを取得または設定します。 |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | 署名フィールドのサニタイズを管理するフラグを取得または設定します。 |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | ファイル全体をメモリにロードする際のファイルサイズ上限を取得および設定します。 |
| [setFitWindow](#setFitWindow-boolean-) | 最初に表示されたページに合わせてドキュメントウィンドウのサイズを変更するかどうかを指定するフラグを設定します。 |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | 変更が加えられ、署名がある状態でドキュメントを保存しようとした場合、例外をスローします。 |
| [setHideMenubar](#setHideMenubar-boolean-) | ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを指定するフラグを設定します。 |
| [setHideToolBar](#setHideToolBar-boolean-) | ドキュメントがアクティブなときにツールバーを非表示にするかどうかを指定するフラグを設定します。 |
| [setHideWindowUI](#setHideWindowUI-boolean-) | ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを指定するフラグを設定します。 |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | ソースファイルのエラーを無視するかどうかのフラグを取得または設定します。このフラグが false の場合、ソースドキュメントからページが宛先ドキュメントにコピーされる際に、ソースファイル内のオブジェクトが破損していると例外でコピー処理が中止されます。例: dest.Pages.Add(src.Pages); フラグが true に設定されていると、破損したオブジェクトは空の値で置き換えられます。デフォルト: true。 |
| [setLinearized](#setLinearized-boolean-) | ドキュメントがリニアライズされているかどうかを示す値を設定します。 |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | デフォルトでは、save メソッドは内部ストリームを閉じ、メモリリソースを解放します。ManualDispose パラメータが有効な場合、save メソッドが呼び出された後でもいくつかの操作を行い、ドキュメントの作業を続行できます。ただし、Document インスタンスが不要になった時点で dispose メソッドを呼び出すことが強く推奨されます。 |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | ページモードを設定し、全画面モードを終了したときにドキュメントをどのように表示するかを指定します。 |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | <p> ドキュメントを開く際に実行されるアクションを設定します。 <p> |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 最適化フラグを設定します。このフラグが設定されている場合、ページがドキュメントに追加されると、結果ファイル内の同等のリソースストリームが1つの PDF オブジェクトに統合されます。これにより結果ファイルのサイズを削減できますが、実行が遅くなり、メモリ要件が増加する可能性があります。デフォルト値: false. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | ページ情報を設定します。（ジェネレータ専用で、ドキュメントを読み込む際には設定されません） |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | ドキュメントが開かれたときに使用されるページレイアウトを設定します。 |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | ページモードを設定し、開いたときにドキュメントをどのように表示するかを指定します。 |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | PDF ページサイズを使用して入力用紙トレイを選択するかどうかを指定するフラグを設定します。 |
| [setPrintScaling](#setPrintScaling-int-) | 印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを設定します。 |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | デフォルトでは、規則が破られた場合に pdfp を更新または削除するために pdfp 検証プロセスが必要です。 |
| [setTitle](#setTitle-java.lang.String-) | Pdf Document のタイトルを設定します。 |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | ドキュメントの XMP メタデータを設定します。 |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | ドキュメントが PDF/A に準拠しているかどうかを取得または設定します。 |
| [suppressUpdate](#suppressUpdate--) | すべてのページのコンテンツデータの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツは更新されません。 |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | ドキュメントを指定されたファイルに検証します。 |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | ドキュメントを指定されたファイルに検証します。 |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | ドキュメントを指定されたファイルに検証します。 |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

フォントが文書内で別のフォントに置き換えられたときに発生します。

### Document {#Document--}
```
public Document()
```

空のドキュメントを初期化します。

### Document {#Document-byte:A-}
```
public Document(byte[] input)
```

バイト配列 {@code input} から新しい Document インスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 入力 |  | PDF ドキュメントを含むバイト配列。 |

### Document {#Document-java.io.InputStream-}
空のドキュメントを初期化します。

### Document {#Document-java.io.InputStream-boolean-}
空のドキュメントを初期化します。

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
空のドキュメントを初期化します。

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
空のドキュメントを初期化します。

### Document {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
空のドキュメントを初期化します。

### Document {#Document-java.io.InputStream-java.lang.String-}
空のドキュメントを初期化します。

### Document {#Document-java.io.InputStream-java.lang.String-boolean-}
空のドキュメントを初期化します。

### Document {#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
空のドキュメントを初期化します。

### Document {#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
空のドキュメントを初期化します。

### Document {#Document-com.aspose.pdf.PdfVersion-}
空のドキュメントを初期化します。

### Document {#Document-com.aspose.ms.System.IO.Stream-}
空のドキュメントを初期化します。

### Document {#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-}
空のドキュメントを初期化します。

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
空のドキュメントを初期化します。

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
空のドキュメントを初期化します。

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-boolean-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-java.lang.String-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-java.lang.String-boolean-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
空のドキュメントを初期化します。

### Document {#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
空のドキュメントを初期化します。

### afterImport {#afterImport--}
```
public void afterImport()
```

登録されているすべてのアノテーションを列挙し、それぞれに対して AfterImport を呼び出します。

### bindXml {#bindXml-java.io.InputStream-}
XML をドキュメントにバインドします

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
XML/XSL をドキュメントにバインドする

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
XML/XSL をドキュメントにバインドする

### bindXml {#bindXml-java.lang.String-}
XML をドキュメントにバインドします

### bindXml {#bindXml-java.lang.String-java.lang.String-}
XML/XSL をドキュメントにバインドする

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
ドキュメントのパスワードを変更します。この操作は所有者パスワードを使用してのみ実行できます。

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

ドキュメントを検証する。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| doRepair |  | true の場合、検出された問題が修復されます。 |

**Returns:**
ブール値

### close {#close--}
```
public void close()
```

このドキュメントで使用されているすべてのリソースを閉じます。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
ドキュメント内の画像を認識し、その上に hocr 文字列を追加します。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Fixup を適用してドキュメントを変換します。

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Fixup を適用してドキュメントを変換します。

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Fixup を適用してドキュメントを変換します。

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Fixup を適用してドキュメントを変換します。

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
ソース形式のストリームを宛先形式のストリームに変換します。

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
ソース形式のストリームを宛先形式のファイルに変換します。

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
ドキュメントを変換し、エラーを指定されたストリームに保存します。

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
指定された変換オプションを使用してドキュメントを変換する

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
ソース形式のソースファイルを宛先形式のストリームに変換します。

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
ソース形式のソースファイルを宛先形式のファイルに変換します。

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
ドキュメントを変換し、エラーを指定されたストリームに保存します。

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
DSR、OMR、OCR 画像ストリーム用にページを PNG に変換します。

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。

### decrypt {#decrypt--}
```
public void decrypt()
```

ドキュメントを復号化します。次に Save を呼び出して、復号化されたバージョンのドキュメントを取得します。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

このドキュメントで使用されているすべてのリソースを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
ドキュメントを暗号化する。

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
ドキュメントを暗号化します。次に Save を呼び出して、暗号化されたバージョンのドキュメントを取得します。

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
ドキュメントを暗号化する。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
ドキュメントを暗号化します。次に Save を呼び出して、暗号化されたバージョンのドキュメントを取得します。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
ドキュメントを暗号化します。次に Save を呼び出して、暗号化されたバージョンのドキュメントを取得します。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
ドキュメントを暗号化する。

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
すべてのドキュメント注釈をストリームにエクスポートします。

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
すべてのドキュメント注釈を XFDF ファイルにエクスポートする

### flatten {#flatten--}
```
public void flatten()
```

ドキュメントからすべてのフィールド（および注釈）を削除し、代わりにその値を配置する。

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
ドキュメントからすべてのフィールド（および注釈）を削除し、代わりにその値を配置する。

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

透明なコンテンツを非透明のラスタおよびベクターグラフィックに置き換える。

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

メモリをクリアする

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

ドキュメント処理中にフォントが見つからないことを通知します。

**Returns:**
ADocument.AbsentFontHandler インスタンス

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

<p> ドキュメントのアクションを取得します。このプロパティは DocumentActions クラスのインスタンスで、BeforClosing、BeforSaving などのアクションを取得/設定できます。 </p>

**Returns:**
DocumentActionCollection オブジェクト <hr> <pre> この例は、ドキュメントのオープン後アクションを取得する方法を示します: Document document = new Document("PdfWithOpenAction.pdf"); DocumentActionCollection actions = document.getActions(); PdfAction afterSavingAction = actions.getAfterSaving(); </pre>

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

ページ内容をマージしてドキュメントサイズを最適化できるようにします。

**Returns:**
value ブール値

### getBackground {#getBackground--}
```
public Color getBackground()
```

ドキュメントの背景色を取得する。

**Returns:**
Color オブジェクト

### getCatalogValue {#getCatalogValue-java.lang.String-}
カタログ辞書から項目の値を返す。

### getCollection {#getCollection--}
```
public Collection getCollection()
```

ドキュメントのコレクションを取得する。

**Returns:**
Collection オブジェクト

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

ドキュメントが暗号化されている場合、セキュリティ設定を取得します。ドキュメントが暗号化されていない場合、.net 1.1 では対応する例外がスローされ、他の .net バージョンでは CryptoAlgorithm が null になります。

**Returns:**
CryptoAlgorithm 要素 @see CryptoAlgorithm

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public final com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

カスタムセキュリティハンドラを取得する。

**Returns:**
ICustomSecurityHandler インスタンス

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

このドキュメントにページをコピーするために使用されるコピー機能を返す。

**Returns:**
Copier オブジェクト

### getDestinations {#getDestinations--}
```
public DestinationCollection getDestinations()
```

宛先のコレクションを取得する。

**Returns:**
DestinationCollection 要素

### getDirection {#getDirection--}
```
public Direction getDirection()
```

テキストの読み順を取得する：L2R（左から右）または R2L（右から左）。

**Returns:**
Direction 要素 @see Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。

**Returns:**
PrintDuplex 要素

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

ドキュメントに埋め込まれたファイルのコレクションを取得します。

**Returns:**
EmbeddedFileCollection オブジェクト

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。

**Returns:**
ブール値

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

署名フィールドのサニタイズを管理するフラグを取得または設定します。

**Returns:**
ブール値

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

内部ドキュメント構造にアクセスするために使用される IPdfDocument のインスタンスです。内部専用です。

**Returns:**
IPdfDocument オブジェクト

### getFileName {#getFileName--}
```
public String getFileName()
```

このドキュメントを引き起こした PDF ファイルの名前

**Returns:**
String オブジェクト

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

ファイル全体をメモリにロードする際のファイルサイズ上限を取得および設定します。

**Returns:**
int 値です。

### getFontUtilities {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```

IDocumentFontUtilities のインスタンス

**Returns:**
IDocumentFontUtilities のインスタンス

### getForm {#getForm--}
```
public Form getForm()
```

ドキュメントの Acro Form を取得します。

**Returns:**
Form オブジェクト

### getId {#getId--}
```
public Id getId()
```

ID を取得します。

**Returns:**
Id オブジェクト

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

ソースファイルのエラーを無視するかどうかのフラグを取得または設定します。このフラグが false の場合、ソースドキュメントからページが宛先ドキュメントにコピーされる際に、ソースファイル内のオブジェクトが破損していると例外でコピー処理が中止されます。例: dest.Pages.Add(src.Pages); フラグが true に設定されていると、破損したオブジェクトは空の値で置き換えられます。デフォルト: true。

**Returns:**
ブール値

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

ドキュメント情報を取得します。

**Returns:**
DocumentInfo オブジェクト

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

ドキュメントレベルの JavaScript コレクションです。

**Returns:**
JavaScriptCollection オブジェクト

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

ドキュメントの論理構造を取得します。

**Returns:**
RootElement オブジェクト

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

ドキュメントのメタデータです。（PDF ドキュメントには、タイトル、著者、作成日や変更日などの一般情報が含まれることがあります。このようなドキュメントに関する全体的な情報（コンテンツや構造とは対照的に）はメタデータと呼ばれ、外部データベースでのカタログ化や検索を支援することを目的としています。）

**Returns:**
Metadata オブジェクト

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

生のメタデータストリームを返します

**Returns:**
IPdfStreamAccessor オブジェクト

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

ドキュメント内の名前付きデスティネーションのコレクションです。

**Returns:**
NamedDestinationCollection インスタンス

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

全画面モードを終了したときにドキュメントを表示する方法を指定するページモードを取得します。

**Returns:**
PageMode 要素 @see PageMode

### getObjectById {#getObjectById-java.lang.String-}
ドキュメント内で指定された ID を持つオブジェクトを取得します。

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

<p> ドキュメントを開く際に実行されるアクションを取得します。 </p> <hr> <pre> 例では CenterWindow フラグの取得方法を示しています: Document document = new Document(\"sample.pdf\"); IAppointment value = document.getOpenAction(); </pre>

**Returns:**
IAppointment オブジェクト

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

最適化フラグを取得します。ページがドキュメントに追加されるとき、このフラグが設定されている場合、結果ファイル内の同一リソースストリームが 1 つの PDF オブジェクトにマージされます。これにより結果ファイルのサイズを減らすことができますが、実行が遅くなりメモリ使用量が増える可能性があります。デフォルト値: false。

**Returns:**
ブール値

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

ドキュメントのアウトラインを取得します。

**Returns:**
OutlineCollection オブジェクト

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

ドキュメント内の Output intents コレクションを取得します。

**Returns:**
OutputIntents インスタンス

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

ページ情報を取得します。（生成時のみ、ドキュメント読み取り時には設定されません）

**Returns:**
ページ情報です。

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

ドキュメント内のページラベルを取得します。

**Returns:**
PageLabelCollection オブジェクト

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

ドキュメントが開かれたときに使用されるページレイアウトを取得します。

**Returns:**
PageLayout 要素 @see PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

ドキュメントが開かれたときにどのように表示されるかを指定するページモードを取得します。

**Returns:**
PageMode 要素 @see PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

<p> ドキュメントページのコレクションを取得します。コレクション内のページは 1 から番号付けされていることに注意してください。 </p>

**Returns:**
PageCollection オブジェクト <hr> <pre> 以下の例は、ドキュメントページを操作する方法を示します: ページ数の取得方法とドキュメントの開始ページの矩形を取得する方法。 Document document = new Document("sample.pdf"); PageCollection pages = document.getPages(); System.out.println("Document contains " + pages.size()); Page page = pages.get_Item(1); Rectangle rect = page.getRect(); </pre>

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

PDF/A 形式を取得します

**Returns:**
PdfFormat 要素 @see PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

ドキュメントの権限を取得します。

**Returns:**
int 値です。

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを取得します。

**Returns:**
PrintScaling 要素

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```

TaggedPdf コンテンツへのアクセスを取得します。以下の例は、ヘッダー、段落、画像を含む新しいドキュメントを作成するためにタグ付けされたコンテンツを使用する方法を示しています。 // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage(\"en-US\"); // Set title for PDF document taggedContent.setTitle(\"Example document\"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText(\"The Header\"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag(\"Paragraph\"); p.setText(\"The text of paragraph.\"); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText(\"Figure 1\"); figure1.setTitle(\"Image 1\"); figure1.setTag(\"Fig\"); figure1.setImage(\"path/of/image.jpg\"); // Save document document.save(\"example.pdf\");

**Returns:**
ITaggedContent インスタンス

### getVersion {#getVersion--}
```
public String getVersion()
```

Pdf ファイルヘッダーから Pdf のバージョンを取得します。

**Returns:**
文字列値

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
ドキュメントから XMP メタデータを取得します。

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

現在の PDF ドキュメントが増分更新で保存されているかどうかを確認します。

**Returns:**
PDF ドキュメントに増分更新がある場合は true、そうでない場合は false。

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
ストリームからドキュメントへ注釈をインポートします。

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
XFDF ファイルからドキュメントへ注釈をインポートします。

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

欠落フォントの置換について通知するフラグです。

**Returns:**
ブール値

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

<p> ドキュメントウィンドウの位置が画面の中央に配置されるかどうかを指定するフラグを取得します。 </p>

**Returns:**
ブール値 <hr> <pre> この例は CenterWindow フラグの取得方法を示します: Document document = new Document("sample.pdf"); boolean value = document.isCenterWindow(); </pre>

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。

**Returns:**
ブール値 デフォルトは false。

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

<p> ドキュメントのウィンドウタイトルバーにドキュメントタイトルを表示するかどうかを指定するフラグを取得します。 </p>

**Returns:**
ブール値 <hr> <pre> この例は DisplayDocTitle フラグの取得方法を示します: Document document = new Document("sample.pdf"); boolean value = document.isDisplayDocTitle(); </pre>

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

通知のロギングを有効にするかどうかを示す値を取得または設定します。

**Returns:**
ブール値

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

ドキュメントをメモリから部分的にアンロードできるようにするフラグを取得または設定します。

**Returns:**
ブール値

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

ドキュメントの暗号化ステータスを取得します。暗号化されている場合は true です。

**Returns:**
ブール値

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

<p> 最初に表示されるページに合わせてドキュメントウィンドウのサイズを変更するかどうかを指定するフラグを取得します。 </p>

**Returns:**
ブール値 <hr> <pre> この例は FitWindow フラグの取得方法を示します: Document document = new Document("sample.pdf"); boolean value = document.isFitWindow(); </pre>

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

変更が加えられ、署名がある状態でドキュメントを保存しようとした場合、例外をスローします。

**Returns:**
ブール値

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

<p> ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを指定するフラグを取得します。 </p>

**Returns:**
ブール値 <hr> <pre> この例は HideMenubar フラグの取得方法を示します: Document document = new Document("sample.pdf"); boolean value = document.isHideMenubar(); </pre>

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

<p> ドキュメントがアクティブなときにツールバーを非表示にするかどうかを指定するフラグを取得します。 </p>

**Returns:**
ブール値 <hr> <pre> 例では HideToolBar フラグの取得方法を示しています: Document document = new Document("sample.pdf"); boolean value = document.isHideToolBar(); </pre>

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

<p> ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを指定するフラグを取得します。 </p>

**Returns:**
ブール値 <hr> <pre> 例では HideWindowUI フラグの取得方法を示しています: Document document = new Document("sample.pdf"); boolean value = document.isHideWindowUI(); </pre>

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

システムのライセンス状態を取得します。

**Returns:**
ブール値

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

ドキュメントがリニアライズされているかどうかを示す値を取得します。

**Returns:**
ブール値

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

デフォルトでは、save メソッドは内部ストリームを閉じ、メモリリソースを解放します。この ManualDispose パラメータが有効な場合、save メソッドの後でもいくつかの操作を行い、ドキュメントの作業を続行できます。

**Returns:**
ブール値。 (デフォルト値 == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

ドキュメントが PDF/A に準拠しているかどうかを取得します。

**Returns:**
ブール値

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

ドキュメントが PDF/UA に準拠しているかどうかを取得します。

**Returns:**
ブール値

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

PDF ページサイズを入力用紙トレイの選択に使用するかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
ドキュメントが Repair メソッドの呼び出しを必要とするかどうかをチェックします。

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

デフォルトでは、いくつかの規則が破られた場合に PDF/A 準拠データを更新または削除するために PDF/A 検証プロセスが必要です。

**Returns:**
ブール値

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

ドキュメントが PDF/A に準拠しているかどうかを取得または設定します。

**Returns:**
ブール値

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
ファイルを読み込み、PDF に変換します。

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
ドキュメントを結合します。

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
ドキュメントを結合します。

### merge {#merge-com.aspose.pdf.Document...-}
ドキュメントを結合します。

### merge {#merge-java.lang.String...-}
PDF ファイルを結合します。

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
ドキュメントを結合します。

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
ドキュメントを結合します。

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
ドキュメントを結合します。

### mergeDocuments {#mergeDocuments-java.lang.String...-}
PDF ファイルを結合します。

### optimize {#optimize--}
```
public void optimize()
```

ドキュメントをリニアライズする目的は、- 最初のページをできるだけ早く開くこと、- 次のページや次のページへのリンクをできるだけ早く表示すること、- ページデータが遅いチャネルで届く際にページを段階的に表示すること（最も有用なデータを先に表示）、- リンクのクリックなどのユーザー操作を、ページ全体が受信・表示される前に実行できるようにすることです。このメソッドを呼び出しても実際にはドキュメントは保存されません。むしろ、ドキュメントは最適化された構造になるように準備されるだけです。最適化されたドキュメントを取得するには、Save を呼び出してください。

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

ドキュメント内のリソースを最適化します：1. ドキュメントページで使用されていないリソースは削除されます；2. 同一のリソースは1つのオブジェクトに結合されます；3. 未使用のオブジェクトは削除されます。

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
ドキュメント内のリソースを最適化します：1. ドキュメントページで使用されていないリソースは削除されます；2. 同一のリソースは1つのオブジェクトに結合されます；3. 未使用のオブジェクトは削除されます。

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

ドキュメント内のページツリーノードをバランスツリーに整理します。ドキュメントが nodesNumInSubtrees 以上のページオブジェクトを持つ場合にのみ実行され、そうでなければ何もしません。

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

ドキュメント内のページツリーノードをバランスツリーに整理します。ドキュメントが nodesNumInSubtrees 以上のページオブジェクトを持つ場合にのみ実行され、そうでなければ何もしません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| nodesNumInSubtrees |  | サブノードの希望数。 |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
内部メソッド

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

ドキュメントをストリームに保存します。

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

ドキュメントからメタデータを削除します。

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

ドキュメントから PDF/A 準拠を削除します

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

ドキュメントから PDF/UA 準拠を削除します

### repair {#repair--}
```
public void repair()
```

破損したドキュメントを修復します。

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
破損したドキュメントを修復します。

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

ドキュメントの更新を再開します

### save {#save--}
```
public void save()
```

<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### save {#save-java.io.OutputStream-}
<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### save {#save-com.aspose.pdf.SaveOptions-}
<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### save {#save-com.aspose.ms.System.IO.Stream-}
<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### save {#save-java.lang.String-}
<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
<p> ドキュメントをインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 </p> <hr> <p> インクリメンタルにドキュメントを保存するには、書き込み用にドキュメントファイルを開く必要があります。そのため、Document は InputStream ではなくファイルパスで初期化する必要があります。次のコードスニペットのように： Document doc = new Document(\"document.pdf\"); // 変更を加えてドキュメントをインクリメンタルに保存 doc.save(); </p> Document が InputStream で初期化されている場合、InputStream への書き込みは不可能なため、ドキュメントを保存するには \"save\" メソッド、インクリメンタルに保存するには \"saveIncrementally\" メソッドの使用を推奨します。

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。

### saveIncrementally {#saveIncrementally-java.lang.String-}
PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。

### saveXml {#saveXml-java.lang.String-}
ドキュメントを XML に保存します。

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
ドキュメントの特定のページを処理用にドキュメントデバイスへ送信します。

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
ドキュメント全体を処理用にドキュメントデバイスへ送信します。

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
ドキュメント全体を処理用にドキュメントデバイスへ送信します。

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
ドキュメント全体を処理用にドキュメントデバイスへ送信します。

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
ドキュメント処理中にフォントが見つからないことを通知します。

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

フォントが存在しない場合にプログラムが決定したフォントを設定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  |  |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

ページ内容をマージしてドキュメントサイズを最適化できるようにします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBackground {#setBackground-java.awt.Color-}
ドキュメントの背景色を設定します。

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

ドキュメントウィンドウの位置を画面の中央に配置するかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
ドキュメントのコレクションを設定します。

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

pdf/ua コンバータの変換パラメータを取得します（true に設定するとメタデータとドキュメントカタログのみ変換します）

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

メモリにファイル全体をロードする際のファイルサイズ上限をデフォルト値の210 MBに設定します。

### setDirection {#setDirection-com.aspose.pdf.Direction-}
テキストの読み順を設定します：L2R（左から右）または R2L（右から左）。

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 デフォルトは false。 |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

ドキュメントウィンドウのタイトルバーにドキュメントタイトルを表示するかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PrintDuplex 要素 |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

通知のロギングを有効にするかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

ドキュメントをメモリから部分的にアンロードできるようにするフラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

署名フィールドのサニタイズを管理するフラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

ファイル全体をメモリにロードする際のファイルサイズ上限を取得および設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

最初に表示されたページに合わせてドキュメントウィンドウのサイズを変更するかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

変更が加えられ、署名がある状態でドキュメントを保存しようとした場合、例外をスローします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

ドキュメントがアクティブなときにツールバーを非表示にするかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

ソースファイルのエラーを無視するかどうかのフラグを取得または設定します。このフラグが false の場合、ソースドキュメントからページが宛先ドキュメントにコピーされる際に、ソースファイル内のオブジェクトが破損していると例外でコピー処理が中止されます。例: dest.Pages.Add(src.Pages); フラグが true に設定されていると、破損したオブジェクトは空の値で置き換えられます。デフォルト: true。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

ドキュメントがリニアライズされているかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

デフォルトでは、save メソッドは内部ストリームを閉じ、メモリリソースを解放します。ManualDispose パラメータが有効な場合、save メソッドが呼び出された後でもいくつかの操作を行い、ドキュメントの作業を続行できます。ただし、Document インスタンスが不要になった時点で dispose メソッドを呼び出すことが強く推奨されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| manualDisposeEnabled |  | ブール値。 (デフォルト値 == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
ページモードを設定し、全画面モードを終了したときにドキュメントをどのように表示するかを指定します。

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
<p> ドキュメントを開く際に実行されるアクションを設定します。 <p>

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

最適化フラグを設定します。このフラグが設定されている場合、ページがドキュメントに追加されると、結果ファイル内の同等のリソースストリームが1つの PDF オブジェクトに統合されます。これにより結果ファイルのサイズを削減できますが、実行が遅くなり、メモリ要件が増加する可能性があります。デフォルト値: false.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
ページ情報を設定します。（ジェネレータ専用で、ドキュメントを読み込む際には設定されません）

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
ドキュメントが開かれたときに使用されるページレイアウトを設定します。

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
ページモードを設定し、開いたときにドキュメントをどのように表示するかを指定します。

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
public final void setPickTrayByPdfSize(boolean value)
```

PDF ページサイズを使用して入力用紙トレイを選択するかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PrintDuplex 要素 |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

デフォルトでは、規則が破られた場合に pdfp を更新または削除するために pdfp 検証プロセスが必要です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | ブール値 |

### setTitle {#setTitle-java.lang.String-}
Pdf Document のタイトルを設定します。

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
ドキュメントの XMP メタデータを設定します。

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

ドキュメントが PDF/A に準拠しているかどうかを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

すべてのページのコンテンツデータの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツは更新されません。

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
ドキュメントを指定されたファイルに検証します。

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
ドキュメントを指定されたファイルに検証します。

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
ドキュメントを指定されたファイルに検証します。
