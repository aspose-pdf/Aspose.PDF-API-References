---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルの各ページを画像に変換するクラスを表します。現在、BMP、JPEG、PNG、TIFF をサポートしています。PDF のサポート対象コンテンツ: 画像、フォーム、コメント。"
type: docs
weight: 390
url: /ja/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

PDF ファイルの各ページを画像に変換するクラスを表します。現在、BMP、JPEG、PNG、TIFF をサポートしています。PDF のサポート対象コンテンツ: 画像、フォーム、コメント。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfConverter](#PdfConverter--) | 新しい {@code PdfConverter} オブジェクトを初期化します。 |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | 新しい {@code PdfConverter} オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | PDF ドキュメントを {@link PdfConverter} インスタンスにバインドして、さらに処理できるようにします。 |
| [bindPdf](#bindPdf-java.io.InputStream-) | 変換のために Pdf ストリームをバインドします。 |
| [bindPdf](#bindPdf-java.lang.String-) | 変換のために Pdf ファイルをバインドします。 |
| [close](#close--) | PdfConverter のインスタンスを閉じ、リソースを解放します。 |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | 内部使用のみです。 |
| [dispose](#dispose--) | PdfConverter のインスタンスを閉じ、リソースを解放します。このメソッドは非推奨です。代わりに close() を使用してください。 |
| [doConvert](#doConvert--) | <p> PDF ドキュメントを画像に変換するための初期作業を行います。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | ページ座標タイプ (Media/Crop ボックス) を取得します。デフォルトでは CropBox の値が使用されます。 |
| [getEndPage](#getEndPage--) | 変換したい終了位置を取得します。 |
| [getFormPresentationMode](#getFormPresentationMode--) | フォームの表示モードを取得します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-) | 画像をデフォルトの画像形式（jpeg）でストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | 指定された画像形式で画像をストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | 指定された画像形式、サイズ、品質で画像をストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | 指定された画像形式と品質で画像をストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | 指定された画像形式、サイズ、品質で画像をストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | 指定された画像形式、寸法、品質で画像をストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | 指定されたページサイズで画像をストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | 指定されたページサイズで画像をストリームに保存します。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | 指定されたページサイズ、画像形式、品質で画像をストリームに保存します。 |
| [getNextImage](#getNextImage-java.lang.String-) | 画像をデフォルトの画像形式（jpeg）でファイルに保存します。 |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> 指定された画像形式で画像をファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> 指定された画像形式、画像サイズ、品質で画像をファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | 画像を指定された画像形式と品質でファイルに保存します。 |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> 画像を指定された画像形式と寸法でファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> 画像を指定された画像形式、寸法、品質でファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | 画像を指定されたページサイズとデフォルトの画像形式（jpeg）でファイルに保存します。 |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | 画像を指定されたページサイズと画像形式でファイルに保存します。 |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | 画像を指定されたページサイズ、画像形式、品質でファイルに保存します。 |
| [getPageCount](#getPageCount--) | ページ数を取得します。 |
| [getPassword](#getPassword--) | ドキュメントの所有者パスワードを取得します。 |
| [getRenderingOptions](#getRenderingOptions--) | レンダリング オプションを取得します。 |
| [getResolution](#getResolution--) | 変換中の解像度を取得します。解像度が高いほど変換速度は遅くなります。デフォルト値は150です。 |
| [getStartPage](#getStartPage--) | 変換したい開始位置を取得します。最小値は1です。 |
| [getUserPassword](#getUserPassword--) | ドキュメントのユーザーパスワードを取得します。 |
| [hasNextImage](#hasNextImage--) | PDFファイルにさらに画像があるかどうかを示します。 |
| [isShowHiddenAreas](#isShowHiddenAreas--) | ページ上の非表示領域の表示を制御するフラグを取得します。このメソッドは非推奨です。 |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | 画像ストリームのリストを1つの画像ストリームに結合します。 |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | TIFFストリームのリストを1つのマルチフレームTIFFストリームに結合します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | PDFドキュメントの各ページをページサイズで画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | PDFドキュメントの各ページをページサイズで画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | PDFドキュメントの各ページをページサイズで画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | PDFドキュメントの各ページをページサイズで画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。 |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。 |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。 |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> 各ページのPDFドキュメントを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | 各ページのPDFドキュメントを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。 |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | ページ座標タイプ (Media/Crop ボックス) を設定します。デフォルトでは CropBox の値が使用されます。 |
| [setEndPage](#setEndPage-int-) | 変換したい終了位置を設定します。setStartPage(int) の前に setEndPage(int) を使用してください。 |
| [setFormPresentationMode](#setFormPresentationMode-int-) | フォームの表示モードを設定します。 |
| [setPassword](#setPassword-java.lang.String-) | ドキュメントの OwnerPassword を設定します。 |
| [setRangeOfPages](#setRangeOfPages-int-int-) | 変換したいページの範囲を設定します。 |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | レンダリング オプションを設定します。 |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | 変換中の解像度を設定します。解像度が高いほど、変換速度は遅くなります。デフォルト値は 150 です。 |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | 非推奨です。 |
| [setStartPage](#setStartPage-int-) | 変換したい開始位置を設定します。最小値は 1 です。setStartPage(int) の前に setEndPage(int) を使用してください。 |
| [setUserPassword](#setUserPassword-java.lang.String-) | ドキュメントの UserPassword を設定します。 |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

新しい {@code PdfConverter} オブジェクトを初期化します。

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
新しい {@code PdfConverter} オブジェクトを初期化します。

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
PDF ドキュメントを {@link PdfConverter} インスタンスにバインドして、さらに処理できるようにします。

### bindPdf {#bindPdf-java.io.InputStream-}
変換のために Pdf ストリームをバインドします。

### bindPdf {#bindPdf-java.lang.String-}
変換のために Pdf ファイルをバインドします。

### close {#close--}
```
public void close()
```

PdfConverter のインスタンスを閉じ、リソースを解放します。

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
内部使用のみです。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

PdfConverter のインスタンスを閉じ、リソースを解放します。このメソッドは非推奨です。代わりに close() を使用してください。

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> PDFドキュメントを画像に変換するための初期作業を行います。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

ページ座標タイプ (Media/Crop ボックス) を取得します。デフォルトでは CropBox の値が使用されます。

**Returns:**
PageCoordinateType 要素 @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

変換したい終了位置を取得します。

**Returns:**
int 値です。

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

フォームの表示モードを取得します。

**Returns:**
フォーム表示モード。 @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
画像をデフォルトの画像形式（jpeg）でストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
指定された画像形式で画像をストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
指定された画像形式、サイズ、品質で画像をストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
指定された画像形式と品質で画像をストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
指定された画像形式、サイズ、品質で画像をストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
指定された画像形式、寸法、品質で画像をストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
指定されたページサイズで画像をストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
指定されたページサイズで画像をストリームに保存します。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
指定されたページサイズ、画像形式、品質で画像をストリームに保存します。

### getNextImage {#getNextImage-java.lang.String-}
画像をデフォルトの画像形式（jpeg）でファイルに保存します。

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> 指定された画像形式で画像をファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> 指定された画像形式、画像サイズ、品質で画像をファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
画像を指定された画像形式と品質でファイルに保存します。

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> 指定された画像形式と寸法で画像をファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> 指定された画像形式、寸法、品質で画像をファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
画像を指定されたページサイズとデフォルトの画像形式（jpeg）でファイルに保存します。

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
画像を指定されたページサイズと画像形式でファイルに保存します。

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
画像を指定されたページサイズ、画像形式、品質でファイルに保存します。

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

ページ数を取得します。

**Returns:**
int 値です。

### getPassword {#getPassword--}
```
public String getPassword()
```

ドキュメントの所有者パスワードを取得します。

**Returns:**
文字列値

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

レンダリング オプションを取得します。

**Returns:**
レンダリング オプション。

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

変換中の解像度を取得します。解像度が高いほど変換速度は遅くなります。デフォルト値は150です。

**Returns:**
Resolution 要素

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

変換したい開始位置を取得します。最小値は1です。

**Returns:**
int 値です。

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

ドキュメントのユーザーパスワードを取得します。

**Returns:**
文字列値

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

PDFファイルにさらに画像があるかどうかを示します。

**Returns:**
さらに画像を取得できるかどうかを示します。取得可能なら true、そうでなければ false。

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

ページ上の非表示領域の表示を制御するフラグを取得します。このメソッドは非推奨です。

**Returns:**
ブール値

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
画像ストリームのリストを1つの画像ストリームに結合します。

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
TIFFストリームのリストを1つのマルチフレームTIFFストリームに結合します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
PDFドキュメントの各ページをページサイズで画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
PDFドキュメントの各ページをページサイズで画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> 各ページのPDFドキュメントを画像に変換し、画像を単一のTIFFファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> 各ページのPDFドキュメントを画像に変換し、画像を単一のTIFFファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
PDFドキュメントの各ページを指定された寸法で画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
PDFドキュメントの各ページをページサイズで画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
PDFドキュメントの各ページをページサイズで画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> 各ページのPDFドキュメントを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\Test\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> 各ページのPDFドキュメントを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\Test\test.tiff",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
各ページのPDFドキュメントを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
ページ座標タイプ (Media/Crop ボックス) を設定します。デフォルトでは CropBox の値が使用されます。

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

変換したい終了位置を設定します。setStartPage(int) の前に setEndPage(int) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

フォームの表示モードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | フォーム表示モード。 @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
ドキュメントの OwnerPassword を設定します。

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

変換したいページの範囲を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startPage |  | int 値です。 |
| EndPage |  | int 値です。 |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
レンダリング オプションを設定します。

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
変換中の解像度を設定します。解像度が高いほど、変換速度は遅くなります。デフォルト値は 150 です。

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

非推奨です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

変換したい開始位置を設定します。最小値は 1 です。setStartPage(int) の前に setEndPage(int) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setUserPassword {#setUserPassword-java.lang.String-}
ドキュメントの UserPassword を設定します。
