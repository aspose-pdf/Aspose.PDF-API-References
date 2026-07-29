---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントから画像とテキストを抽出するクラスです。"
type: docs
weight: 400
url: /ja/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

PDF ドキュメントから画像とテキストを抽出するクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Pdf ドキュメントを編集用にバインドします。 / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Pdf ドキュメントを編集用にバインドします。 / * / * / * |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> ストリームから PDF ドキュメントをバインドします。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> 入力 PDF ファイルをバインドします。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | Pdf ドキュメントから添付ファイルを抽出します。 |
| [extractAttachment](#extractAttachment-java.lang.String-) | Pdf ドキュメントから添付ファイルを抽出します。 |
| [extractImage](#extractImage--) | <p> PDF ファイルから画像を抽出します。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> すべてのマークドコンテンツコンテナを個別の画像として取得します。 </p> <p> 各マークドコンテンツは、ページのブロック番号を含む {@code MCID_<ID number of block for the page>.png} という名前の PNG 形式画像として保存されます。 |
| [extractText](#extractText--) | <p> Pdf ドキュメントからテキストを抽出します。 </p> <hr> <pre> 最初の例は、PDF ファイルからすべてのテキストを抽出する方法を示します。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> 2 番目の例は、各ページのテキストを 1 つの txt ファイルに抽出する方法を示します。 <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Pdf ドキュメントからテキストを抽出します。 </p> <hr> <pre> 最初の例は、PDF ファイルからすべてのテキストを抽出する方法を示します。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> 2 番目の例は、各ページのテキストを 1 つの txt ファイルに抽出する方法を示します。 <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | 内部使用のみ |
| [getAttachment](#getAttachment--) | <p> すべての添付ファイルをストリームに保存します。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> すべての添付ファイルをストリームに保存します。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | 添付ファイルの一覧を取得します。 |
| [getAttachNames](#getAttachNames--) | <p> PDF ファイル内の添付ファイルの一覧を返します。注: このメソッドを使用する前に ExtractAttachments を呼び出す必要があります。 </p> <hr> <pre> 例は、PDF ファイルから添付ファイル名を抽出する方法を示します。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> 抽出操作が実行されるページ範囲の終了ページを取得します。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> 画像抽出プロセスのモードを設定します。 </p> <hr> デフォルト値は ExtractImageMode.DefinedInResources で、リソースで定義されたすべての画像を抽出します。実際に表示されている画像を抽出するには ExtractImageMode.ActuallyUsed モードを使用する必要があります。 |
| [getExtractTextMode](#getExtractTextMode--) | <p> テキスト抽出結果のモードを取得します。 </p> <hr> <pre> この例は、テキスト抽出シナリオにおける {@code ExtractTextMode} プロパティの使用方法を示します。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> 値: 0 は純粋テキストモード、1 は生の順序モードです。デフォルトは 0 です。 |
| [getNextImage](#getNextImage-java.io.OutputStream-) | PDF ファイルから次の画像を取得し、ストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | PDF ファイルから次の画像を取得し、指定された画像形式でストリームに保存します。 |
| [getNextImage](#getNextImage-java.lang.String-) | <p> PDF ドキュメントから次の画像を取得します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | PDF ドキュメントから指定された画像形式で次の画像を取得します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> 1 ページのテキストをストリームに保存します。 </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> 1 ページのテキストをファイルに保存します。 </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @\"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | 入力ファイルのパスワードを取得します。 |
| [getResolution](#getResolution--) | 抽出された画像の解像度を取得します。既定値は 150 です。解像度が高い画像ほど鮮明になります。ただし、解像度を上げると画像抽出にかかる時間とメモリが増加します。通常、鮮明な画像を得るには解像度を 150 または 300 に設定すれば十分です。 |
| [getStartPage](#getStartPage--) | PDF ドキュメントを表す Pdf.Engine オブジェクトです。 |
| [getText](#getText-java.io.OutputStream-) | テキストをストリームに保存します。詳しくは {@code ExtractText} を参照してください。 |
| [getText](#getText-java.io.OutputStream-boolean-) | テキストをストリームに保存します。詳しくは {@code ExtractText} を参照してください。 |
| [getText](#getText-java.lang.String-) | テキストをファイルに保存します。詳しくは {@code ExtractText} を参照してください。 |
| [getTextSearchOptions](#getTextSearchOptions--) | テキスト検索オプションを取得します。 |
| [hasNextImage](#hasNextImage--) | <p> PDF ドキュメントでさらに画像が取得可能かどうかを確認します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> さらにテキストを取得できるかどうかを示します。 </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | テキストにヘブライ語またはアラビア語の記号が含まれる場合に true になります。このケースは特別に考慮する必要があります。文字列関数の動作が変わり、テキストの処理が右から左へ開始されるためです（数字やその他の非テキスト文字は除く）。 |
| [setEndPage](#setEndPage-int-) | <p> 抽出操作を実行するページ範囲の終了ページを設定します。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> 画像抽出プロセスのモードを設定します。 </p> <hr> デフォルト値は ExtractImageMode.DefinedInResources で、リソースで定義されたすべての画像を抽出します。実際に表示されている画像を抽出するには ExtractImageMode.ActuallyUsed モードを使用する必要があります。 |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> テキスト抽出結果のモードを設定します。 </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> 値: 0 は純粋テキストモード、1 は生の順序モードです。既定は 0 です。 |
| [setPassword](#setPassword-java.lang.String-) | 入力ファイルのパスワードを設定します。 |
| [setResolution](#setResolution-int-) | 抽出された画像の解像度を設定します。既定値は 150 です。解像度が高い画像ほど鮮明になります。ただし、解像度を上げると画像抽出にかかる時間とメモリが増加します。通常、鮮明な画像を得るには解像度を 150 または 300 に設定すれば十分です。 |
| [setStartPage](#setStartPage-int-) | <p> 抽出操作を実行するページ範囲の開始ページを設定します。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | テキスト検索オプションを設定します。 |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Pdf ドキュメントを編集用にバインドします。 / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Pdf ドキュメントを編集用にバインドします。 / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> ストリームから PDF ドキュメントをバインドします。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> 入力 PDF ファイルをバインドします。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Pdf ドキュメントから添付ファイルを抽出します。

### extractAttachment {#extractAttachment-java.lang.String-}
Pdf ドキュメントから添付ファイルを抽出します。

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> PDF ファイルから画像を抽出します。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> すべてのマークドコンテンツコンテナを個別の画像として取得します。 </p> <p> 各マークドコンテンツは、ページのブロック番号を含む {@code MCID_<ID number of block for the page>.png} という名前の PNG 形式画像として保存されます。

### extractText {#extractText--}
```
public void extractText()
```

<p> PDF ドキュメントからテキストを抽出します。 </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> 2 番目の例は、各ページのテキストを 1 つの txt ファイルに抽出する方法を示します。 <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> PDF ドキュメントからテキストを抽出します。 </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> 2 番目の例は、各ページのテキストを 1 つの txt ファイルに抽出する方法を示します。 <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
内部使用のみ

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> すべての添付ファイルをストリームに保存します。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
PDF ドキュメント内の添付ファイルのストリーム配列です。

### getAttachment {#getAttachment-java.lang.String-}
<p> すべての添付ファイルをストリームに保存します。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
PDF ドキュメント内の添付ファイルのストリーム配列です。

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

添付ファイルの一覧を取得します。

**Returns:**
List<FileSpecificatio> を返します。

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> PDF ファイル内の添付ファイルの一覧を返します。注: このメソッドを使用する前に ExtractAttachments を呼び出す必要があります。 </p> <hr> <pre> 例は、PDF ファイルから添付ファイル名を抽出する方法を示します。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
添付ファイルの一覧

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> 抽出操作が実行されるページ範囲の終了ページを取得します。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
終了ページ。

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> 画像抽出プロセスのモードを設定します。 </p> <hr> デフォルト値は ExtractImageMode.DefinedInResources で、リソースで定義されたすべての画像を抽出します。実際に表示されている画像を抽出するには ExtractImageMode.ActuallyUsed モードを使用する必要があります。

**Returns:**
ExtractImageMode の値 @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> 抽出テキスト結果のモードを取得します。 </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> <p> 値: 0 は純粋テキストモードで、1 は生の順序モードです。デフォルトは 0 です。</p>

**Returns:**
抽出テキストの結果。

### getNextImage {#getNextImage-java.io.OutputStream-}
PDF ファイルから次の画像を取得し、ストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
PDF ファイルから次の画像を取得し、指定された画像形式でストリームに保存します。

### getNextImage {#getNextImage-java.lang.String-}
<p> PDF ドキュメントから次の画像を取得します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
PDF ドキュメントから指定された画像形式で次の画像を取得します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> 1 ページのテキストをストリームに保存します。 </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> 1 ページのテキストをファイルに保存します。 </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @\"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

入力ファイルのパスワードを取得します。

**Returns:**
文字列値

### getResolution {#getResolution--}
```
public int getResolution()
```

抽出された画像の解像度を取得します。既定値は 150 です。解像度が高い画像ほど鮮明になります。ただし、解像度を上げると画像抽出にかかる時間とメモリが増加します。通常、鮮明な画像を得るには解像度を 150 または 300 に設定すれば十分です。

**Returns:**
int 値です。

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

PDF ドキュメントを表す Pdf.Engine オブジェクトです。

**Returns:**
ページ範囲の開始ページ。

### getText {#getText-java.io.OutputStream-}
テキストをストリームに保存します。詳しくは {@code ExtractText} を参照してください。

### getText {#getText-java.io.OutputStream-boolean-}
テキストをストリームに保存します。詳しくは {@code ExtractText} を参照してください。

### getText {#getText-java.lang.String-}
テキストをファイルに保存します。詳しくは {@code ExtractText} を参照してください。

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

テキスト検索オプションを取得します。

**Returns:**
テキスト検索オプション。

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> PDF ドキュメントでさらに画像が取得可能かどうかを確認します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

**Returns:**
画像がさらに取得可能な場合は true です。

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> さらにテキストを取得できるかどうかを示します。 </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
テキストをさらに取得できるかどうか、true は取得可能、false は取得不可です。

### isBidi {#isBidi--}
```
public boolean isBidi()
```

テキストにヘブライ語またはアラビア語の記号が含まれる場合に true になります。このケースは特別に考慮する必要があります。文字列関数の動作が変わり、テキストの処理が右から左へ開始されるためです（数字やその他の非テキスト文字は除く）。

**Returns:**
ブール値

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> 抽出操作を実行するページ範囲の終了ページを設定します。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 終了ページ。 |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> 画像抽出プロセスのモードを設定します。 </p> <hr> デフォルト値は ExtractImageMode.DefinedInResources で、リソースで定義されたすべての画像を抽出します。実際に表示されている画像を抽出するには ExtractImageMode.ActuallyUsed モードを使用する必要があります。

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> 抽出テキスト結果のモードを設定します。 </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> <p> 値: 0 は純粋テキストモードで、1 は生の順序モードです。デフォルトは 0 です。</p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 抽出テキストの結果。 |

### setPassword {#setPassword-java.lang.String-}
入力ファイルのパスワードを設定します。

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

抽出された画像の解像度を設定します。既定値は 150 です。解像度が高い画像ほど鮮明になります。ただし、解像度を上げると画像抽出にかかる時間とメモリが増加します。通常、鮮明な画像を得るには解像度を 150 または 300 に設定すれば十分です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> 抽出操作を実行するページ範囲の開始ページを設定します。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ページ範囲の開始ページ。 |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
テキスト検索オプションを設定します。
