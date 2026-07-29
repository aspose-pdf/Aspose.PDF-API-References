---
title: "スタンプ"
linktitle: "スタンプ"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "スタンプを表すクラスです。"
type: docs
weight: 700
url: /ja/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

スタンプを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Stamp](#Stamp--) | Stamp オブジェクトのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | スタンプとして使用される画像を設定します。 |
| [bindImage](#bindImage-java.lang.String-) | <p> 画像をスタンプとして設定します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | テキストをスタンプとして設定します。 |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> スタンプとして使用される PDF ファイルとページ番号を設定します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> スタンプとして使用される PDF ファイルとページ番号を設定します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | スタンプテキストのテキスト状態を設定します。 |
| [close](#close--) | このインスタンスを閉じます |
| [getBlendingSpace](#getBlendingSpace--) | ページ上で透過およびブレンド操作を実行するために使用されるカラースペースを定義する BlendingColorSpace 値を取得します。 |
| [getOpacity](#getOpacity--) | スタンプの不透明度を取得します。 |
| [getPageNumber](#getPageNumber--) | ページ番号を取得します。 |
| [getPages](#getPages--) | スタンプの影響を受けるページ番号の配列を取得します。 |
| [getQuality](#getQuality--) | 画像スタンプの品質をパーセンテージで取得します。有効な値は 0..100% です。 |
| [getRotation](#getRotation--) | スタンプの回転角度（度）を取得します。 |
| [getStampId](#getStampId--) | スタンプの識別子を取得します。 |
| [isBackground](#isBackground--) | 背景ステータスを取得します。true の場合、スタンプは対象ページの背景として配置されます。デフォルトは false に設定されています。 |
| [setBackground](#setBackground-boolean-) | 背景ステータスを設定します。true の場合、スタンプは対象ページの背景として配置されます。デフォルトは false に設定されています。 |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | ページ上で透過およびブレンド操作を実行するために使用されるカラースペースを定義する BlendingColorSpace 値を設定します。 |
| [setImageSize](#setImageSize-float-float-) | 画像スタンプのサイズを設定します。画像は指定された値に従ってスケーリングされます。 |
| [setOpacity](#setOpacity-float-) | スタンプの不透明度を設定します。 |
| [setOrigin](#setOrigin-float-float-) | スタンプが配置されるページ上の位置を設定します。 |
| [setPageNumber](#setPageNumber-int-) | ページ番号を設定します。 |
| [setPages](#setPages-int:A-) | <p> スタンプの影響を受けるページ番号の配列を設定します。Pages が null の場合、ドキュメントのすべてのページが対象となります。 </p> |
| [setQuality](#setQuality-int-) | 画像スタンプの品質をパーセンテージで設定します。有効な値は 0..100% です。 |
| [setRotation](#setRotation-float-) | <p> スタンプの回転角度（度単位）を取得または設定します。 </p> |
| [setStampId](#setStampId-int-) | スタンプの識別子を設定します。 |

### Stamp {#Stamp--}
```
public Stamp()
```

Stamp オブジェクトのコンストラクタです。

### bindImage {#bindImage-java.io.InputStream-}
スタンプとして使用される画像を設定します。

### bindImage {#bindImage-java.lang.String-}
<p> 画像をスタンプとして設定します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
テキストをスタンプとして設定します。

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> スタンプとして使用される PDF ファイルとページ番号を設定します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> スタンプとして使用される PDF ファイルとページ番号を設定します。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
スタンプテキストのテキスト状態を設定します。

### close {#close--}
```
public void close()
```

このインスタンスを閉じます

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

ページ上で透過およびブレンド操作を実行するために使用されるカラースペースを定義する BlendingColorSpace 値を取得します。

**Returns:**
int 値 @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

スタンプの不透明度を取得します。

**Returns:**
float 値

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

ページ番号を取得します。

**Returns:**
int 値です。

### getPages {#getPages--}
```
public int[] getPages()
```

スタンプの影響を受けるページ番号の配列を取得します。

**Returns:**
int 配列

### getQuality {#getQuality--}
```
public int getQuality()
```

画像スタンプの品質をパーセンテージで取得します。有効な値は 0..100% です。

**Returns:**
int 値です。

### getRotation {#getRotation--}
```
public float getRotation()
```

スタンプの回転角度（度）を取得します。

**Returns:**
float 値

### getStampId {#getStampId--}
```
public int getStampId()
```

スタンプの識別子を取得します。

**Returns:**
int 値です。

### isBackground {#isBackground--}
```
public boolean isBackground()
```

背景ステータスを取得します。true の場合、スタンプは対象ページの背景として配置されます。デフォルトは false に設定されています。

**Returns:**
ブール値

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

背景ステータスを設定します。true の場合、スタンプは対象ページの背景として配置されます。デフォルトは false に設定されています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
ページ上で透過およびブレンド操作を実行するために使用されるカラースペースを定義する BlendingColorSpace 値を設定します。

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

画像スタンプのサイズを設定します。画像は指定された値に従ってスケーリングされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の幅。 |
| 高さ |  | 画像の高さ。 |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

スタンプの不透明度を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

スタンプが配置されるページ上の位置を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| originX |  | スタンプの X 座標。 |
| originY |  | スタンプの Y 座標。 |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

ページ番号を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> スタンプの影響を受けるページ番号の配列を設定します。Pages が null の場合、ドキュメントのすべてのページが対象となります。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 配列 <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

画像スタンプの品質をパーセンテージで設定します。有効な値は 0..100% です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> スタンプの回転角度（度単位）を取得または設定します。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

スタンプの識別子を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
