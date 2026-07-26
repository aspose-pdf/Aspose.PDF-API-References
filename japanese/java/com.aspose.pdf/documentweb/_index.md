---
title: "DocumentWeb"
linktitle: "DocumentWeb"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "DocumentWeb クラスを表します。"
type: docs
weight: 1170
url: /ja/java/com.aspose.pdf/documentweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DocumentWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class DocumentWeb extends Object implements IDocument
```

DocumentWeb クラスを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | フォントが文書内で別のフォントに置き換えられたときに発生します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DocumentWeb](#DocumentWeb--) | 空の DocumentWeb を初期化します。 |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-) | 空の DocumentWeb を初期化します。 |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-) | 空の DocumentWeb を初期化します。 |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-java.lang.String-) | 空の DocumentWeb を初期化します。 |
| [DocumentWeb](#DocumentWeb-java.lang.String-) | 空の DocumentWeb を初期化します。 |
| [DocumentWeb](#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-) | 空の DocumentWeb を初期化します。 |
| [DocumentWeb](#DocumentWeb-java.lang.String-java.lang.String-) | 空の DocumentWeb を初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [afterImport](#afterImport--) | 登録されているすべてのアノテーションを列挙し、それぞれに対して AfterImport を呼び出します。 |
| [bindXml](#bindXml-java.io.InputStream-) | XML をドキュメントにバインドします |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | XML/XSL をドキュメントにバインドする |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | XML/XSL をドキュメントにバインドする |
| [bindXml](#bindXml-java.lang.String-) | XML をドキュメントにバインドします |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | XML/XSL をドキュメントにバインドする |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | ドキュメントのパスワードを変更する。 |
| [check](#check-boolean-) | ドキュメントを検証する。 |
| [close](#close--) | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | ドキュメントを検索可能なドキュメントに変換する。 |
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
| [decrypt](#decrypt--) | ドキュメントの暗号を解除する。 |
| [dispose](#dispose--) | 非推奨です。 |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | ドキュメントを暗号化する。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | ドキュメントを暗号化する。 |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | すべてのドキュメント注釈をストリームにエクスポートします。 |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | すべてのドキュメント注釈を XFDF ファイルにエクスポートする |
| [flatten](#flatten--) | ドキュメントからすべてのフィールド（および注釈）を削除し、代わりにその値を配置する。 |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | ドキュメントからすべてのフィールドを削除し、代わりにその値を配置する。 |
| [flattenTransparency](#flattenTransparency--) | 透明なコンテンツを非透明のラスタおよびベクターグラフィックに置き換える。 |
| [freeMemory](#freeMemory--) | メモリをクリアする |
| [getAbsentFontHandler](#getAbsentFontHandler--) | ドキュメント処理中にフォントが見つからないことを通知します。 |
| [getActions](#getActions--) | ドキュメントのアクションを取得する。 |
| [getAllowReusePageContent](#getAllowReusePageContent--) | ページ内容をマージしてドキュメントサイズを最適化できるようにします。 |
| [getBackground](#getBackground--) | ドキュメントの背景色を取得する。 |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | カタログ辞書から項目の値を返す。 |
| [getCollection](#getCollection--) | ドキュメントのコレクションを取得する。 |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | ドキュメントが暗号化されている場合、セキュリティ設定を取得する。 |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | カスタムセキュリティハンドラを取得する。 |
| [getDefaultCopier](#getDefaultCopier--) | このドキュメントにページをコピーするために使用されるコピー機能を返す。 |
| [getDestinations](#getDestinations--) | 非推奨です。 |
| [getDirection](#getDirection--) | テキストの読み順を取得する：L2R（左から右）または R2L（右から左）。 |
| [getDuplex](#getDuplex--) | 印刷ダイアログからファイルを印刷する際に使用する、印刷デュプレックスモード処理オプションを取得または設定します。 |
| [getEmbeddedFiles](#getEmbeddedFiles--) | ドキュメントに埋め込まれたファイルのコレクションを取得します。 |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言し、IsEmbedded フラグが true に設定されていることを示すプロパティです。 |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | 署名フィールドのサニタイズを管理するフラグを取得または設定します。 |
| [getEngineDoc](#getEngineDoc--) | 内部ドキュメント構造にアクセスするために使用される IPdfDocument のインスタンスです。 |
| [getFileName](#getFileName--) | このドキュメントを引き起こした PDF ファイルの名前 |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | ファイル全体をメモリにロードする際のファイルサイズ上限を取得および設定します。 |
| [getForm](#getForm--) | ドキュメントの Acro Form を取得します。 |
| [getId](#getId--) | ID を取得します。 |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | ソースファイルのエラーを無視するフラグを取得または設定します。 |
| [getInfo](#getInfo--) | ドキュメント情報を取得します。 |
| [getJavaScript](#getJavaScript--) | ドキュメントレベルの JavaScript コレクションです。 |
| [getLogicalStructure](#getLogicalStructure--) | ドキュメントの論理構造を取得します。 |
| [getMetadata](#getMetadata--) | ドキュメントのメタデータです。 |
| [getMetadataStream](#getMetadataStream--) | 内部使用のみ！ |
| [getNamedDestinations](#getNamedDestinations--) | ドキュメント内の名前付きデスティネーションのコレクションです。 |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | 全画面モードを終了したときにドキュメントを表示する方法を指定するページモードを取得します。 |
| [getObjectById](#getObjectById-java.lang.String-) | ドキュメント内で指定された ID を持つオブジェクトを取得します。 |
| [getOpenAction](#getOpenAction--) | ドキュメントを開く際に実行されるアクションを取得します。 |
| [getOptimizeSize](#getOptimizeSize--) | 最適化フラグを取得します。 |
| [getOutlines](#getOutlines--) | ドキュメントのアウトラインを取得します。 |
| [getOutputIntents](#getOutputIntents--) | ドキュメント内の Output intents コレクションを取得します。 |
| [getPageInfo](#getPageInfo--) | ページ情報を取得します。（生成時のみ、ドキュメント読み取り時には設定されません） |
| [getPageLabels](#getPageLabels--) | ドキュメント内のページラベルを取得します。 |
| [getPageLayout](#getPageLayout--) | ドキュメントが開かれたときに使用されるページレイアウトを取得します。 |
| [getPageMode](#getPageMode--) | ドキュメントが開かれたときにどのように表示されるかを指定するページモードを取得します。 |
| [getPages](#getPages--) | ドキュメントページのコレクションを取得します。 |
| [getPdfFormat](#getPdfFormat--) | PDF 形式を取得します。 |
| [getPermissions](#getPermissions--) | ドキュメントの権限を取得します。 |
| [getPrintScaling](#getPrintScaling--) | 印刷ダイアログからファイルを印刷する際に使用する印刷スケーリング処理オプションを取得します。 |
| [getTaggedContent](#getTaggedContent--) | TaggedPdf コンテンツへのアクセスを取得します。 |
| [getVersion](#getVersion--) | Pdf ファイルヘッダーから Pdf のバージョンを取得します。 |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | ドキュメントから XMP メタデータを取得します。 |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | 現在の PDF ドキュメントが増分更新で保存されているかどうかを確認します。 |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | ストリームからドキュメントへ注釈をインポートします。 |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | XFDF ファイルからドキュメントへ注釈をインポートします。 |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | 欠落フォントの置換について通知するフラグです。 |
| [isCenterWindow](#isCenterWindow--) | ドキュメントウィンドウの位置が画面の中央に配置されるかどうかを示すフラグを取得します。 |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | フォントに対する多くの操作は、そのフォントのライセンスでこれらの操作が禁止されている場合、実行できません。 |
| [isDisplayDocTitle](#isDisplayDocTitle--) | ドキュメントウィンドウのタイトルバーにドキュメントタイトルを表示するかどうかを示すフラグを取得します。 |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | 通知のロギングを有効にするかどうかを示す値を取得または設定します。 |
| [isEnableObjectUnload](#isEnableObjectUnload--) | ドキュメントをメモリから部分的にアンロードできるようにするフラグを取得または設定します。 |
| [isEncrypted](#isEncrypted--) | ドキュメントの暗号化状態を取得します。 |
| [isFitWindow](#isFitWindow--) | ドキュメントウィンドウを最初に表示されるページに合わせてサイズ変更する必要があるかどうかを示すフラグを取得します。 |
| [isHandleSignatureChange](#isHandleSignatureChange--) | 変更が加えられ、署名がある状態でドキュメントを保存しようとした場合、例外をスローします。 |
| [isHideMenubar](#isHideMenubar--) | ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを示すフラグを取得します。 |
| [isHideToolBar](#isHideToolBar--) | ドキュメントがアクティブなときにツールバーを非表示にするかどうかを示すフラグを取得します。 |
| [isHideWindowUI](#isHideWindowUI--) | ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを示すフラグを取得または設定します。 |
| [isLicensed](#isLicensed--) | システムのライセンス状態を取得します。 |
| [isLinearized](#isLinearized--) | ドキュメントがリニアライズされているかどうかを示す値を取得または設定します。 |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | デフォルトでは、メソッド save は内部ストリームを閉じ、メモリリソースを解放します。 |
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
| [optimize](#optimize--) | ドキュメントを線形化して、- 最初のページをできるだけ速く開くため、- 次のページや次のページへのリンクをできるだけ速く表示するため、- ページのデータが遅いチャネルで配信される際に、ページが到着したら段階的に表示する（最も有用なデータを先に表示する）ため、- ページ全体が受信・表示される前でも、リンクをたどるなどのユーザー操作を可能にするためです。 |
| [optimizeResources](#optimizeResources--) | ドキュメント内のリソースを最適化します：1。 |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | 定義された最適化戦略に従ってドキュメント内のリソースを最適化します。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。 |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | 内部メソッド |
| [processParagraphs](#processParagraphs--) | ドキュメントをジェネレータに格納します。 |
| [removeMetadata](#removeMetadata--) | ドキュメントからメタデータを削除します。 |
| [removePdfaCompliance](#removePdfaCompliance--) | ドキュメントから PDF/A 準拠を削除します |
| [removePdfUaCompliance](#removePdfUaCompliance--) | ドキュメントから PDF/UA 準拠を削除します |
| [repair](#repair--) | 破損したドキュメントを修復します。 |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | 破損したドキュメントを修復します。 |
| [resumeUpdate](#resumeUpdate--) | ドキュメントの更新を再開します |
| [save](#save--) | ドキュメントをインクリメンタルに保存 (例: |
| [save](#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-) | 保存オプションを使用して、ドキュメントをレスポンスストリームに保存します。 |
| [save](#save-java.io.OutputStream-) | ドキュメントをストリームに保存します。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | 新しい名前とファイル形式でドキュメントを保存します。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 保存オプションを設定して、ドキュメントを新しい名前で保存します。 |
| [save](#save-com.aspose.pdf.SaveOptions-) | 保存オプションでドキュメントを保存します。 |
| [save](#save-com.aspose.ms.System.IO.Stream-) | 内部使用のみです。 |
| [save](#save-java.lang.String-) | 指定されたファイルにドキュメントを保存します。 |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | 新しい名前とファイル形式でドキュメントを保存します。 |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | 保存オプションを設定して、ドキュメントを新しい名前で保存します。 |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | PDF ドキュメントをインクリメンタルに指定されたストリームへ保存します。 |
| [saveXml](#saveXml-java.lang.String-) | ドキュメントを XML に保存します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | ドキュメントの特定のページを処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | ドキュメント全体を処理用にドキュメントデバイスへ送信します。 |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | ドキュメント処理中にフォントが見つからないことを通知します。 |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | 欠落フォントを置き換えるフラグを設定します。 |
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
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | ソースファイルのエラーを無視するフラグを取得または設定します。 |
| [setLinearized](#setLinearized-boolean-) | ドキュメントがリニアライズされているかどうかを示す値を設定します。 |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | デフォルトでは、メソッド save は内部ストリームを閉じ、メモリリソースを解放します。 |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | ページモードを設定し、全画面モードを終了したときにドキュメントをどのように表示するかを指定します。 |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | ドキュメントを開く際に実行されるアクションを設定します。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 最適化フラグを設定します。 |
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

### DocumentWeb {#DocumentWeb--}
```
public DocumentWeb()
```

空の DocumentWeb を初期化します。

### DocumentWeb {#DocumentWeb-java.io.InputStream-}
空の DocumentWeb を初期化します。

### DocumentWeb {#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-}
空の DocumentWeb を初期化します。

### DocumentWeb {#DocumentWeb-java.io.InputStream-java.lang.String-}
空の DocumentWeb を初期化します。

### DocumentWeb {#DocumentWeb-java.lang.String-}
空の DocumentWeb を初期化します。

### DocumentWeb {#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-}
空の DocumentWeb を初期化します。

### DocumentWeb {#DocumentWeb-java.lang.String-java.lang.String-}
空の DocumentWeb を初期化します。

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
ドキュメントのパスワードを変更する。

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
ブール値 True - ドキュメントが修復された場合；それ以外は false。

### close {#close--}
```
public void close()
```

このドキュメントで使用されているすべてのリソースを閉じます。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
ドキュメントを検索可能なドキュメントに変換する。

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

ドキュメントの暗号を解除する。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

非推奨です。

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
ドキュメントを暗号化する。

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
ドキュメントを暗号化する。

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
ドキュメントを暗号化する。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
ドキュメントを暗号化する。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
ドキュメントを暗号化する。

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
ドキュメントからすべてのフィールドを削除し、代わりにその値を配置する。

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

ドキュメントのアクションを取得する。

**Returns:**
DocumentActionCollection オブジェクト

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
java.awt.Color オブジェクト

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

ドキュメントが暗号化されている場合、セキュリティ設定を取得する。

**Returns:**
CryptoAlgorithm 要素または null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
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
@Deprecated public DestinationCollection getDestinations()
```

非推奨です。

**Returns:**
DestinationCollection オブジェクト

### getDirection {#getDirection--}
```
public Direction getDirection()
```

テキストの読み順を取得する：L2R（左から右）または R2L（右から左）。

**Returns:**
Direction 要素

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

内部ドキュメント構造にアクセスするために使用される IPdfDocument のインスタンスです。

**Returns:**
IPdfDocument オブジェクト

### getFileName {#getFileName--}
```
public String getFileName()
```

このドキュメントを引き起こした PDF ファイルの名前

**Returns:**
文字列値

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

ファイル全体をメモリにロードする際のファイルサイズ上限を取得および設定します。

**Returns:**
int 値です。

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

ソースファイルのエラーを無視するフラグを取得または設定します。

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

ドキュメントのメタデータです。

**Returns:**
Metadata オブジェクト

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

内部使用のみ！

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
PageMode 要素

### getObjectById {#getObjectById-java.lang.String-}
ドキュメント内で指定された ID を持つオブジェクトを取得します。

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

ドキュメントを開く際に実行されるアクションを取得します。

**Returns:**
IAppointment オブジェクト

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

最適化フラグを取得します。

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
PageLayout 要素

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

ドキュメントが開かれたときにどのように表示されるかを指定するページモードを取得します。

**Returns:**
PageMode 要素

### getPages {#getPages--}
```
public PageCollection getPages()
```

ドキュメントページのコレクションを取得します。

**Returns:**
ブール値

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

PDF 形式を取得します。

**Returns:**
PdfFormat

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
public ITaggedContent getTaggedContent()
```

TaggedPdf コンテンツへのアクセスを取得します。

**Returns:**
ITaggedContent インスタンス

### getVersion {#getVersion--}
```
public String getVersion()
```

Pdf ファイルヘッダーから Pdf のバージョンを取得します。

**Returns:**
String オブジェクト

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

ドキュメントウィンドウの位置が画面の中央に配置されるかどうかを示すフラグを取得します。

**Returns:**
ブール値

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

ドキュメントウィンドウのタイトルバーにドキュメントタイトルを表示するかどうかを示すフラグを取得します。

**Returns:**
ブール値

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

ドキュメントの暗号化状態を取得します。

**Returns:**
ブール値

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

ドキュメントウィンドウを最初に表示されるページに合わせてサイズ変更する必要があるかどうかを示すフラグを取得します。

**Returns:**
ブール値

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

ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

ドキュメントがアクティブなときにツールバーを非表示にするかどうかを示すフラグを取得します。

**Returns:**
ブール値

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを示すフラグを取得または設定します。

**Returns:**
ブール値

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

ドキュメントがリニアライズされているかどうかを示す値を取得または設定します。

**Returns:**
ブール値

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

デフォルトでは、メソッド save は内部ストリームを閉じ、メモリリソースを解放します。

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

ドキュメントを線形化して、- 最初のページをできるだけ速く開くため、- 次のページや次のページへのリンクをできるだけ速く表示するため、- ページのデータが遅いチャネルで配信される際に、ページが到着したら段階的に表示する（最も有用なデータを先に表示する）ため、- ページ全体が受信・表示される前でも、リンクをたどるなどのユーザー操作を可能にするためです。

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

ドキュメント内のリソースを最適化します：1。

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
定義された最適化戦略に従ってドキュメント内のリソースを最適化します。

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| nodesNumInSubtrees |  | サブノードの希望数。 デフォルト値は 10 です。 |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
内部メソッド

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

ドキュメントをジェネレータに格納します。

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

ドキュメントをインクリメンタルに保存 (例:

### save {#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-}
保存オプションを使用して、ドキュメントをレスポンスストリームに保存します。

### save {#save-java.io.OutputStream-}
ドキュメントをストリームに保存します。

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
新しい名前とファイル形式でドキュメントを保存します。

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
保存オプションを設定して、ドキュメントを新しい名前で保存します。

### save {#save-com.aspose.pdf.SaveOptions-}
保存オプションでドキュメントを保存します。

### save {#save-com.aspose.ms.System.IO.Stream-}
内部使用のみです。

### save {#save-java.lang.String-}
指定されたファイルにドキュメントを保存します。

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
新しい名前とファイル形式でドキュメントを保存します。

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

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
ドキュメント処理中にフォントが見つからないことを通知します。

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean substitute)
```

欠落フォントを置き換えるフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 代替 |  | ブール値 |

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

ソースファイルのエラーを無視するフラグを取得または設定します。

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

デフォルトでは、メソッド save は内部ストリームを閉じ、メモリリソースを解放します。

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
public void setOptimizeSize(boolean value)
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
