---
title: "IDocument"
linktitle: "IDocument"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントを表すインターフェイス"
type: docs
weight: 2230
url: /ja/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

PDF ドキュメントを表すインターフェイス

## メソッド

| メソッド | 説明 |
| --- | --- |
| [afterImport](#afterImport--) | 登録されているすべてのアノテーションを列挙し、それぞれに対して AfterImport を呼び出します。 |
| [bindXml](#bindXml-java.io.InputStream-) | XML をドキュメントにバインドします |
| [bindXml](#bindXml-java.lang.String-) | XML をドキュメントにバインドします |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | XML/XSL をドキュメントにバインドする |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | ドキュメントのパスワードを変更する。 |
| [check](#check-boolean-) | ドキュメントを検証する。 |
| [close](#close--) | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | ドキュメントを検索可能なドキュメントに変換する。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 <p> これはページ上で検索可能なテキストの表示/非表示を可能にします。デフォルト値は FALSE です。これは PDF から元の画像を取得することを可能にします。デフォルト値は FALSE です。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 <p> これはページ上で検索可能なテキストの表示/非表示を可能にします。デフォルト値は FALSE です。これは PDF から元の画像を取得することを可能にします。デフォルト値は FALSE です。 |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | 指定された変換オプションを使用してドキュメントを変換する |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | ドキュメントを変換し、エラーを指定されたファイルに保存する。 |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 内部メソッド |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。 |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。 |
| [decrypt](#decrypt--) | ドキュメントの暗号を解除する。 |
| [dispose](#dispose--) | 非推奨です。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | ドキュメントを暗号化する。 |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | すべてのドキュメント注釈を XFDF ファイルにエクスポートする |
| [flatten](#flatten--) | ドキュメントからすべてのフィールド（および注釈）を削除し、代わりにその値を配置する。 |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | ドキュメントからすべてのフィールドを削除し、代わりにその値を配置する。 |
| [flattenTransparency](#flattenTransparency--) | 透明なコンテンツを非透明のラスタおよびベクターグラフィックに置き換える。 |
| [freeMemory](#freeMemory--) | メモリをクリアする |
| [getActions](#getActions--) | ドキュメントのアクションを取得する。 |
| [getBackground](#getBackground--) | ドキュメントの背景色を取得する。 |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | カタログ辞書から項目の値を返す。 |
| [getCollection](#getCollection--) | ドキュメントのコレクションを取得する。 |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | ドキュメントが暗号化されている場合、セキュリティ設定を取得する。 |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | カスタムセキュリティハンドラを取得する。 |
| [getDefaultCopier](#getDefaultCopier--) | このドキュメントにページをコピーするために使用されるコピー機能を返す。 |
| [getDestinations](#getDestinations--) | 宛先のコレクションを取得する。 |
| [getDirection](#getDirection--) | テキストの読み順を取得する：L2R（左から右）または R2L（右から左）。 |
| [getDuplex](#getDuplex--) | 印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。 |
| [getEmbeddedFiles](#getEmbeddedFiles--) | ドキュメントに埋め込まれたファイルのコレクションを取得します。 |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。 |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | 署名フィールドのサニタイズを管理するフラグを取得または設定します。 |
| [getEngineDoc](#getEngineDoc--) | 内部ドキュメント構造にアクセスするために使用される IPdfDocument のインスタンスです。 |
| [getFileName](#getFileName--) | このドキュメントを引き起こした PDF ファイルの名前 |
| [getForm](#getForm--) | ドキュメントの Acro Form を取得します。 |
| [getId](#getId--) | ID を取得します。 |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | ソースファイルのエラーを無視するフラグを取得または設定します。 |
| [getInfo](#getInfo--) | ドキュメント情報を取得します。 |
| [getLogicalStructure](#getLogicalStructure--) | ドキュメントの論理構造を取得します。 |
| [getMetadata](#getMetadata--) | ドキュメントのメタデータです。 |
| [getMetadataStream](#getMetadataStream--) | 生のメタデータストリームを返します |
| [getNamedDestinations](#getNamedDestinations--) | ドキュメント内の名前付きデスティネーションのコレクションです。 |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | 全画面モードを終了したときにドキュメントを表示する方法を指定するページモードを取得します。 |
| [getObjectById](#getObjectById-java.lang.String-) | ドキュメント内で指定された ID を持つオブジェクトを取得します。 |
| [getOpenAction](#getOpenAction--) | ドキュメントを開く際に実行されるアクションを取得します。 |
| [getOptimizeSize](#getOptimizeSize--) | 最適化フラグを取得します。 |
| [getOutlines](#getOutlines--) | ドキュメントのアウトラインを取得します。 |
| [getPageInfo](#getPageInfo--) | ページ情報を取得します。（生成時のみ、ドキュメント読み取り時には設定されません） |
| [getPageLabels](#getPageLabels--) | ドキュメント内のページラベルを取得します。 |
| [getPageLayout](#getPageLayout--) | ドキュメントが開かれたときに使用されるページレイアウトを取得します。 |
| [getPageMode](#getPageMode--) | ドキュメントが開かれたときにどのように表示されるかを指定するページモードを取得します。 |
| [getPages](#getPages--) | ドキュメントページのコレクションを取得します。 |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | ドキュメントの権限を取得します。 |
| [getPrintScaling](#getPrintScaling--) | 印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを取得します。 |
| [getTaggedContent](#getTaggedContent--) | TaggedPdf コンテンツへのアクセスを取得します。 |
| [getVersion](#getVersion--) | Pdf ファイルヘッダーから Pdf のバージョンを取得します。 |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | ドキュメントから XMP メタデータを取得します。 |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | XFDF ファイルからドキュメントへ注釈をインポートします。 |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | ドキュメント処理時にフォントが欠落していることの通知 |
| [isCenterWindow](#isCenterWindow--) | ドキュメントウィンドウの位置が画面の中央に配置されるかどうかを示すフラグを取得します。 |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。 |
| [isDisplayDocTitle](#isDisplayDocTitle--) | ドキュメントウィンドウのタイトルバーにドキュメントタイトルを表示するかどうかを示すフラグを取得します。 |
| [isEncrypted](#isEncrypted--) | ドキュメントの暗号化状態を取得します。 |
| [isFitWindow](#isFitWindow--) | ドキュメントウィンドウを最初に表示されるページに合わせてサイズ変更する必要があるかどうかを示すフラグを取得します。 |
| [isHideMenubar](#isHideMenubar--) | ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを示すフラグを取得します。 |
| [isHideToolBar](#isHideToolBar--) | ドキュメントがアクティブなときにツールバーを非表示にするかどうかを示すフラグを取得します。 |
| [isHideWindowUI](#isHideWindowUI--) | ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを示すフラグを取得または設定します。 |
| [isLinearized](#isLinearized--) | ドキュメントがリニアライズされているかどうかを示す値を取得または設定します。 |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | デフォルトでは、save メソッドは内部ストリームを閉じ、メモリリソースを解放します。この ManualDispose パラメータが有効な場合、save 後にいくつかの操作を行い、ドキュメントの作業を続行できます。 |
| [isPdfaCompliant](#isPdfaCompliant--) | ドキュメントが PDF/A に準拠しているかどうかを取得します。 |
| [isPdfUaCompliant](#isPdfUaCompliant--) | ドキュメントが PDF/UA に準拠しているかどうかを取得します。 |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | PDF ページサイズを入力用紙トレイの選択に使用するかどうかを示すフラグを取得します。 |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | ドキュメントが PDF/A に準拠しているかどうかを取得または設定します。 |
| [optimize](#optimize--) | ドキュメントをリニアライズして、- 最初のページをできるだけ早く開く; - 次のページや次のページへのリンクをできるだけ早く表示する; - ページデータが遅いチャネルで配信される際に、ページが到着するたびに段階的に表示する（最も有用なデータを先に表示）; - ページ全体が受信・表示される前でも、リンクのクリックなどのユーザー操作を可能にする、という目的を達成します。 |
| [optimizeResources](#optimizeResources--) | ドキュメント内のリソースを最適化します：1。 |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | 定義された最適化戦略に従ってドキュメント内のリソースを最適化します。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。 |
| [processParagraphs](#processParagraphs--) | ドキュメントをストリームに保存します。 |
| [removeMetadata](#removeMetadata--) | ドキュメントからメタデータを削除します。 |
| [removePdfaCompliance](#removePdfaCompliance--) | ドキュメントから PDF/A 準拠を削除します |
| [removePdfUaCompliance](#removePdfUaCompliance--) | ドキュメントから PDF/UA 準拠を削除します |
| [repair](#repair--) | 破損したドキュメントを修復します。 |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | ドキュメントをインクリメンタルに保存 (例: |
| [save](#save-java.io.OutputStream-) | ドキュメントをストリームに保存します。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | ドキュメントを保存 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 保存オプションを設定して、ドキュメントを新しい名前で保存します。 |
| [save](#save-java.lang.String-) | 指定されたファイルにドキュメントを保存します。 |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | 保存オプションを設定して、ドキュメントを新しい名前で保存します。 |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveXml](#saveXml-java.lang.String-) | ドキュメントを XML に保存します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | ドキュメントの特定のページを処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | フォントが存在しない場合にプログラムが決定したフォントを設定するフラグを設定します。 |
| [setBackground](#setBackground-java.awt.Color-) | ドキュメントの背景色を設定します。 |
| [setCenterWindow](#setCenterWindow-boolean-) | ドキュメントウィンドウの位置を画面の中央にするかどうかを指定するフラグを設定します。 |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | ドキュメントのコレクションを設定します。 |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | pdf/ua コンバータの変換パラメータを取得します（true に設定するとメタデータとドキュメントカタログのみ変換します） |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | テキストの読み順を設定します：L2R（左から右）または R2L（右から左）。 |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。 |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | ドキュメントウィンドウのタイトルバーにドキュメントタイトルを表示するかどうかを指定するフラグを設定します。 |
| [setDuplex](#setDuplex-int-) | 印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。 |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。 |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | 署名フィールドのサニタイズを管理するフラグを取得または設定します。 |
| [setFitWindow](#setFitWindow-boolean-) | 最初に表示されたページに合わせてドキュメントウィンドウのサイズを変更するかどうかを指定するフラグを設定します。 |
| [setHideMenubar](#setHideMenubar-boolean-) | ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを指定するフラグを設定します。 |
| [setHideToolBar](#setHideToolBar-boolean-) | ドキュメントがアクティブなときにツールバーを非表示にするかどうかを指定するフラグを設定します。 |
| [setHideWindowUI](#setHideWindowUI-boolean-) | ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを指定するフラグを設定します。 |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | ドキュメントがリニアライズされているかどうかを示す値を設定します。 |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | デフォルトでは、save メソッドは内部ストリームを閉じ、メモリリソースを解放します。ManualDispose パラメータが有効な場合、save メソッドが呼び出された後でもいくつかの操作を行い、ドキュメントの作業を続行できます。ただし、Document インスタンスが不要になったときは、dispose メソッドを呼び出すことが強く推奨されます。 |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | ページモードを設定し、全画面モードを終了したときにドキュメントをどのように表示するかを指定します。 |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | ドキュメントを開く際に実行されるアクションを設定します。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 最適化フラグを設定します。 |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | ページ情報を設定します。（ジェネレータ専用で、ドキュメントを読み込む際には設定されません） |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | ドキュメントが開かれたときに使用されるページレイアウトを設定します。 |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | ページモードを設定し、開いたときにドキュメントをどのように表示するかを指定します。 |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | PDF ページサイズを使用して入力用紙トレイを選択するかどうかを指定するフラグを設定します。 |
| [setPrintScaling](#setPrintScaling-int-) | 印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを設定します。 |
| [setTitle](#setTitle-java.lang.String-) | Pdf Document のタイトルを設定します。 |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | ドキュメントの XMP メタデータを設定します。 |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | ドキュメントが PDF/A に準拠しているかどうかを取得または設定します。 |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | ドキュメントを指定されたファイルに検証します。 |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | ドキュメントを指定されたファイルに検証します。 |

### afterImport {#afterImport--}
```
void afterImport()
```

登録されているすべてのアノテーションを列挙し、それぞれに対して AfterImport を呼び出します。

### bindXml {#bindXml-java.io.InputStream-}
XML をドキュメントにバインドします

### bindXml {#bindXml-java.lang.String-}
XML をドキュメントにバインドします

### bindXml {#bindXml-java.lang.String-java.lang.String-}
XML/XSL をドキュメントにバインドする

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
ドキュメントのパスワードを変更する。

### check {#check-boolean-}
```
boolean check(boolean doRepair)
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
void close()
```

このドキュメントで使用されているすべてのリソースを閉じます。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
ドキュメントを検索可能なドキュメントに変換する。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。 <p> これはページ上で検索可能なテキストの表示/非表示を可能にします。デフォルト値は FALSE です。これは PDF から元の画像を取得することを可能にします。デフォルト値は FALSE です。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。 <p> これはページ上で検索可能なテキストの表示/非表示を可能にします。デフォルト値は FALSE です。これは PDF から元の画像を取得することを可能にします。デフォルト値は FALSE です。

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
指定された変換オプションを使用してドキュメントを変換する

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
ドキュメントを変換し、エラーを指定されたファイルに保存する。

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
内部メソッド

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
ドキュメントを検索可能なドキュメントに変換し、変換できない hochr のエラーをスキップする。

### decrypt {#decrypt--}
```
void decrypt()
```

ドキュメントの暗号を解除する。

### dispose {#dispose--}
```
@Deprecated void dispose()
```

非推奨です。

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
ドキュメントを暗号化する。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
ドキュメントを暗号化する。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
ドキュメントを暗号化する。

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
すべてのドキュメント注釈を XFDF ファイルにエクスポートする

### flatten {#flatten--}
```
void flatten()
```

ドキュメントからすべてのフィールド（および注釈）を削除し、代わりにその値を配置する。

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
ドキュメントからすべてのフィールドを削除し、代わりにその値を配置する。

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

透明なコンテンツを非透明のラスタおよびベクターグラフィックに置き換える。

### freeMemory {#freeMemory--}
```
void freeMemory()
```

メモリをクリアする

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

ドキュメントのアクションを取得する。

**Returns:**
DocumentActionCollection オブジェクト

### getBackground {#getBackground--}
```
Color getBackground()
```

ドキュメントの背景色を取得する。

**Returns:**
java.awt.Color オブジェクト

### getCatalogValue {#getCatalogValue-java.lang.String-}
カタログ辞書から項目の値を返す。

### getCollection {#getCollection--}
```
Collection getCollection()
```

ドキュメントのコレクションを取得する。

**Returns:**
Collection オブジェクト

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

ドキュメントが暗号化されている場合、セキュリティ設定を取得する。

**Returns:**
CryptoAlgorithm 要素または null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

カスタムセキュリティハンドラを取得する。

**Returns:**
ICustomSecurityHandler インスタンス

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

このドキュメントにページをコピーするために使用されるコピー機能を返す。

**Returns:**
Copier オブジェクト

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

宛先のコレクションを取得する。

**Returns:**
DestinationCollection オブジェクト

### getDirection {#getDirection--}
```
Direction getDirection()
```

テキストの読み順を取得する：L2R（左から右）または R2L（右から左）。

**Returns:**
Direction 要素

### getDuplex {#getDuplex--}
```
int getDuplex()
```

印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。

**Returns:**
PrintDuplex 要素

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

ドキュメントに埋め込まれたファイルのコレクションを取得します。

**Returns:**
EmbeddedFileCollection オブジェクト

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。

**Returns:**
ブール値

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

署名フィールドのサニタイズを管理するフラグを取得または設定します。

**Returns:**
ブール値

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

内部ドキュメント構造にアクセスするために使用される IPdfDocument のインスタンスです。

**Returns:**
IPdfDocument オブジェクト

### getFileName {#getFileName--}
```
String getFileName()
```

このドキュメントを引き起こした PDF ファイルの名前

**Returns:**
String オブジェクト

### getForm {#getForm--}
```
Form getForm()
```

ドキュメントの Acro Form を取得します。

**Returns:**
Form オブジェクト

### getId {#getId--}
```
Id getId()
```

ID を取得します。

**Returns:**
Id オブジェクト

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

ソースファイルのエラーを無視するフラグを取得または設定します。

**Returns:**
ブール値

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

ドキュメント情報を取得します。

**Returns:**
DocumentInfo オブジェクト

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

ドキュメントの論理構造を取得します。

**Returns:**
RootElement オブジェクト

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

ドキュメントのメタデータです。

**Returns:**
Metadata オブジェクト

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

生のメタデータストリームを返します

**Returns:**
IPdfStreamAccessor オブジェクト

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

ドキュメント内の名前付きデスティネーションのコレクションです。

**Returns:**
NamedDestinationCollection インスタンス

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

全画面モードを終了したときにドキュメントを表示する方法を指定するページモードを取得します。

**Returns:**
PageMode 要素

### getObjectById {#getObjectById-java.lang.String-}
ドキュメント内で指定された ID を持つオブジェクトを取得します。

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

ドキュメントを開く際に実行されるアクションを取得します。

**Returns:**
IAppointment オブジェクト

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

最適化フラグを取得します。

**Returns:**
ブール値

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

ドキュメントのアウトラインを取得します。

**Returns:**
OutlineCollection オブジェクト

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

ページ情報を取得します。（生成時のみ、ドキュメント読み取り時には設定されません）

**Returns:**
ページ情報です。

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

ドキュメント内のページラベルを取得します。

**Returns:**
PageLabelCollection オブジェクト

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

ドキュメントが開かれたときに使用されるページレイアウトを取得します。

**Returns:**
PageLayout 要素

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

ドキュメントが開かれたときにどのように表示されるかを指定するページモードを取得します。

**Returns:**
PageMode 要素

### getPages {#getPages--}
```
PageCollection getPages()
```

ドキュメントページのコレクションを取得します。

**Returns:**
ブール値

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
PdfFormat 要素

### getPermissions {#getPermissions--}
```
int getPermissions()
```

ドキュメントの権限を取得します。

**Returns:**
int 値です。

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを取得します。

**Returns:**
PrintScaling 要素

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

TaggedPdf コンテンツへのアクセスを取得します。

**Returns:**
ITaggedContent インスタンス

### getVersion {#getVersion--}
```
String getVersion()
```

Pdf ファイルヘッダーから Pdf のバージョンを取得します。

**Returns:**
String オブジェクト

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
ドキュメントから XMP メタデータを取得します。

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
XFDF ファイルからドキュメントへ注釈をインポートします。

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

ドキュメント処理時にフォントが欠落していることの通知

**Returns:**
ブール値

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

ドキュメントウィンドウの位置が画面の中央に配置されるかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。

**Returns:**
ブール値 デフォルトは false。

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

ドキュメントウィンドウのタイトルバーにドキュメントタイトルを表示するかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

ドキュメントの暗号化状態を取得します。

**Returns:**
ブール値

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

ドキュメントウィンドウを最初に表示されるページに合わせてサイズ変更する必要があるかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

ドキュメントがアクティブなときにツールバーを非表示にするかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを示すフラグを取得または設定します。

**Returns:**
ブール値

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

ドキュメントがリニアライズされているかどうかを示す値を取得または設定します。

**Returns:**
ブール値

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

デフォルトでは、save メソッドは内部ストリームを閉じ、メモリリソースを解放します。この ManualDispose パラメータが有効な場合、save 後にいくつかの操作を行い、ドキュメントの作業を続行できます。

**Returns:**
ブール値。 (デフォルト値 == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

ドキュメントが PDF/A に準拠しているかどうかを取得します。

**Returns:**
ブール値

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

ドキュメントが PDF/UA に準拠しているかどうかを取得します。

**Returns:**
ブール値

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

PDF ページサイズを入力用紙トレイの選択に使用するかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

ドキュメントが PDF/A に準拠しているかどうかを取得または設定します。

**Returns:**
ブール値

### optimize {#optimize--}
```
void optimize()
```

ドキュメントをリニアライズして、- 最初のページをできるだけ早く開く; - 次のページや次のページへのリンクをできるだけ早く表示する; - ページデータが遅いチャネルで配信される際に、ページが到着するたびに段階的に表示する（最も有用なデータを先に表示）; - ページ全体が受信・表示される前でも、リンクのクリックなどのユーザー操作を可能にする、という目的を達成します。

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

ドキュメント内のリソースを最適化します：1。

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
定義された最適化戦略に従ってドキュメント内のリソースを最適化します。

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| nodesNumInSubtrees |  | サブノードの希望数。 デフォルト値は 10 です。 |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

ドキュメントをストリームに保存します。

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

ドキュメントからメタデータを削除します。

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

ドキュメントから PDF/A 準拠を削除します

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

ドキュメントから PDF/UA 準拠を削除します

### repair {#repair--}
```
void repair()
```

破損したドキュメントを修復します。

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

ドキュメントをインクリメンタルに保存 (例:

### save {#save-java.io.OutputStream-}
ドキュメントをストリームに保存します。

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
ドキュメントを保存

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
保存オプションを設定して、ドキュメントを新しい名前で保存します。

### save {#save-java.lang.String-}
指定されたファイルにドキュメントを保存します。

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
保存オプションを設定して、ドキュメントを新しい名前で保存します。

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

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

フォントが存在しない場合にプログラムが決定したフォントを設定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | ブール値 |

### setBackground {#setBackground-java.awt.Color-}
ドキュメントの背景色を設定します。

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

ドキュメントウィンドウの位置を画面の中央にするかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
ドキュメントのコレクションを設定します。

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

pdf/ua コンバータの変換パラメータを取得します（true に設定するとメタデータとドキュメントカタログのみ変換します）

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
テキストの読み順を設定します：L2R（左から右）または R2L（右から左）。

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 デフォルトは false。 |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

ドキュメントウィンドウのタイトルバーにドキュメントタイトルを表示するかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PrintDuplex 要素 |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

署名フィールドのサニタイズを管理するフラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

最初に表示されたページに合わせてドキュメントウィンドウのサイズを変更するかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

ドキュメントがアクティブなときにツールバーを非表示にするかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

ドキュメントがリニアライズされているかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

デフォルトでは、save メソッドは内部ストリームを閉じ、メモリリソースを解放します。ManualDispose パラメータが有効な場合、save メソッドが呼び出された後でもいくつかの操作を行い、ドキュメントの作業を続行できます。ただし、Document インスタンスが不要になったときは、dispose メソッドを呼び出すことが強く推奨されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| manualDisposeEnabled |  | ブール値。 (デフォルト値 == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
ページモードを設定し、全画面モードを終了したときにドキュメントをどのように表示するかを指定します。

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
ドキュメントを開く際に実行されるアクションを設定します。

### setOptimizeSize {#setOptimizeSize-boolean-}
```
void setOptimizeSize(boolean value)
```

最適化フラグを設定します。

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
void setPickTrayByPdfSize(boolean value)
```

PDF ページサイズを使用して入力用紙トレイを選択するかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PrintDuplex 要素 |

### setTitle {#setTitle-java.lang.String-}
Pdf Document のタイトルを設定します。

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
ドキュメントの XMP メタデータを設定します。

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

ドキュメントが PDF/A に準拠しているかどうかを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
ドキュメントを指定されたファイルに検証します。

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
ドキュメントを指定されたファイルに検証します。
