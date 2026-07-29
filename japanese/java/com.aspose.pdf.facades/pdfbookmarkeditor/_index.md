---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルのブックマーク（作成、変更、エクスポート、インポート、削除を含む）を扱うクラスを表します。"
type: docs
weight: 370
url: /ja/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

PDF ファイルのブックマーク（作成、変更、エクスポート、インポート、削除を含む）を扱うクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | 新しい {@code PdfBookmarkEditor} オブジェクトを初期化します。 |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | 新しい {@code PdfBookmarkEditor} オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [close](#close--) | PdfBookmarkEditor のインスタンスを閉じ、リソースを解放します。 |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> 指定されたページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> 指定されたページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> すべてのページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> すべてのページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> すべてのページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> PDF ドキュメントのすべてのブックマークを削除します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> PDF ドキュメントのすべてのブックマークを削除します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> ブックマークを HTML ファイルにエクスポートします。 </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | ブックマークを XML ストリームにエクスポートします。 |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> ブックマークを XML ファイルにエクスポートします。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> ドキュメントからすべてのレベルのブックマークを抽出します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> ドキュメントからすべてのレベルのブックマークを抽出します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | ドキュメントからすべてのレベルのブックマークを抽出します。 |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> ドキュメントからすべてのレベルのブックマークを抽出します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> ブックマークを HTML ファイルにエクスポートします。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | XML ファイルからドキュメントへブックマークをインポートします。 |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> XML ファイルからドキュメントへブックマークをインポートします。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> 指定されたブックマークタイトルに従ってブックマークのタイトルを変更します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

新しい {@code PdfBookmarkEditor} オブジェクトを初期化します。

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
新しい {@code PdfBookmarkEditor} オブジェクトを初期化します。

### close {#close--}
```
public void close()
```

PdfBookmarkEditor のインスタンスを閉じ、リソースを解放します。

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> 指定されたページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> 指定されたページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> すべてのページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> すべてのページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> すべてのページのブックマークを作成します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> PDF ドキュメントのすべてのブックマークを削除します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> PDF ドキュメントのすべてのブックマークを削除します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> ブックマークを HTML ファイルにエクスポートします。 </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
ブックマークを XML ストリームにエクスポートします。

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> ブックマークを XML ファイルにエクスポートします。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> ドキュメントからすべてのレベルのブックマークを抽出します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
ドキュメントに存在するすべてのブックマークのコレクションです。

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> ドキュメントからすべてのレベルのブックマークを抽出します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
ドキュメントに存在するすべてのブックマークのコレクションです。

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

ドキュメントからすべてのレベルのブックマークを抽出します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| upperLevel |  | true の場合、上位レベルのブックマークのみを抽出します。false の場合、すべてのブックマークを再帰的に抽出します。 |

**Returns:**
抽出されたブックマークの一覧。

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> ドキュメントからすべてのレベルのブックマークを抽出します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
ドキュメントに存在するすべてのブックマークのコレクションです。

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> ブックマークを HTML ファイルにエクスポートします。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
XML ファイルからドキュメントへブックマークをインポートします。

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> XML ファイルからドキュメントへブックマークをインポートします。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> 指定されたブックマークタイトルに従ってブックマークのタイトルを変更します。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre>
