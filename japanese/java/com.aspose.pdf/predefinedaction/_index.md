---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルからトリガー可能なさまざまなアクションを定義します。"
type: docs
weight: 3960
url: /ja/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

PDF ファイルからトリガー可能なさまざまなアクションを定義します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | 現在のブックマークを検索するための名前付きアクションです。 |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | 現在のブックマークをハイライトするための名前付きアクションです。 |
| [Document_AttachFile](#Document_AttachFile) | ファイル添付を追加するための名前付きアクションです。 |
| [Document_CropPages](#Document_CropPages) | 文書ページをトリミングするための名前付きアクション。 |
| [Document_DeletePages](#Document_DeletePages) | 文書ページを削除するための名前付きアクション。 |
| [Document_ExtractPages](#Document_ExtractPages) | 文書ページを抽出するための名前付きアクション。 |
| [Document_InsertPages](#Document_InsertPages) | 文書からページを挿入するための名前付きアクション。 |
| [Document_ReplacePages](#Document_ReplacePages) | 文書ページを置き換えるための名前付きアクション。 |
| [Document_RotatePages](#Document_RotatePages) | 文書ページを回転させるための名前付きアクション。 |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | コメントのスペルチェックを行うための名前付きアクション。 |
| [Edit_Find](#Edit_Find) | 検索するための名前付きアクション。 |
| [Edit_Preferences](#Edit_Preferences) | 設定を編集するための名前付きアクション。 |
| [Edit_Search](#Edit_Search) | 検索のための名前付きアクション。 |
| [File_AttachToEmail](#File_AttachToEmail) | 現在のPDF文書をメールメッセージに添付するための名前付きアクション。 |
| [File_Close](#File_Close) | 文書を閉じるための名前付きアクション。 |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | スキャナーからPDF文書を作成するための名前付きアクション。 |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | ウェブページからPDF文書を作成するための名前付きアクション。 |
| [File_Exit](#File_Exit) | PDFリーダーを終了するための名前付きアクション。 |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | オーガナイザーを開くための名前付きアクション。 |
| [File_Print](#File_Print) | 文書を印刷するための名前付きアクション。 |
| [File_Properties](#File_Properties) | 文書プロパティを開くための名前付きアクション。 |
| [File_SaveAs](#File_SaveAs) | 文書を別名で保存するための名前付きアクション。 |
| [FirstPage](#FirstPage) | 最初のページへ移動するための名前付きアクション。 |
| [LastPage](#LastPage) | 最後のページへ移動するための名前付きアクション。 |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | 文書をズームインするための名前付きアクション。 |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | 文書をズームアウトするための名前付きアクション。 |
| [NextPage](#NextPage) | 次のページへ移動するための名前付きアクション。 |
| [PageImages_PrintPages](#PageImages_PrintPages) | 文書ページを印刷するための名前付きアクション。 |
| [PrevPage](#PrevPage) | 前のページに移動する名前付きアクション。 |
| [Print](#Print) | 印刷ダイアログを開く名前付きアクション。 |
| [PrintDialog](#PrintDialog) | 印刷ダイアログを開く名前付きアクション（JavaScript）。 |
| [View_GoTo_NextView](#View_GoTo_NextView) | 次のビューに移動する名前付きアクション。 |
| [View_GoTo_Page](#View_GoTo_Page) | 特定のページに移動する名前付きアクション。 |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | 前のドキュメントに移動する名前付きアクション。 |
| [View_GoTo_PreView](#View_GoTo_PreView) | 前のビューに移動する名前付きアクション。 |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | 記事パネルを表示/非表示にする名前付きアクション。 |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | 添付ファイルパネルを表示/非表示にする名前付きアクション。 |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | ブックマークパネルを表示/非表示にする名前付きアクション。 |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | コメントパネルを表示/非表示にする名前付きアクション。 |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | フィールドパネルを表示/非表示にする名前付きアクション。 |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | レイヤーパネルを表示/非表示にする名前付きアクション。 |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | モデルツリーパネルを表示/非表示にする名前付きアクション。 |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | ページパネルを表示/非表示にする名前付きアクション。 |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | 署名パネルを表示/非表示にする名前付きアクション。 |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | 単一ページを表示する名前付きアクション。 |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | 単一の連続ページを表示する名前付きアクション。 |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | ページをTwo-Upで表示する名前付きアクション。 |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | ページをTwo-Up連続で表示する名前付きアクション。 |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | 高度な編集ツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | コメントツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | 編集ツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_File](#View_Toolbars_File) | ファイルツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_Find](#View_Toolbars_Find) | 検索ツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | フォームツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | 測定ツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | オブジェクトデータツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | ページ表示ツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | ナビゲーションツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | 印刷プロダクションツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | プロパティツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | 編集ツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | 選択とズームツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | タスクツールバーを表示/非表示にする名前付きアクション。 |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | タイプライターツールバーを表示/非表示にする名前付きアクション。 |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | ページを実際のサイズで表示する名前付きアクション。 |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | ページを高さに合わせて表示する名前付きアクション。 |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | ページに合わせて表示する名前付きアクション。 |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | ページの表示領域に合わせる名前付きアクション。 |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | ページを幅に合わせて表示する名前付きアクション。 |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | ズームを行う名前付きアクション。 |
| [Window_FullScreenMode](#Window_FullScreenMode) | ドキュメントを全画面モードで表示する名前付きアクション。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

現在のブックマークを検索するための名前付きアクションです。

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

現在のブックマークをハイライトするための名前付きアクションです。

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

ファイル添付を追加するための名前付きアクションです。

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

文書ページをトリミングするための名前付きアクション。

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

文書ページを削除するための名前付きアクション。

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

文書ページを抽出するための名前付きアクション。

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

文書からページを挿入するための名前付きアクション。

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

文書ページを置き換えるための名前付きアクション。

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

文書ページを回転させるための名前付きアクション。

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

コメントのスペルチェックを行うための名前付きアクション。

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

検索するための名前付きアクション。

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

設定を編集するための名前付きアクション。

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

検索のための名前付きアクション。

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

現在のPDF文書をメールメッセージに添付するための名前付きアクション。

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

文書を閉じるための名前付きアクション。

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

スキャナーからPDF文書を作成するための名前付きアクション。

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

ウェブページからPDF文書を作成するための名前付きアクション。

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

PDFリーダーを終了するための名前付きアクション。

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

オーガナイザーを開くための名前付きアクション。

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

文書を印刷するための名前付きアクション。

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

文書プロパティを開くための名前付きアクション。

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

文書を別名で保存するための名前付きアクション。

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

最初のページへ移動するための名前付きアクション。

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

最後のページへ移動するための名前付きアクション。

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

文書をズームインするための名前付きアクション。

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

文書をズームアウトするための名前付きアクション。

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

次のページへ移動するための名前付きアクション。

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

文書ページを印刷するための名前付きアクション。

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

前のページに移動する名前付きアクション。

### Print {#Print}
```
public static final PredefinedAction Print
```

印刷ダイアログを開く名前付きアクション。

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

印刷ダイアログを開く名前付きアクション（JavaScript）。

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

次のビューに移動する名前付きアクション。

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

特定のページに移動する名前付きアクション。

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

前のドキュメントに移動する名前付きアクション。

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

前のビューに移動する名前付きアクション。

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

記事パネルを表示/非表示にする名前付きアクション。

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

添付ファイルパネルを表示/非表示にする名前付きアクション。

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

ブックマークパネルを表示/非表示にする名前付きアクション。

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

コメントパネルを表示/非表示にする名前付きアクション。

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

フィールドパネルを表示/非表示にする名前付きアクション。

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

レイヤーパネルを表示/非表示にする名前付きアクション。

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

モデルツリーパネルを表示/非表示にする名前付きアクション。

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

ページパネルを表示/非表示にする名前付きアクション。

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

署名パネルを表示/非表示にする名前付きアクション。

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

単一ページを表示する名前付きアクション。

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

単一の連続ページを表示する名前付きアクション。

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

ページをTwo-Upで表示する名前付きアクション。

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

ページをTwo-Up連続で表示する名前付きアクション。

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

高度な編集ツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

コメントツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

編集ツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

ファイルツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

検索ツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

フォームツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

測定ツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

オブジェクトデータツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

ページ表示ツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

ナビゲーションツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

印刷プロダクションツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

プロパティツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

編集ツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

選択とズームツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

タスクツールバーを表示/非表示にする名前付きアクション。

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

タイプライターツールバーを表示/非表示にする名前付きアクション。

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

ページを実際のサイズで表示する名前付きアクション。

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

ページを高さに合わせて表示する名前付きアクション。

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

ページに合わせて表示する名前付きアクション。

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

ページの表示領域に合わせる名前付きアクション。

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

ページを幅に合わせて表示する名前付きアクション。

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

ズームを行う名前付きアクション。

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

ドキュメントを全画面モードで表示する名前付きアクション。

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static PredefinedAction [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列
