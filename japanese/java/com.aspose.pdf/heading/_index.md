---
title: "見出し"
linktitle: "見出し"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "見出しを表します。"
type: docs
weight: 1890
url: /ja/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

見出しを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Heading](#Heading--) | 内部使用のみです。 |
| [Heading](#Heading-int-) | Cell クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | すべてのセグメントを含む見出しをクローンします。 |
| [deepClone](#deepClone--) | 見出しをクローンします。 |
| [getDestinationPage](#getDestinationPage--) | 対象ページを取得します。 |
| [getLevel](#getLevel--) | レベルを取得します。 |
| [getStartNumber](#getStartNumber--) | 見出しの開始番号を取得します。 |
| [getStyle](#getStyle--) | スタイルを取得または設定します。 |
| [getTocPage](#getTocPage--) | この見出しを含むページを取得します。 |
| [getTop](#getTop--) | この見出しの上部 Y 座標を取得します（内部使用向け）。 |
| [getUserLabel](#getUserLabel--) | ユーザーラベルを取得または設定します。 |
| [isAutoSequence](#isAutoSequence--) | 見出しが自動的に番号付けされるかどうかを取得します。 |
| [isInList](#isInList--) | 見出しが目次リストに含まれるかどうかを取得します。 |
| [setAutoSequence](#setAutoSequence-boolean-) | 見出しが自動的に番号付けされるかどうかを設定します。 |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | 目的のページを設定します。 |
| [setInList](#setInList-boolean-) | 見出しが目次リストに含まれるかどうかを設定します。 |
| [setLevel](#setLevel-int-) | レベルを設定します。 |
| [setStartNumber](#setStartNumber-int-) | 見出しの開始番号を取得します。値: その startNumber。 |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | スタイルを設定または設定します。 |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | この見出しを含むページを設定します。 |
| [setTop](#setTop-double-) | この見出しの上部 Y を設定します（内部使用）。 |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | ユーザーラベルを取得または設定します。 |

### Heading {#Heading--}
```
public Heading()
```

内部使用のみです。

### Heading {#Heading-int-}
```
public Heading(int level)
```

Cell クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| level |  | 見出しのレベル。 |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

すべてのセグメントを含む見出しをクローンします。

**Returns:**
クローンされたオブジェクト

### deepClone {#deepClone--}
```
public Object deepClone()
```

見出しをクローンします。

**Returns:**
クローンされたオブジェクト

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

対象ページを取得します。

**Returns:**
目的のページ。

### getLevel {#getLevel--}
```
public int getLevel()
```

レベルを取得します。

**Returns:**
見出しのレベル。

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

見出しの開始番号を取得します。

**Returns:**
値: その startNumber。

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

スタイルを取得または設定します。

**Returns:**
見出しのスタイル。

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

この見出しを含むページを取得します。

**Returns:**
ページ。

### getTop {#getTop--}
```
public double getTop()
```

この見出しの上部 Y 座標を取得します（内部使用向け）。

**Returns:**
上部 Y 値

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

ユーザーラベルを取得または設定します。

**Returns:**
TextSegment オブジェクト

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

見出しが自動的に番号付けされるかどうかを取得します。

**Returns:**
その IsAutoSequens。

### isInList {#isInList--}
```
public boolean isInList()
```

見出しが目次リストに含まれるかどうかを取得します。

**Returns:**
その IsInList。

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

見出しが自動的に番号付けされるかどうかを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | その IsAutoSequens。 |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
目的のページを設定します。

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

見出しが目次リストに含まれるかどうかを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | その IsInList。 |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

レベルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 見出しのレベル。 |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

見出しの開始番号を取得します。値: その startNumber。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | その startNumber。 |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
スタイルを設定または設定します。

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
この見出しを含むページを設定します。

### setTop {#setTop-double-}
```
public void setTop(double value)
```

この見出しの上部 Y を設定します（内部使用）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 上部 Y 値 |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
ユーザーラベルを取得または設定します。
