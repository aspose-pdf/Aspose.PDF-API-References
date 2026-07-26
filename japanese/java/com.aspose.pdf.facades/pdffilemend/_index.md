---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "既存の PDF ドキュメントのページにテキストや画像を追加するクラスを表します。"
type: docs
weight: 500
url: /ja/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

既存の PDF ドキュメントのページにテキストや画像を追加するクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | コンストラクタ。 |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | コンストラクタ。 |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | コンストラクタ。 |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | コンストラクタ。 |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | コンストラクタ。 |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | コンストラクタ。 |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | コンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | 実装されていません。 |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | 実装されていません。 |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | 実装されていません。 |
| [close](#close--) | PdfFileMend オブジェクトを閉じます。 |
| [dispose](#dispose--) | PdfFileMend オブジェクトを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。 |
| [getDocument](#getDocument--) | {@code PdfFileMend} が操作しているドキュメントを取得します。 |
| [getInputFile](#getInputFile--) | 入力ファイルを取得します。 |
| [getInputStream](#getInputStream--) | 入力ストリームを取得します。 |
| [getOutputFile](#getOutputFile--) | 出力ファイルを取得します。 |
| [getOutputStream](#getOutputStream--) | 出力ストリームを取得します。 |
| [getTextPositioningMode](#getTextPositioningMode--) | テキスト配置戦略を取得します。{@code PositioningMode} デフォルトモードは Legacy です。 |
| [getWrapMode](#getWrapMode--) | ワードラップアルゴリズムを取得します。 |
| [save](#save-java.io.OutputStream-) | PDFドキュメントを指定されたファイルに保存します。 |
| [save](#save-java.lang.String-) | PDFドキュメントを指定されたファイルに保存します。 |
| [setInputFile](#setInputFile-java.lang.String-) | 非推奨です。 |
| [setInputStream](#setInputStream-java.io.InputStream-) | 入力ストリームを設定します。 |
| [setOutputFile](#setOutputFile-java.lang.String-) | 出力ファイルを設定します。 |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | このメソッドは非推奨です。Facade の結果を取得するには Save(outputStream) メソッドを使用してください。 |
| [setTextPositioningMode](#setTextPositioningMode-int-) | テキスト配置戦略を設定します。{@code PositioningMode} デフォルトモードは Legacy です。 |
| [setWordWrap](#setWordWrap-boolean-) | AddText メソッドでワードラップを示す bool 値を設定します。値が true の場合、FormattedText のテキストはワードラップされます。デフォルトでは、値は false です。 |
| [setWrapMode](#setWrapMode-int-) | ワードラップアルゴリズムを設定します。 |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

コンストラクタ。

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
コンストラクタ。

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
コンストラクタ。

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
コンストラクタ。

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
コンストラクタ。

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
コンストラクタ。

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
コンストラクタ。

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
実装されていません。

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
実装されていません。

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
実装されていません。

### close {#close--}
```
public void close()
```

PdfFileMend オブジェクトを閉じます。

### dispose {#dispose--}
```
public void dispose()
```

PdfFileMend オブジェクトを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

{@code PdfFileMend} が操作しているドキュメントを取得します。

**Returns:**
IDocument オブジェクト

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

入力ファイルを取得します。

**Returns:**
文字列値

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

入力ストリームを取得します。

**Returns:**
入力ストリーム。

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

出力ファイルを取得します。

**Returns:**
文字列値

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

出力ストリームを取得します。

**Returns:**
出力ストリーム。

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

テキスト配置戦略を取得します。{@code PositioningMode} デフォルトモードは Legacy です。

**Returns:**
PositioningMode 要素 @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

ワードラップアルゴリズムを取得します。

**Returns:**
WordWrapMode 値 @see WordWrapMode

### save {#save-java.io.OutputStream-}
PDFドキュメントを指定されたファイルに保存します。

### save {#save-java.lang.String-}
PDFドキュメントを指定されたファイルに保存します。

### setInputFile {#setInputFile-java.lang.String-}
非推奨です。

### setInputStream {#setInputStream-java.io.InputStream-}
入力ストリームを設定します。

### setOutputFile {#setOutputFile-java.lang.String-}
出力ファイルを設定します。

### setOutputStream {#setOutputStream-java.io.OutputStream-}
このメソッドは非推奨です。Facade の結果を取得するには Save(outputStream) メソッドを使用してください。

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

テキスト配置戦略を設定します。{@code PositioningMode} デフォルトモードは Legacy です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PositioningMode 要素 @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

AddText メソッドでワードラップを示す bool 値を設定します。値が true の場合、FormattedText のテキストはワードラップされます。デフォルトでは、値は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

ワードラップアルゴリズムを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | WordWrapMode 要素 @see WordWrapMode |
