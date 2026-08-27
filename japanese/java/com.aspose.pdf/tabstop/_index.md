---
title: "TabStop"
linktitle: "TabStop"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "段落内のカスタムタブストップ位置を表します。"
type: docs
weight: 4840
url: /ja/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

段落内のカスタムタブストップ位置を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TabStop](#TabStop--) | {@code TabStop} クラスの新しいインスタンスを初期化します。 |
| [TabStop](#TabStop-float-) | 指定された位置で {@code TabStop} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | タブの配置タイプを示す {@code AlignmentType} 列挙体を取得または設定します。 |
| [getLeaderType](#getLeaderType--) | タブリーダータイプを示す {@code TabLeaderType} 列挙体を取得または設定します。 |
| [getPosition](#getPosition--) | タブストップ位置を示す float 値を取得または設定します。 |
| [isReadOnly](#isReadOnly--) | この {@code TabStop} インスタンスが既に {@code TextFragment} に添付され、読み取り専用になっていることを示す値を取得します。 |
| [setAlignmentType](#setAlignmentType-int-) | タブの配置タイプを示す {@code AlignmentType} 列挙体を取得または設定します。 |
| [setLeaderType](#setLeaderType-int-) | タブリーダータイプを示す {@code TabLeaderType} 列挙体を取得または設定します。 |
| [setPosition](#setPosition-float-) | タブストップ位置を示す float 値を設定します。 |

### TabStop {#TabStop--}
```
public TabStop()
```

{@code TabStop} クラスの新しいインスタンスを初期化します。

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

指定された位置で {@code TabStop} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 位置 |  | タブストップの位置です。 |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

タブの配置タイプを示す {@code AlignmentType} 列挙体を取得または設定します。

**Returns:**
TabAlignmentType 要素 @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

タブリーダータイプを示す {@code TabLeaderType} 列挙体を取得または設定します。

**Returns:**
TabLeaderType 要素 @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

タブストップ位置を示す float 値を取得または設定します。

**Returns:**
float 値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

この {@code TabStop} インスタンスが既に {@code TextFragment} に添付され、読み取り専用になっていることを示す値を取得します。

**Returns:**
ブール値

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

タブの配置タイプを示す {@code AlignmentType} 列挙体を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | TabAlignmentType 要素 @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

タブリーダータイプを示す {@code TabLeaderType} 列挙体を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | TabLeaderType 要素 @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

タブストップ位置を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |
