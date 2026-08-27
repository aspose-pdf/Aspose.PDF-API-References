---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルにスタンプ（透かしまたは背景）を追加するためのインターフェイス。"
type: docs
weight: 320
url: /ja/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

PDF ファイルにスタンプ（透かしまたは背景）を追加するためのインターフェイス。

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

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | ドキュメントのページにフッターを追加します。 |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | ドキュメントのページにフッターを追加します。 |
| [addFooter](#addFooter-java.io.InputStream-float-) | ページのフッターとして画像を追加します。 |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | ページのフッターとして画像を追加します。 |
| [addFooter](#addFooter-java.lang.String-float-) | ドキュメントのページにフッターとして画像を追加します。 |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | ページのフッターとして画像を追加します。 |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | ページにヘッダーを追加します。 |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | ファイルのページにヘッダーを追加します。 |
| [addHeader](#addHeader-java.io.InputStream-float-) | ページ上にヘッダーとして画像を追加します。 |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | ページ上部に画像を追加します。 |
| [addHeader](#addHeader-java.lang.String-float-) | ファイルのページにヘッダーとして画像を追加します。 |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | ページ上にヘッダーとして画像を追加します。 |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | ページにページ番号を追加します。 |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | ページ上の指定された位置にページ番号を追加します。 |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | ページにページ番号を追加します。 |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | ドキュメントのページにページ番号を追加します。 |
| [addPageNumber](#addPageNumber-java.lang.String-) | ファイルにページ番号を追加します。 |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | ページ上の指定された位置にページ番号を追加します。 |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | ページにページ番号を追加します。 |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | ドキュメントのページにページ番号を追加します。 |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | ファイルにスタンプを追加します。 |
| [close](#close--) | 開かれたファイルを閉じ、変更を保存します。 |
| [dispose](#dispose--) | 非推奨です。 |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを取得します。 |
| [getDocument](#getDocument--) | PdfFileStamp が処理しているドキュメントを取得します。 |
| [getInputFile](#getInputFile--) | 入力ファイルの名前とパスを取得します。 |
| [getInputStream](#getInputStream--) | 入力ストリームを取得します。 |
| [getKeepSecurity](#getKeepSecurity--) | true の場合、セキュリティを保持します。 |
| [getOutputFile](#getOutputFile--) | 出力ファイルの名前とパスを取得します。 |
| [getOutputStream](#getOutputStream--) | 出力ストリームを取得します。 |
| [getPageHeight](#getPageHeight--) | ソースファイルの最初のページの高さを取得します。 |
| [getPageNumberRotation](#getPageNumberRotation--) | ページ番号の回転を取得します。 |
| [getPageWidth](#getPageWidth--) | 入力ファイルの最初のページの幅を取得します。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpResponse として格納される際の保存オプションを取得します。 |
| [getStartingNumber](#getStartingNumber--) | 入力ファイルの最初のページの開始番号を取得または設定します。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF ファイル形式を設定します。 |
| [setInputFile](#setInputFile-java.lang.String-) | 入力ファイルの名前とパスを設定します。 |
| [setInputStream](#setInputStream-java.io.InputStream-) | 入力ストリームを設定します。 |
| [setKeepSecurity](#setKeepSecurity-boolean-) | セキュリティ保持を設定します。 |
| [setOutputFile](#setOutputFile-java.lang.String-) | 出力ファイルの名前とパスを設定します。 |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | 出力ストリームを取得または設定します。 |
| [setPageNumberRotation](#setPageNumberRotation-float-) | ページ番号の回転を設定します。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpResponse として格納される際の保存オプションを設定します。 |
| [setStartingNumber](#setStartingNumber-int-) | 入力ファイルの最初のページの開始番号を設定します。 |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

左下の位置。

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

下部中央の位置。

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

右下の位置。

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

左の位置。

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

右の位置。

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

左上の位置。

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

上部中央の位置。

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

右上の位置。

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
ドキュメントのページにフッターを追加します。

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
ドキュメントのページにフッターを追加します。

### addFooter {#addFooter-java.io.InputStream-float-}
ページのフッターとして画像を追加します。

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
ページのフッターとして画像を追加します。

### addFooter {#addFooter-java.lang.String-float-}
ドキュメントのページにフッターとして画像を追加します。

### addFooter {#addFooter-java.lang.String-float-float-float-}
ページのフッターとして画像を追加します。

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
ページにヘッダーを追加します。

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
ファイルのページにヘッダーを追加します。

### addHeader {#addHeader-java.io.InputStream-float-}
ページ上にヘッダーとして画像を追加します。

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
ページ上部に画像を追加します。

### addHeader {#addHeader-java.lang.String-float-}
ファイルのページにヘッダーとして画像を追加します。

### addHeader {#addHeader-java.lang.String-float-float-float-}
ページ上にヘッダーとして画像を追加します。

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
ページにページ番号を追加します。

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
ページ上の指定された位置にページ番号を追加します。

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
ページにページ番号を追加します。

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
ドキュメントのページにページ番号を追加します。

### addPageNumber {#addPageNumber-java.lang.String-}
ファイルにページ番号を追加します。

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
ページ上の指定された位置にページ番号を追加します。

### addPageNumber {#addPageNumber-java.lang.String-int-}
ページにページ番号を追加します。

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
ドキュメントのページにページ番号を追加します。

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
ファイルにスタンプを追加します。

### close {#close--}
```
void close()
```

開かれたファイルを閉じ、変更を保存します。

### dispose {#dispose--}
```
@Deprecated void dispose()
```

非推奨です。

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。

**Returns:**
文字列値

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを取得します。

**Returns:**
ContentDisposition 要素

### getDocument {#getDocument--}
```
IDocument getDocument()
```

PdfFileStamp が処理しているドキュメントを取得します。

**Returns:**
IDocument オブジェクト

### getInputFile {#getInputFile--}
```
String getInputFile()
```

入力ファイルの名前とパスを取得します。

**Returns:**
String オブジェクト

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

入力ストリームを取得します。

**Returns:**
InputStream オブジェクト

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

true の場合、セキュリティを保持します。

**Returns:**
ブール値

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

出力ファイルの名前とパスを取得します。

**Returns:**
String オブジェクト

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

出力ストリームを取得します。

**Returns:**
OutputStream オブジェクト

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

ソースファイルの最初のページの高さを取得します。

**Returns:**
float 値

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

ページ番号の回転を取得します。

**Returns:**
float 値

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

入力ファイルの最初のページの幅を取得します。

**Returns:**
float 値

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

結果が HttpResponse として格納される際の保存オプションを取得します。

**Returns:**
SaveOptions オブジェクト

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

入力ファイルの最初のページの開始番号を取得または設定します。

**Returns:**
int 値です。

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF ファイル形式を設定します。

### setInputFile {#setInputFile-java.lang.String-}
入力ファイルの名前とパスを設定します。

### setInputStream {#setInputStream-java.io.InputStream-}
入力ストリームを設定します。

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

セキュリティ保持を設定します。

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
void setPageNumberRotation(float value)
```

ページ番号の回転を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpResponse として格納される際の保存オプションを設定します。

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

入力ファイルの最初のページの開始番号を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
