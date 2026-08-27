---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "スタンプ情報を表すクラスです。"
type: docs
weight: 710
url: /ja/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

スタンプ情報を表すクラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getForm](#getForm--) | スタンプの XForm を取得します。 |
| [getImage](#getImage--) | スタンプの画像を取得します。スタンプに画像が含まれていない場合（例: テキストスタンプ）は null になる可能性があります。 |
| [getImageInternal](#getImageInternal--) | スタンプの画像を取得します。スタンプに画像が含まれていない場合（例: テキストスタンプ）は null になる可能性があります。 |
| [getIndexOnPage](#getIndexOnPage--) | ページ上のスタンプインデックスを取得します。 |
| [getRectangle](#getRectangle--) | スタンプが配置されている矩形を取得します。 |
| [getStampId](#getStampId--) | スタンプの識別子を取得します。 |
| [getStampType](#getStampType--) | スタンプのタイプ（画像 / フォーム）を取得します。 |
| [getText](#getText--) | スタンプ内のテキストを取得します。 |
| [getVisible](#getVisible--) | スタンプの表示状態を取得します。false の場合、スタンプは非表示になります（HideStampById を使用）。非表示のスタンプは ShowStampById で復元できます。 |

### getForm {#getForm--}
```
public XForm getForm()
```

スタンプの XForm を取得します。

**Returns:**
XForm オブジェクト

### getImage {#getImage--}
```
public BufferedImage getImage()
```

スタンプの画像を取得します。スタンプに画像が含まれていない場合（例: テキストスタンプ）は null になる可能性があります。

**Returns:**
BufferedImage オブジェクト

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

スタンプの画像を取得します。スタンプに画像が含まれていない場合（例: テキストスタンプ）は null になる可能性があります。

**Returns:**
画像オブジェクト

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

ページ上のスタンプインデックスを取得します。

**Returns:**
int 値です。

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

スタンプが配置されている矩形を取得します。

**Returns:**
矩形要素

### getStampId {#getStampId--}
```
public int getStampId()
```

スタンプの識別子を取得します。

**Returns:**
int 値です。

### getStampType {#getStampType--}
```
public StampType getStampType()
```

スタンプのタイプ（画像 / フォーム）を取得します。

**Returns:**
StampType 要素 @see StampType

### getText {#getText--}
```
public String getText()
```

スタンプ内のテキストを取得します。

**Returns:**
文字列値

### getVisible {#getVisible--}
```
public boolean getVisible()
```

スタンプの表示状態を取得します。false の場合、スタンプは非表示になります（HideStampById を使用）。非表示のスタンプは ShowStampById で復元できます。

**Returns:**
ブール値
