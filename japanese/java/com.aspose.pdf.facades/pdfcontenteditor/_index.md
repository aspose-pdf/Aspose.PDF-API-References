---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルの内容を編集するクラスを表します。"
type: docs
weight: 380
url: /ja/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

PDF ファイルの内容を編集するクラスを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | ドキュメントイベントの種類です。ドキュメントを閉じます。 |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | ドキュメントイベントの種類です。ドキュメントを開きます。 |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | ドキュメントイベントの種類です。印刷後にアクションを実行します。 |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | ドキュメントイベントの種類です。保存後にアクションを実行します。 |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | ドキュメントイベントの種類です。印刷前にアクションを実行します。 |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | ドキュメントイベントの種類です。保存前にアクションを実行します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | PdfContentEditor オブジェクトのコンストラクタです。 |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | PdfContentEditor オブジェクトのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> ドキュメントイベントに追加のアクションを追加します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> ドキュメントに注釈なしで添付ファイルを追加します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> ドキュメントに注釈なしで添付ファイルを追加します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | PDF ストリームを編集用にバインドします。 |
| [bindPdf](#bindPdf-java.lang.String-) | PDF ファイルを編集用にバインドします。 |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> ビュー設定を変更します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | 開かれたドキュメントを閉じます。 |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | PDF ドキュメント内でアプリケーションを起動するリンクを作成します。 |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | PDF ドキュメント内でアプリケーションを起動するリンクを作成します。 |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | PDF ドキュメント内でアプリケーションを起動するリンクを作成します。 |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | 指定されたアクションを持つブックマークを作成します。 |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | キャレット注釈を作成します。 |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | PDF ドキュメント内のカスタムアクションへのリンクを作成します。 |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | ファイル添付注釈を作成します。 |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | ファイル添付注釈を作成します。 |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | PDFドキュメントにフリーテキスト注釈を作成します |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | PDFドキュメントにJavaScriptへのリンクを作成します。 |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | 線注釈を作成します。 |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | PDFドキュメントにローカルリンクを作成します。 |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | PDFドキュメントにローカルリンクを作成します。 |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | PDFドキュメントにローカルリンクを作成します。 |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | PDFドキュメントにマークアップ注釈を作成します。 |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | 別のPDFドキュメントページへのリンクを作成します。 |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | 別のPDFドキュメントページへのリンクを作成します。 |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | 別のPDFドキュメントページへのリンクを作成します。 |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | ポリゴン注釈を作成します。 |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | ポリライン注釈を作成します。 |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | PDFドキュメントにポップアップ注釈を作成します。 |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | ゴム印注釈を作成します。 |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | ゴム印注釈を作成します。 |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | ゴム印注釈を作成します。 |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | 四角形・円形注釈を作成します。 |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | PDFドキュメントにテキスト注釈を作成します |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | PDFドキュメントにウェブリンクを作成します。 |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | PDFドキュメントにウェブリンクを作成します。 |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | PDFドキュメントにウェブリンクを作成します。 |
| [deleteAttachments](#deleteAttachments--) | <p> PDFドキュメント内のすべての添付ファイルを削除します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> PDFドキュメントからすべての画像を削除します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> 指定されたページの指定された画像を削除します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> 指定されたページでスタンプインデックスにより複数のスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> ドキュメントのすべてのページからIDでスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> 指定されたページでスタンプIDによりスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> ドキュメントのすべてのページから指定されたIDのスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> 指定されたページで複数のスタンプIDによりスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | 曲線注釈を作成します。 |
| [extractLink](#extractLink--) | <p> PDFドキュメントに含まれるLinkインスタンスのコレクションを抽出します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | テキスト置換操作のパラメータセットを取得します |
| [getStamps](#getStamps-int-) | ページ上のスタンプ配列を返します。 |
| [getTextEditOptions](#getTextEditOptions--) | テキスト編集オプションを取得します。 |
| [getTextReplaceOptions](#getTextReplaceOptions--) | テキスト置換オプションを取得します。 |
| [getTextSearchOptions](#getTextSearchOptions--) | テキスト検索オプションを取得します。 |
| [getViewerPreference](#getViewerPreference--) | <p> ビュー設定を返します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | スタンプを非表示にします。非表示にした後、スタンプの表示は ShowStampById メソッドで復元できる場合があります。 |
| [moveStamp](#moveStamp-int-int-double-double-) | ページ上のスタンプの位置を変更します。 |
| [moveStampById](#moveStampById-int-int-double-double-) | ページ上のスタンプの位置を変更します。 |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> ドキュメントからオープンアクションを削除します。 この操作は、起動時に明示的な 'GoTo' アクションを使用する複数のドキュメントを結合する際に便利です。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> PDF ドキュメントの指定ページにある指定画像を別の画像に置き換えます。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> 指定ページの PDF ファイル内のテキストを置き換えます。 </p> <hr> <pre> // この例は、指定ページの PDF ドキュメントでテキストを置き換える方法を示しています。 // ドキュメントを開く Document doc = new Document(inFile); // テキスト編集用の PdfContentEditor オブジェクトを作成 PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // テキストを変更 editor.replaceText("hello world", 1, "hi world"); // ドキュメントを保存 doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // 指定フォントでテキストを変更 editor.replaceText("hello world", 1, "hi world", textState); // ドキュメントを保存 doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> PDF ファイル内のテキストを置き換えます。 </p> <hr> <pre> // この例は、PDF ドキュメントでテキストを置き換える方法を示しています。 // デフォルトでは、最初に見つかったテキストを置き換えます。 // ドキュメントを開く Document doc = new Document(inFile); // テキスト編集用の PdfContentEditor オブジェクトを作成 PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // テキストを変更 editor.replaceText("hello world", "hi world"); // ドキュメントを保存 doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> PDF ファイル内のテキストを置き換え、フォントサイズを設定します。 </p> <hr> <pre> // この例は、テキストを置き換え、新しいテキストのフォントサイズを設定する方法を示しています。 // ドキュメントを開く Document doc = new Document(inFile); // フォントを作成し、埋め込み用にマーク com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // テキスト編集用の PdfContentEditor オブジェクトを作成 PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // 指定フォントでテキストを変更 editor.replaceText("hello world", "hi world", 14); // ドキュメントを保存 doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // 指定フォントでテキストを変更 editor.replaceText("hello world", "hi world", textState); // ドキュメントを保存 doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | テキスト置換操作のパラメータセットを設定します |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | テキスト編集オプションを設定します。 |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | テキスト置換オプションを設定します。 |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | テキスト検索オプションを設定します。 |
| [showStampById](#showStampById-int-int-) | HiddenStampById によって非表示にされたスタンプを表示します。 |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

ドキュメントイベントの種類です。ドキュメントを閉じます。

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

ドキュメントイベントの種類です。ドキュメントを開きます。

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

ドキュメントイベントの種類です。印刷後にアクションを実行します。

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

ドキュメントイベントの種類です。保存後にアクションを実行します。

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

ドキュメントイベントの種類です。印刷前にアクションを実行します。

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

ドキュメントイベントの種類です。保存前にアクションを実行します。

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

PdfContentEditor オブジェクトのコンストラクタです。

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
PdfContentEditor オブジェクトのコンストラクタです。

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> ドキュメントイベントに追加のアクションを追加します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> ドキュメントに注釈なしで添付ファイルを追加します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> ドキュメントに注釈なしで添付ファイルを追加します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
PDF ストリームを編集用にバインドします。

### bindPdf {#bindPdf-java.lang.String-}
PDF ファイルを編集用にバインドします。

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> ビュー設定を変更します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| viewerAttribution |  | ViewerPreference クラスで定義されているビュー属性です。 |

### close {#close--}
```
public void close()
```

開かれたドキュメントを閉じます。

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
PDF ドキュメント内でアプリケーションを起動するリンクを作成します。

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
PDF ドキュメント内でアプリケーションを起動するリンクを作成します。

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
PDF ドキュメント内でアプリケーションを起動するリンクを作成します。

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
指定されたアクションを持つブックマークを作成します。

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
キャレット注釈を作成します。

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
PDF ドキュメント内のカスタムアクションへのリンクを作成します。

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
ファイル添付注釈を作成します。

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
ファイル添付注釈を作成します。

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
PDFドキュメントにフリーテキスト注釈を作成します

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
PDFドキュメントにJavaScriptへのリンクを作成します。

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
線注釈を作成します。

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
PDFドキュメントにローカルリンクを作成します。

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
PDFドキュメントにローカルリンクを作成します。

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
PDFドキュメントにローカルリンクを作成します。

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
PDFドキュメントにマークアップ注釈を作成します。

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
別のPDFドキュメントページへのリンクを作成します。

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
別のPDFドキュメントページへのリンクを作成します。

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
別のPDFドキュメントページへのリンクを作成します。

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
ポリゴン注釈を作成します。

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
ポリライン注釈を作成します。

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
PDFドキュメントにポップアップ注釈を作成します。

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
ゴム印注釈を作成します。

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
ゴム印注釈を作成します。

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
ゴム印注釈を作成します。

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
四角形・円形注釈を作成します。

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
PDFドキュメントにテキスト注釈を作成します

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
PDFドキュメントにウェブリンクを作成します。

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
PDFドキュメントにウェブリンクを作成します。

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
PDFドキュメントにウェブリンクを作成します。

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> PDFドキュメント内のすべての添付ファイルを削除します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> PDFドキュメントからすべての画像を削除します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> 指定されたページの指定された画像を削除します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | 画像を削除するページ番号です。 |
| インデックス |  | 画像のインデックスを表す配列です。 |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> 指定されたページでスタンプインデックスにより複数のスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | スタンプが削除されるページ番号です。 |
| インデックス |  | スタンプのインデックスです。 |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> ドキュメントのすべてのページからIDでスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stampId |  | 削除すべきスタンプの識別子。 |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> 指定されたページでスタンプIDによりスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | スタンプが削除されるページ番号です。 |
| stampId |  | 削除すべきスタンプの識別子。 |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> ドキュメントのすべてのページから指定されたIDのスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stampIds |  | スタンプ ID の配列。 |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> 指定されたページで複数のスタンプIDによりスタンプを削除します。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | スタンプが削除されるページ番号。 |
| stampIds |  | スタンプ ID の配列。 |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
曲線注釈を作成します。

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> PDFドキュメントに含まれるLinkインスタンスのコレクションを抽出します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
Link オブジェクトのコレクション

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

テキスト置換操作のパラメータセットを取得します

**Returns:**
ReplaceTextStrategy 要素

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

ページ上のスタンプ配列を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | スタンプが検索されるページ番号。 |

**Returns:**
スタンプの配列。

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

テキスト編集オプションを取得します。

**Returns:**
TextEditOptions 要素

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

テキスト置換オプションを取得します。

**Returns:**
TextReplaceOptions 要素

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

テキスト検索オプションを取得します。

**Returns:**
TextSearchOptions 要素

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> ビュー設定を返します。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
ViewerPrefernece フラグのセットを返します

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

スタンプを非表示にします。非表示にした後、スタンプの表示は ShowStampById メソッドで復元できる場合があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | ページ番号。 |
| stampId |  | 非表示にすべきスタンプの識別子。 |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

ページ上のスタンプの位置を変更します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | ページ番号。 |
| stampIndex |  | ページ上のスタンプのインデックス。 |
| x |  | 新しいスタンプの水平位置。 |
| y |  | 新しいスタンプの垂直位置。 |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

ページ上のスタンプの位置を変更します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | ページ番号。 |
| stampId |  | 移動すべきスタンプの識別子。 |
| x |  | ページ上の新しいスタンプの水平位置。 |
| y |  | ページ上の新しいスタンプの垂直位置。 |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> ドキュメントからオープンアクションを削除します。 この操作は、起動時に明示的な 'GoTo' アクションを使用する複数のドキュメントを結合する際に便利です。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> PDF ドキュメントの指定ページにある指定画像を別の画像に置き換えます。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> 指定ページの PDF ファイル内のテキストを置き換えます。 </p> <hr> <pre> // この例は、指定ページの PDF ドキュメントでテキストを置き換える方法を示しています。 // ドキュメントを開く Document doc = new Document(inFile); // テキスト編集用の PdfContentEditor オブジェクトを作成 PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // テキストを変更 editor.replaceText("hello world", 1, "hi world"); // ドキュメントを保存 doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> 指定されたページの PDF ファイル内のテキストを置換します。 {@code TextState} オブジェクト（フォントファミリ、カラー）を指定してテキストを置換できます。 </p> <hr> <pre> この例は、PDF ドキュメントの最初のページのテキストを置換し、新しいテキストの {@code TextState} テキストプロパティを設定する方法を示しています。 // ドキュメントを開く Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // テキストを編集するための PdfContentEditor オブジェクトを作成 PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // textState オブジェクトを作成 com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // 指定されたフォントでテキストを変更 editor.replaceText("hello world", 1, "hi world", textState); // ドキュメントを保存 doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> PDF ファイル内のテキストを置き換えます。 </p> <hr> <pre> // この例は、PDF ドキュメントでテキストを置き換える方法を示しています。 // デフォルトでは、最初に見つかったテキストを置き換えます。 // ドキュメントを開く Document doc = new Document(inFile); // テキスト編集用の PdfContentEditor オブジェクトを作成 PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // テキストを変更 editor.replaceText("hello world", "hi world"); // ドキュメントを保存 doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> PDF ファイル内のテキストを置き換え、フォントサイズを設定します。 </p> <hr> <pre> // この例は、テキストを置き換え、新しいテキストのフォントサイズを設定する方法を示しています。 // ドキュメントを開く Document doc = new Document(inFile); // フォントを作成し、埋め込み用にマーク com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // テキスト編集用の PdfContentEditor オブジェクトを作成 PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // 指定フォントでテキストを変更 editor.replaceText("hello world", "hi world", 14); // ドキュメントを保存 doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> 指定された {@code TextState} オブジェクトを使用して PDF ファイル内のテキストを置換します。 </p> <hr> <pre> この例は、テキストを置換し、新しいテキストの {@code TextState} テキストプロパティを設定する方法を示しています。 Document doc = new Document(inFile); // フォントを作成し、埋め込み用にマーク com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // テキストを編集するための PdfContentEditor オブジェクトを作成 PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // textState オブジェクトを作成 com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // 指定されたフォントでテキストを変更 editor.replaceText("hello world", "hi world", textState); // ドキュメントを保存 doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
テキスト置換操作のパラメータセットを設定します

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
テキスト編集オプションを設定します。

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
テキスト置換オプションを設定します。

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
テキスト検索オプションを設定します。

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

HiddenStampById によって非表示にされたスタンプを表示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | ページ番号。 |
| stampId |  | 表示すべきスタンプの識別子。 |
