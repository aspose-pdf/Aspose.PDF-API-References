---
title: "XImage"
linktitle: "XImage"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "画像 X-Object を表すクラスです。"
type: docs
weight: 5610
url: /ja/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

画像 X-Object を表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | 内部使用のみ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | XImage にステンシルマスクを追加します。 |
| [containsTransparency](#containsTransparency--) | 画像に透明性が含まれている場合は true を返し、そうでない場合は false を返します。 |
| [delete](#delete--) | 画像を親コレクションから削除します。 |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | 画像のカラ―タイプを返します。 |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | XImage の代替テキストの文字列リストを返します。 |
| [getColorType](#getColorType--) | 画像のカラ―タイプを返します。 |
| [getEngineImg](#getEngineImg--) | 画像を記述する IPdfImage オブジェクト。内部使用のみ |
| [getFilterType](#getFilterType--) | 画像フィルターのタイプを取得します。 |
| [getGrayscaled](#getGrayscaled--) | 画像のグレースケール版を取得します。 |
| [getHeight](#getHeight--) | 画像の高さを取得します。 |
| [getImage](#getImage--) | 内部使用のみ |
| [getMetadata](#getMetadata--) | 画像のメタデータ。 |
| [getName](#getName--) | 画像名を取得します。ページコンテンツで参照されている画像の名前を変更すると、ドキュメントが正しくなくなる可能性があることに注意してください。その場合は XImage.Rename メソッドを使用してください。 |
| [getNameInCollection](#getNameInCollection--) | コレクション内の画像の名前を返します。 |
| [getRawBytes](#getRawBytes--) | デコードせずに画像の生バイト列を返します。 |
| [getRawImageData](#getRawImageData--) | ソース画像から生画像データを取得します。 |
| [getRawParameters](#getRawParameters--) | 生画像パラメータを取得します |
| [getWidth](#getWidth--) | 画像の幅を取得します。 |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | プリミティブが画像の場合は true を返します。 |
| [isImageMask](#isImageMask--) | 画像がイメージマスクとして扱われるかどうかを示すフラグを取得します（8.9.6\"Masked Images\"参照）。このフラグが true の場合、BitsPerComponent の値は 1 で、Mask と ColorSpace は指定されません。マスクされていない領域は現在の非ストロークカラーで塗りつぶされます。デフォルト値: false。値: True の場合、画像はイメージマスクです。 |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | 両方の画像が同じオブジェクトを参照している場合は true を返します。 |
| [rename](#rename-java.lang.String-) | 画像の名前を変更し、画像へのすべての参照を新しい名前に置き換えます。 |
| [replace](#replace-java.io.InputStream-) | 画像を {@code image} で指定されたストリームに置き換えます。 * |
| [save](#save-java.io.OutputStream-) | 画像データを JPEG 画像としてストリームに保存します。 |
| [save](#save-java.io.OutputStream-float-float-) | 要求された形式で画像をストリームに保存します。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | 要求された形式で画像をストリームに保存します。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | 要求された形式で画像をストリームに保存します。 |
| [save](#save-java.io.OutputStream-int-) | 指定された解像度で、要求された形式で画像をストリームに保存します。 |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | 要求された形式で画像をストリームに保存します。 |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | 指定された解像度で画像データを JPEG 画像としてストリームに保存します。 |
| [setName](#setName-java.lang.String-) | 画像の名前を設定します。ページ内容で参照されている画像の名前を変更すると、ドキュメントが正しくなくなる可能性があります。その場合は XImage.Rename メソッドを使用してください。 |
| [toStream](#toStream--) | 元の画像ストリームを返します。 |
| [toString](#toString--) | XImage オブジェクトのプロパティを文字列で表現して返します。 |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | ページ上の XImage の代替テキストを設定します。 |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
内部使用のみ

### addStencilMask {#addStencilMask-java.io.InputStream-}
XImage にステンシルマスクを追加します。

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

画像に透明性が含まれている場合は true を返し、そうでない場合は false を返します。

**Returns:**
ブール値

### delete {#delete--}
```
public void delete()
```

画像を親コレクションから削除します。

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
画像のカラ―タイプを返します。

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
XImage の代替テキストの文字列リストを返します。

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

画像のカラ―タイプを返します。

**Returns:**
カラータイプの値です。

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

画像を記述する IPdfImage オブジェクト。内部使用のみ

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

画像フィルターのタイプを取得します。

**Returns:**
ImageFilterType 要素

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

画像のグレースケール版を取得します。

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

画像の高さを取得します。

**Returns:**
int 値です。

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

内部使用のみ

**Returns:**
Image

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

画像のメタデータ。

**Returns:**
Metadata インスタンス

### getName {#getName--}
```
public String getName()
```

画像名を取得します。ページコンテンツで参照されている画像の名前を変更すると、ドキュメントが正しくなくなる可能性があることに注意してください。その場合は XImage.Rename メソッドを使用してください。

**Returns:**
文字列

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

コレクション内の画像の名前を返します。

**Returns:**
画像キー（名前）。

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

デコードせずに画像の生バイト列を返します。

**Returns:**
バイト配列

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

ソース画像から生画像データを取得します。

**Returns:**
元の画像データを含む {@link byte[]}。

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

生画像パラメータを取得します

**Returns:**
RawParameters インスタンス

### getWidth {#getWidth--}
```
public int getWidth()
```

画像の幅を取得します。

**Returns:**
int 値です。

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
プリミティブが画像の場合は true を返します。

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

画像がイメージマスクとして扱われるかどうかを示すフラグを取得します（8.9.6\"Masked Images\"参照）。このフラグが true の場合、BitsPerComponent の値は 1 で、Mask と ColorSpace は指定されません。マスクされていない領域は現在の非ストロークカラーで塗りつぶされます。デフォルト値: false。値: True の場合、画像はイメージマスクです。

**Returns:**
ブール値

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
両方の画像が同じオブジェクトを参照している場合は true を返します。

### rename {#rename-java.lang.String-}
画像の名前を変更し、画像へのすべての参照を新しい名前に置き換えます。

### replace {#replace-java.io.InputStream-}
画像を {@code image} で指定されたストリームに置き換えます。 *

### save {#save-java.io.OutputStream-}
画像データを JPEG 画像としてストリームに保存します。

### save {#save-java.io.OutputStream-float-float-}
要求された形式で画像をストリームに保存します。

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
要求された形式で画像をストリームに保存します。

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
要求された形式で画像をストリームに保存します。

### save {#save-java.io.OutputStream-int-}
指定された解像度で、要求された形式で画像をストリームに保存します。

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
要求された形式で画像をストリームに保存します。

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
指定された解像度で画像データを JPEG 画像としてストリームに保存します。

### setName {#setName-java.lang.String-}
画像の名前を設定します。ページ内容で参照されている画像の名前を変更すると、ドキュメントが正しくなくなる可能性があります。その場合は XImage.Rename メソッドを使用してください。

### toStream {#toStream--}
```
public InputStream toStream()
```

元の画像ストリームを返します。

**Returns:**
元の画像ストリームです。

### toString {#toString--}
```
public String toString()
```

XImage オブジェクトのプロパティを文字列で表現して返します。

**Returns:**
String インスタンス

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
ページ上の XImage の代替テキストを設定します。
