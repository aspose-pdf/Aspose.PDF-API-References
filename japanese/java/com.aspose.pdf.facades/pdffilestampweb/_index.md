---
title: "PdfFileStampWeb"
linktitle: "PdfFileStampWeb"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルにスタンプ（透かしまたは背景）を追加するクラスです。HttpServletResponse と連携できるようにします。"
type: docs
weight: 550
url: /ja/java/com.aspose.pdf.facades/pdffilestampweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStampWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStampWeb extends SaveableFacade implements IPdfFileStamp
```

PDF ファイルにスタンプ（透かしまたは背景）を追加するクラスです。HttpServletResponse と連携できるようにします。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | 左下の位置。 |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | 下部中央の位置。 |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | 右下の位置。 |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | 左の位置。 |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | 右の位置。 |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | 左上の位置。 |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | 上部中央の位置。 |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | 右上の位置。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFileStampWeb](#PdfFileStampWeb--) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-) | <p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> ドキュメントのページにフッターを追加します。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> ドキュメントのページにフッターを追加します。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> ページのフッターとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> ページのフッターとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> ドキュメントの各ページのフッターとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | ページのフッターとして画像を追加します。 |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> ページにヘッダーを追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> ファイルのページにヘッダーを追加します。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> ページのヘッダーとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> ページの上部に画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> ファイルの各ページのヘッダーとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> ページのヘッダーとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> ページにページ番号を追加します。ページ番号には # 記号を含めることができ、# はページ番号に置き換えられます。ページ番号はページ下部の水平中央に配置されます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> ページ上の指定位置にページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> ページにページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> ドキュメントの各ページにページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> ファイルにページ番号を追加します。ページ番号テキストには # 記号を含めることができ、# はページ番号に置き換えられます。ページ番号はページ下部の水平中央に配置されます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> ページ上の指定位置にページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> ページにページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> ドキュメントの各ページにページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> ファイルにスタンプを追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> 開いているファイルを閉じて変更を保存します。警告: 入力または出力ストリームが指定されている場合、Close() メソッドではそれらは閉じられません。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | 非推奨です。 |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を取得します。可能な値: inline / attachment。デフォルト: inline。 |
| [getInputFile](#getInputFile--) | 入力ファイルの名前とパスを取得します。 |
| [getInputStream](#getInputStream--) | 入力ストリームを取得します。 |
| [getKeepSecurity](#getKeepSecurity--) | true の場合、セキュリティを保持します。(この機能は次のバージョンで実装される予定です)。 |
| [getNumberingStyle](#getNumberingStyle--) | ページ番号付けスタイルを取得または設定します。 |
| [getOptimizeSize](#getOptimizeSize--) | 最適化フラグを取得または設定します。 |
| [getOutputFile](#getOutputFile--) | 出力ファイルの名前とパスを取得します。 |
| [getOutputStream](#getOutputStream--) | 出力ストリームを取得します。 |
| [getPageHeight](#getPageHeight--) | <p> ソースファイルの最初のページの高さを取得します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre> |
| [getPageNumberRotation](#getPageNumberRotation--) | ページ番号の回転を取得します。回転は度数で表されます。デフォルトは 0 です。 |
| [getPageWidth](#getPageWidth--) | <p> 入力ファイルの最初のページの幅を取得します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre> |
| [getResponse](#getResponse--) | 操作結果が格納される Response オブジェクトを取得します。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpResponse として保存される際の保存オプションを取得します。デフォルト値: PdfSaveOptions。 |
| [getStampId](#getStampId--) | 次に追加されるスタンプのスタンプ ID（ページヘッダー/フッター/ページ番号を含む）。 |
| [getStartingNumber](#getStartingNumber--) | 入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号付けされます。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を設定します。可能な値: inline / attachment。デフォルト: inline。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換せずにデフォルトの PDF 形式で保存されます。 |
| [setInputFile](#setInputFile-java.lang.String-) | 入力ファイルの名前とパスを設定します。 |
| [setInputStream](#setInputStream-java.io.InputStream-) | 入力ストリームを設定します。 |
| [setKeepSecurity](#setKeepSecurity-boolean-) | true の場合、セキュリティを保持します。(この機能は次のバージョンで実装される予定です)。 |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | ページ番号付けスタイルを取得または設定します。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 最適化フラグを取得または設定します。 |
| [setOutputFile](#setOutputFile-java.lang.String-) | 出力ファイルの名前とパスを設定します。 |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | 出力ストリームを取得または設定します。 |
| [setPageNumberRotation](#setPageNumberRotation-float-) | ページ番号の回転を設定します。回転は度数で表されます。デフォルトは 0 です。 |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | 操作結果が格納される Response オブジェクトを設定します。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpResponse として保存される際の保存オプションを設定します。デフォルト値: PdfSaveOptions。 |
| [setStampId](#setStampId-int-) | 次に追加されるスタンプのスタンプ ID（ページヘッダー/フッター/ページ番号を含む）。 |
| [setStartingNumber](#setStartingNumber-int-) | <p> 入力ファイルの最初のページの開始番号を設定します。次のページはこの値から番号付けされます。たとえば StartingNumber を 100 に設定すると、ドキュメントのページ番号は 100、101、102…となります。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

左下の位置。

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

下部中央の位置。

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

右下の位置。

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

左の位置。

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

右の位置。

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

左上の位置。

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

上部中央の位置。

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

右上の位置。

### PdfFileStampWeb {#PdfFileStampWeb--}
```
public PdfFileStampWeb()
```

<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-}
<p> PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティで指定できます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> ドキュメントのページにフッターを追加します。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> ドキュメントのページにフッターを追加します。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> ページのフッターとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> ページのフッターとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> ドキュメントの各ページのフッターとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
ページのフッターとして画像を追加します。

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> ページにヘッダーを追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> ファイルのページにヘッダーを追加します。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> ページのヘッダーとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> ページの上部に画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> ファイルの各ページのヘッダーとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> ページのヘッダーとして画像を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> ページにページ番号を追加します。ページ番号には # 記号を含めることができ、# はページ番号に置き換えられます。ページ番号はページ下部の水平中央に配置されます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> ページ上の指定位置にページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> ページにページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> ドキュメントの各ページにページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> ファイルにページ番号を追加します。ページ番号テキストには # 記号を含めることができ、# はページ番号に置き換えられます。ページ番号はページ下部の水平中央に配置されます。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> ページ上の指定位置にページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> ページにページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> ドキュメントの各ページにページ番号を追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> ファイルにスタンプを追加します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> 開いているファイルを閉じて変更を保存します。警告: 入力または出力ストリームが指定されている場合、Close() メソッドではそれらは閉じられません。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

非推奨です。

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。

**Returns:**
string オブジェクト

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

操作の結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を取得します。可能な値: inline / attachment。デフォルト: inline。

**Returns:**
ContentDisposition 要素

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

入力ファイルの名前とパスを取得します。

**Returns:**
String オブジェクト

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

入力ストリームを取得します。

**Returns:**
InputStream オブジェクト

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

true の場合、セキュリティを保持します。(この機能は次のバージョンで実装される予定です)。

**Returns:**
ブール値

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

ページ番号付けスタイルを取得または設定します。

**Returns:**
NumberingStyle 要素

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

最適化フラグを取得または設定します。

**Returns:**
ブール値

### getOutputFile {#getOutputFile--}
```
public String getOutputFile()
```

出力ファイルの名前とパスを取得します。

**Returns:**
String オブジェクト

### getOutputStream {#getOutputStream--}
```
public OutputStream getOutputStream()
```

出力ストリームを取得します。

**Returns:**
OutputStream オブジェクト

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> ソースファイルの最初のページの高さを取得します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre>

**Returns:**
float 値

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

ページ番号の回転を取得します。回転は度数で表されます。デフォルトは 0 です。

**Returns:**
float 値

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> 入力ファイルの最初のページの幅を取得します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre>

**Returns:**
float 値

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

操作結果が格納される Response オブジェクトを取得します。

**Returns:**
HttpServletResponse オブジェクト

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

結果が HttpResponse として保存される際の保存オプションを取得します。デフォルト値: PdfSaveOptions。

**Returns:**
SaveOptions オブジェクト

### getStampId {#getStampId--}
```
public int getStampId()
```

次に追加されるスタンプのスタンプ ID（ページヘッダー/フッター/ページ番号を含む）。

**Returns:**
int 値です。

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号付けされます。

**Returns:**
int 値です。

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を設定します。可能な値: inline / attachment。デフォルト: inline。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換せずにデフォルトの PDF 形式で保存されます。

### setInputFile {#setInputFile-java.lang.String-}
入力ファイルの名前とパスを設定します。

### setInputStream {#setInputStream-java.io.InputStream-}
入力ストリームを設定します。

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

true の場合、セキュリティを保持します。(この機能は次のバージョンで実装される予定です)。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
ページ番号付けスタイルを取得または設定します。

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

最適化フラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOutputFile {#setOutputFile-java.lang.String-}
出力ファイルの名前とパスを設定します。

### setOutputStream {#setOutputStream-java.io.OutputStream-}
出力ストリームを取得または設定します。

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

ページ番号の回転を設定します。回転は度数で表されます。デフォルトは 0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
操作結果が格納される Response オブジェクトを設定します。

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpResponse として保存される際の保存オプションを設定します。デフォルト値: PdfSaveOptions。

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

次に追加されるスタンプのスタンプ ID（ページヘッダー/フッター/ページ番号を含む）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> 入力ファイルの最初のページの開始番号を設定します。次のページはこの値から番号付けされます。たとえば StartingNumber を 100 に設定すると、ドキュメントのページ番号は 100、101、102…となります。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
