---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルに対する結合、分割、ページ抽出、ブックレット作成などの操作を実装する PdfFileEditorWeb クラスを表します。"
type: docs
weight: 480
url: /ja/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

PDF ファイルに対する結合、分割、ページ抽出、ブックレット作成などの操作を実装する PdfFileEditorWeb クラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | PdfFileEditorWeb のコンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | ページ内容のサイズを変更し、指定された余白を追加します。 |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | ページ内容のサイズを変更し、指定された余白を追加します。 |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | ページ内容のサイズを変更し、指定された余白を追加します。 |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | ページ内容のサイズを変更し、指定された余白を追加します。 |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | ドキュメントのページに改ページを追加します。 |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | ドキュメントのページに改ページを追加します。 |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | ドキュメントのページに改ページを追加します。 |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | ドキュメントのページに改ページを追加します。 |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | ドキュメントをソースドキュメントに追加し、結果をレスポンスオブジェクトに保存します。 |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | portStreams のドキュメント配列から選択されたページを追加します。 |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | portStream から startPage から endPage の範囲で選択されたページを、firstInputStream の末尾にある portStream に追加します。 |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | ドキュメントをソースドキュメントに追加し、結果を HttpServletResponse オブジェクトに保存します。 |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | portFiles のドキュメントから選択されたページを追加します。 |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | portFile から startPage から endPage の範囲で選択されたページを、firstInputFile の末尾にある portFile に追加します。 |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | ドキュメントを連結します。 |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | ファイルを連結し、結果を HttpServletResponse オブジェクトに格納します。 |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | ファイルを連結します |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 2つの Pdf ドキュメントを交互にページを配置した新しい Pdf ドキュメントに結合し、空白の場所を空白ページで埋めます。 |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 2つのファイルを連結します。 |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | ファイルを連結し、結果を HttpResposnse オブジェクトに保存します。 |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | ファイルを1つのファイルに連結します。 |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | 2つのファイルを連結します。 |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 2つの Pdf ドキュメントを交互にページを配置した新しい Pdf ドキュメントに結合し、空白の場所を空白ページで埋めます。 |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | ドキュメントから指定されたページを削除し、結果を HttpServletResponse オブジェクトに保存します。 |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | ドキュメントから指定されたページを削除し、結果を HttpServletResponse オブジェクトに格納します。 |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | ソースファイルから指定されたページを抽出し、結果を HttpServletResponse オブジェクトに格納します。 |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | 番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。 |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | ソースファイルから指定されたページを抽出し、結果を HttpServletResponse オブジェクトに格納します。 |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | 番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。 |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | 非推奨です。このプロパティは非推奨であり、例外をスローできるように使用できません。 |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpServletResponse オブジェクトに添付ファイルとして格納されるときの添付ファイル名を取得します。 |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | true に設定すると、操作後にストリームが閉じられます。 |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | UseDiskBuffer が true に設定されている場合、連結中に新しい増分更新が行われるまでに連結されたドキュメント数を示します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpServletResponse オブジェクトに格納されるとき、コンテンツがどのように保存されるかを取得します。 |
| [getConversionLog](#getConversionLog--) | 変換プロセスのログを取得します。 |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | true の場合、連結が実行されるときにファイルの論理構造がコピーされます。 |
| [getCopyOutlines](#getCopyOutlines--) | true の場合、アウトラインがコピーされます。 |
| [getCorruptedFileAction](#getCorruptedFileAction--) | このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。 |
| [getCorruptedItems](#getCorruptedItems--) | 連結が実行されたときに発生した問題の配列。 |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | 連結中に動作し、内部連結ステージのイベントを外部顧客コードに変換する内部プログレスイベントプロセッサの表現です。 |
| [getIncrementalUpdates](#getIncrementalUpdates--) | true の場合、連結中に増分更新が行われます。 |
| [getKeepActions](#getKeepActions--) | true の場合、アクションがソースドキュメントからコピーされます。 |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | true の場合、フォームを連結するときにフィールド名が一意になるように作成されます。 |
| [getLastException](#getLastException--) | 最後に発生した例外を取得します。 |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。 |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | true の場合、重複したアウトラインがマージされます。 |
| [getOptimizeSize](#getOptimizeSize--) | 最適化フラグを取得または設定します。 |
| [getOwnerPassword](#getOwnerPassword--) | ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを取得します。 |
| [getPreserveUserRights](#getPreserveUserRights--) | true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。 |
| [getRemoveSignatures](#getRemoveSignatures--) | true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpServletResponse として保存されるときの保存オプションを取得または設定します。 |
| [getUniqueSuffix](#getUniqueSuffix--) | フォームを連結するときにフィールド名を一意にするために追加されるサフィックスの形式を取得します。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | ドキュメントを別のドキュメントに挿入し、結果をレスポンスオブジェクトに格納します。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | 別のファイルからページを挿入して、入力 PDF ファイルに追加します。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | 別のファイルからページを挿入して、入力 PDF ファイルに追加します。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | ファイルの内容をソースファイルに挿入し、結果を HttpServletResponse オブジェクトに格納します。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | 別のファイルからページを挿入して、入力 PDF ファイルに追加します。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | 別のファイルからページを指定位置に挿入して、PDF ファイルに追加します。 |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣り合わせに配置して構成されていることがあります。 |
| [isUseDiskBuffer](#isUseDiskBuffer--) | このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | InputStream から outputStream へブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | firstInputStream から outputStream へカスタマイズされたブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | 入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | firstInputStream から outputStream へブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | ソースファイルからブックレットを作成し、結果を HttpServletResponse に格納します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | PDF ファイルからブックレットを作成し、結果を HttpServletResponse に格納します。 |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | ソースファイルからブックレットを作成し、結果を HttpServletResponse オブジェクトに格納します。 |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | ソースファイルからブックレットを作成し、結果を HttpServletResponse オブジェクトに格納します。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | inputFile から outputFile へブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | 複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 2 つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | N-up ドキュメントを作成し、結果を HttpServletResponse に格納します。 |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | N-up ドキュメントを作成し、結果を HttpServletResponse オブジェクトに格納します。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | 入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | 最初の入力ストリームから output stream へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | 複数の入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | N-up ドキュメントを作成し、結果を HttpServletResponse に格納します。 |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | N-up ドキュメントを作成し、結果を HttpServletResponse オブジェクトに格納します。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | firstInputFile から outputFile へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | 入力ファイルから outputFile へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | 2 つの入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。 |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページサイズを変更します。 |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページサイズを変更します。 |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | ドキュメントページの内容のサイズを変更します。 |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページの内容をリサイズします。 |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | ドキュメント内のページの内容をリサイズします。 |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | ドキュメント内のページの内容をリサイズします。 |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | ドキュメントページの内容のサイズを変更します。 |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメント内のページの内容をリサイズします。 |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | ドキュメントページの内容のサイズを変更します。 |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | ドキュメントページの内容のサイズを変更します。 |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページサイズを変更します。 |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページサイズを変更します。 |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | 非推奨です。このプロパティは非推奨であり、例外をスローできるように使用できません。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作の結果が HttpServletResponse オブジェクトに添付ファイルとして保存されるときの添付ファイル名を設定します。 |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | true に設定すると、操作後にストリームが閉じられます。 |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | UseDiskBuffer が true に設定されている場合、連結中に新しい増分更新が行われるまでに連結されたドキュメント数を示します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作の結果が HttpServletResponse オブジェクトに格納される際のコンテンツの保存方法を設定します。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF ファイル形式を設定します。 |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | true の場合、連結が実行されるときにファイルの論理構造がコピーされます。 |
| [setCopyOutlines](#setCopyOutlines-boolean-) | true の場合、アウトラインがコピーされます。 |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。 |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | 連結中に動作し、内部連結ステージのイベントを外部顧客コードに変換する内部プログレスイベントプロセッサの表現です。 |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | true の場合、連結中に増分更新が行われます。 |
| [setKeepActions](#setKeepActions-boolean-) | true の場合、アクションがソースドキュメントからコピーされます。 |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | true の場合、フォームを連結するときにフィールド名が一意になるように作成されます。 |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。 |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | true の場合、重複したアウトラインがマージされます。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 最適化フラグを取得または設定します。 |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを設定します。 |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。 |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpServletResponse として格納される際の保存オプションを設定します。 |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣り合わせに配置して構成されていることがあります。 |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | フォームが連結されるときにフィールド名が一意になるように付加されるサフィックスの形式を設定します。 |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。 |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | ドキュメントを開始位置から指定された位置まで分割し、結果を HttpServletResponse オブジェクトに格納します。 |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | 開始位置から指定された場所まで分割し、前半部分を出力ストリームに保存します。 |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | ドキュメントを最初のページから指定位置まで分割し、結果を HttpServletResponse オブジェクトに保存します。 |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | PDF ファイルを最初のページから指定された場所まで分割し、前半部分を新しいファイルとして保存します。 |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。 |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。 |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | 指定された位置から分割し、後半部分を HttpServletResponse オブジェクトに保存します。 |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | 指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。 |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | 指定された位置から分割し、後半部分を HttpServletResponse オブジェクトに保存します。 |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | 位置から分割し、後半部分を新しいファイルとして保存します。 |
| [splitToPages](#splitToPages-java.io.InputStream-) | PDF ファイルを単一ページのドキュメントに分割します。 |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。 |
| [splitToPages](#splitToPages-java.lang.String-) | PDFファイルを単一ページのドキュメントに分割します。 |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。 |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

PdfFileEditorWeb のコンストラクタ。

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
ページ内容のサイズを変更し、指定された余白を追加します。

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
ページ内容のサイズを変更し、指定された余白を追加します。

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
ページ内容のサイズを変更し、指定された余白を追加します。

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
ページ内容のサイズを変更し、指定された余白を追加します。

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
ドキュメントのページに改ページを追加します。

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
ドキュメントのページに改ページを追加します。

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
ドキュメントのページに改ページを追加します。

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
ドキュメントのページに改ページを追加します。

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
ドキュメントをソースドキュメントに追加し、結果をレスポンスオブジェクトに保存します。

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
portStreams のドキュメント配列から選択されたページを追加します。

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
portStream から startPage から endPage の範囲で選択されたページを、firstInputStream の末尾にある portStream に追加します。

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
ドキュメントをソースドキュメントに追加し、結果を HttpServletResponse オブジェクトに保存します。

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
portFiles のドキュメントから選択されたページを追加します。

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
portFile から startPage から endPage の範囲で選択されたページを、firstInputFile の末尾にある portFile に追加します。

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
ドキュメントを連結します。

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
ファイルを連結し、結果を HttpServletResponse オブジェクトに格納します。

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
ファイルを連結します

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
2つの Pdf ドキュメントを交互にページを配置した新しい Pdf ドキュメントに結合し、空白の場所を空白ページで埋めます。

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
2つのファイルを連結します。

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
ファイルを連結し、結果を HttpResposnse オブジェクトに保存します。

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
ファイルを1つのファイルに連結します。

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
2つのファイルを連結します。

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
2つの Pdf ドキュメントを交互にページを配置した新しい Pdf ドキュメントに結合し、空白の場所を空白ページで埋めます。

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
ドキュメントから指定されたページを削除し、結果を HttpServletResponse オブジェクトに保存します。

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
ドキュメントから指定されたページを削除し、結果を HttpServletResponse オブジェクトに格納します。

### delete {#delete-java.lang.String-int:A-java.lang.String-}
入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
ソースファイルから指定されたページを抽出し、結果を HttpServletResponse オブジェクトに格納します。

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
ソースファイルから指定されたページを抽出し、結果を HttpServletResponse オブジェクトに格納します。

### extract {#extract-java.lang.String-int:A-java.lang.String-}
番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。

### extract {#extract-java.lang.String-int-int-java.lang.String-}
入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

非推奨です。このプロパティは非推奨であり、例外をスローできるように使用できません。

**Returns:**
ブール値

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

操作の結果が HttpServletResponse オブジェクトに添付ファイルとして格納されるときの添付ファイル名を取得します。

**Returns:**
string 値

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

true に設定すると、操作後にストリームが閉じられます。

**Returns:**
ブール値

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

UseDiskBuffer が true に設定されている場合、連結中に新しい増分更新が行われるまでに連結されたドキュメント数を示します。

**Returns:**
int 値です。

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

操作の結果が HttpServletResponse オブジェクトに格納されるとき、コンテンツがどのように保存されるかを取得します。

**Returns:**
ContentDisposition 要素

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

変換プロセスのログを取得します。

**Returns:**
string 値

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

true の場合、連結が実行されるときにファイルの論理構造がコピーされます。

**Returns:**
ブール値

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

true の場合、アウトラインがコピーされます。

**Returns:**
ブール値

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。

**Returns:**
ConcatenateCorruptedFileAction 要素

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

連結が実行されたときに発生した問題の配列。

**Returns:**
PdfFileEditor.CorruptedItem 配列

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

連結中に動作し、内部連結ステージのイベントを外部顧客コードに変換する内部プログレスイベントプロセッサの表現です。

**Returns:**
ConcatenationProgressHandler インスタンス

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

true の場合、連結中に増分更新が行われます。

**Returns:**
ブール値

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

true の場合、アクションがソースドキュメントからコピーされます。

**Returns:**
ブール値

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

true の場合、フォームを連結するときにフィールド名が一意になるように作成されます。

**Returns:**
ブール値

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

最後に発生した例外を取得します。

**Returns:**
java.lang.Exception オブジェクト

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。

**Returns:**
ブール値

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

true の場合、重複したアウトラインがマージされます。

**Returns:**
ブール値

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

最適化フラグを取得または設定します。

**Returns:**
ブール値

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを取得します。

**Returns:**
String オブジェクト

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。

**Returns:**
ブール値

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。

**Returns:**
ブール値

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

結果が HttpServletResponse として保存されるときの保存オプションを取得または設定します。

**Returns:**
SaveOptions オブジェクト

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

フォームを連結するときにフィールド名を一意にするために追加されるサフィックスの形式を取得します。

**Returns:**
String オブジェクト

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
ドキュメントを別のドキュメントに挿入し、結果をレスポンスオブジェクトに格納します。

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
別のファイルからページを挿入して、入力 PDF ファイルに追加します。

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
別のファイルからページを挿入して、入力 PDF ファイルに追加します。

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
ファイルの内容をソースファイルに挿入し、結果を HttpServletResponse オブジェクトに格納します。

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
別のファイルからページを挿入して、入力 PDF ファイルに追加します。

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
別のファイルからページを指定位置に挿入して、PDF ファイルに追加します。

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣り合わせに配置して構成されていることがあります。

**Returns:**
ブール値

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。

**Returns:**
ブール値

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
InputStream から outputStream へブックレットを作成します。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
firstInputStream から outputStream へカスタマイズされたブックレットを作成します。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
firstInputStream から outputStream へブックレットを作成します。

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
ソースファイルからブックレットを作成し、結果を HttpServletResponse に格納します。

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
PDF ファイルからブックレットを作成し、結果を HttpServletResponse に格納します。

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
ソースファイルからブックレットを作成し、結果を HttpServletResponse オブジェクトに格納します。

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
ソースファイルからブックレットを作成し、結果を HttpServletResponse オブジェクトに格納します。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
入力ファイルから出力ファイルへブックレットを作成します。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
firstInputFile から outputFile へカスタマイズされたブックレットを作成します。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
inputFile から outputFile へブックレットを作成します。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
firstInputFile から outputFile へカスタマイズされたブックレットを作成します。

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
2 つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
N-up ドキュメントを作成し、結果を HttpServletResponse に格納します。

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
N-up ドキュメントを作成し、結果を HttpServletResponse オブジェクトに格納します。

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
最初の入力ストリームから output stream へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
複数の入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
N-up ドキュメントを作成し、結果を HttpServletResponse に格納します。

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
N-up ドキュメントを作成し、結果を HttpServletResponse オブジェクトに格納します。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
firstInputFile から outputFile へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
入力ファイルから outputFile へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
2 つの入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページサイズを変更します。

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページサイズを変更します。

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
ドキュメントページの内容のサイズを変更します。

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページの内容をリサイズします。

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
ドキュメント内のページの内容をリサイズします。

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
ドキュメント内のページの内容をリサイズします。

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
ドキュメントページの内容のサイズを変更します。

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメント内のページの内容をリサイズします。

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
ドキュメントページの内容のサイズを変更します。

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
ドキュメントページの内容のサイズを変更します。

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページサイズを変更します。

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページサイズを変更します。

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

非推奨です。このプロパティは非推奨であり、例外をスローできるように使用できません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作の結果が HttpServletResponse オブジェクトに添付ファイルとして保存されるときの添付ファイル名を設定します。

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

true に設定すると、操作後にストリームが閉じられます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

UseDiskBuffer が true に設定されている場合、連結中に新しい増分更新が行われるまでに連結されたドキュメント数を示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作の結果が HttpServletResponse オブジェクトに格納される際のコンテンツの保存方法を設定します。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF ファイル形式を設定します。

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

true の場合、連結が実行されるときにファイルの論理構造がコピーされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

true の場合、アウトラインがコピーされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ConcatenateCorruptedFileAction 要素 |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
連結中に動作し、内部連結ステージのイベントを外部顧客コードに変換する内部プログレスイベントプロセッサの表現です。

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

true の場合、連結中に増分更新が行われます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

true の場合、アクションがソースドキュメントからコピーされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

true の場合、フォームを連結するときにフィールド名が一意になるように作成されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

true の場合、重複したアウトラインがマージされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

最適化フラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを設定します。

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpServletResponse として格納される際の保存オプションを設定します。

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣り合わせに配置して構成されていることがあります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | ブール値 |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
フォームが連結されるときにフィールド名が一意になるように付加されるサフィックスの形式を設定します。

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
ドキュメントを開始位置から指定された位置まで分割し、結果を HttpServletResponse オブジェクトに格納します。

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
開始位置から指定された場所まで分割し、前半部分を出力ストリームに保存します。

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
ドキュメントを最初のページから指定位置まで分割し、結果を HttpServletResponse オブジェクトに保存します。

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
PDF ファイルを最初のページから指定された場所まで分割し、前半部分を新しいファイルとして保存します。

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
指定された位置から分割し、後半部分を HttpServletResponse オブジェクトに保存します。

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
指定された位置から分割し、後半部分を HttpServletResponse オブジェクトに保存します。

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
位置から分割し、後半部分を新しいファイルとして保存します。

### splitToPages {#splitToPages-java.io.InputStream-}
PDF ファイルを単一ページのドキュメントに分割します。

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。

### splitToPages {#splitToPages-java.lang.String-}
PDFファイルを単一ページのドキュメントに分割します。

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。
