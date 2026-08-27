---
title: "PageInfo"
linktitle: "PageInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "pdfジェネレータ用のページ情報を表します。"
type: docs
weight: 3370
url: /ja/java/com.aspose.pdf/pageinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class PageInfo extends Object implements com.aspose.ms.System.ICloneable
```

pdfジェネレータ用のページ情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageInfo](#PageInfo--) | デフォルトコンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | ページ情報をクローンします。 |
| [getAnyMargin](#getAnyMargin--) | 最初のページを除く任意のページの余白を取得または設定します。 |
| [getDefaultTextState](#getDefaultTextState--) | デフォルトフォントを取得します。 |
| [getHeight](#getHeight--) | ページの高さを取得します。 |
| [getMargin](#getMargin--) | ページの余白を取得します。 |
| [getPureHeight](#getPureHeight--) | 余白を除いたページの純粋な高さを取得します。 |
| [getWidth](#getWidth--) | ページの幅を取得します。 |
| [isLandscape](#isLandscape--) | ページが横向きかどうかを取得します。 |
| [setAnyMargin](#setAnyMargin-com.aspose.pdf.MarginInfo-) | 最初のページを除く任意のページの余白を取得または設定します。 |
| [setDefaultTextState](#setDefaultTextState-com.aspose.pdf.TextState-) | デフォルトフォントを設定します。 |
| [setHeight](#setHeight-double-) | ページの高さを設定します。 |
| [setLandscape](#setLandscape-boolean-) | ページが横向きかどうかを設定します。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | ページの余白を設定します。 |
| [setWidth](#setWidth-double-) | ページの幅を設定します。 |

### PageInfo {#PageInfo--}
```
public PageInfo()
```

デフォルトコンストラクタ

### deepClone {#deepClone--}
```
public Object deepClone()
```

ページ情報をクローンします。

**Returns:**
クローンされたオブジェクト

### getAnyMargin {#getAnyMargin--}
```
public final MarginInfo getAnyMargin()
```

最初のページを除く任意のページの余白を取得または設定します。

**Returns:**
MarginInfo インスタンス

### getDefaultTextState {#getDefaultTextState--}
```
public TextState getDefaultTextState()
```

デフォルトフォントを取得します。

**Returns:**
TextState インスタンス

### getHeight {#getHeight--}
```
public double getHeight()
```

ページの高さを取得します。

**Returns:**
double 値

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

ページの余白を取得します。

**Returns:**
MarginInfo 値

### getPureHeight {#getPureHeight--}
```
public double getPureHeight()
```

余白を除いたページの純粋な高さを取得します。

**Returns:**
double 値

### getWidth {#getWidth--}
```
public double getWidth()
```

ページの幅を取得します。

**Returns:**
double 値

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

ページが横向きかどうかを取得します。

**Returns:**
ブール値

### setAnyMargin {#setAnyMargin-com.aspose.pdf.MarginInfo-}
最初のページを除く任意のページの余白を取得または設定します。

### setDefaultTextState {#setDefaultTextState-com.aspose.pdf.TextState-}
デフォルトフォントを設定します。

### setHeight {#setHeight-double-}
```
public final void setHeight(double value)
```

ページの高さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

ページが横向きかどうかを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
ページの余白を設定します。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

ページの幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
