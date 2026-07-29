---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメント内の FloatingBox を表します。FloatingBox はカスタム位置に配置されます。"
type: docs
weight: 1610
url: /ja/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

PDF ドキュメント内の FloatingBox を表します。FloatingBox はカスタム位置に配置されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FloatingBox](#FloatingBox--) | 新しい {@code FloatingBox} クラスのインスタンスを初期化します。 |
| [FloatingBox](#FloatingBox-float-float-) | 指定された幅と高さで新しい {@code FloatingBox} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | 新しい {@code FloatingBox} オブジェクトをクローンします。フローティングボックス内の段落はクローンされません。 |
| [getBackgroundColor](#getBackgroundColor--) | フローティングボックスの背景色を示すオブジェクトを取得します。 |
| [getBackgroundImage](#getBackgroundImage--) | ページの背景画像を取得または設定します（ジェネレータ用のみで、ドキュメントを読み取る際には設定されません）。 |
| [getBorder](#getBorder--) | フローティングボックスの枠情報を示すオブジェクトを取得します。 |
| [getColumnInfo](#getColumnInfo--) | 列情報を取得します。 |
| [getHeight](#getHeight--) | フローティングボックスの高さを示す float 値を取得します。 |
| [getLeft](#getLeft--) | テーブルの左座標を取得します。 |
| [getPadding](#getPadding--) | フローティングボックスの余白を示すオブジェクトを取得します。 |
| [getParagraphs](#getParagraphs--) | セル内のすべての段落を示すコレクションを取得します。 |
| [getPositioningMode](#getPositioningMode--) | ページ上の FloatingBox の位置を決定するバリアントを指定します。 |
| [getTop](#getTop--) | テーブルの上座標を取得します。 |
| [getWidth](#getWidth--) | フローティングボックスの幅を示す float 値を取得します。 |
| [isNeedRepeating](#isNeedRepeating--) | 段落が次のページに繰り返し必要かどうかを示す boolean 値を取得します。デフォルト値は true です。この属性は、段落自体と、その ReferenceParagraphID が参照するオブジェクトの両方が RepeatingRows に含まれている場合にのみ有効です。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | フローティングボックスの背景色を示すオブジェクトを設定します。 |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | ページの背景画像を取得または設定します（ジェネレータ用のみで、ドキュメントを読み取る際には設定されません）。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | フローティングボックスの枠情報を示すオブジェクトを設定します。 |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | 列情報を設定します。 |
| [setHeight](#setHeight-double-) | フローティングボックスの高さを示す float 値を設定します。 |
| [setLeft](#setLeft-double-) | テーブルの左座標を設定します。 |
| [setNeedRepeating](#setNeedRepeating-boolean-) | 段落が次のページに繰り返し必要かどうかを示す boolean 値を設定します。デフォルト値は true です。この属性は、段落自体と、その ReferenceParagraphID が参照するオブジェクトの両方が RepeatingRows に含まれている場合にのみ有効です。 |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | フローティングボックスの余白を示すオブジェクトを設定します。 |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | セル内のすべての段落を示すコレクションを設定します。 |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | ページ上の FloatingBox の位置を決定するバリアントを指定します。 |
| [setTop](#setTop-double-) | テーブルの上端座標を設定します。 |
| [setWidth](#setWidth-double-) | 浮動ボックスの幅を示す float 値を設定します。 |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

新しい {@code FloatingBox} クラスのインスタンスを初期化します。

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

指定された幅と高さで新しい {@code FloatingBox} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | ボックスの幅。 |
| 高さ |  | ボックスの高さ。 |

### deepClone {#deepClone--}
```
public Object deepClone()
```

新しい {@code FloatingBox} オブジェクトをクローンします。フローティングボックス内の段落はクローンされません。

**Returns:**
新しい {@code FloatingBox} オブジェクト。

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

フローティングボックスの背景色を示すオブジェクトを取得します。

**Returns:**
背景色を示すオブジェクト。

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

ページの背景画像を取得または設定します（ジェネレータ用のみで、ドキュメントを読み取る際には設定されません）。

**Returns:**
Image インスタンス

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

フローティングボックスの枠情報を示すオブジェクトを取得します。

**Returns:**
境界情報を示すオブジェクト。

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

列情報を取得します。

**Returns:**
ColumnInfo オブジェクト

### getHeight {#getHeight--}
```
public double getHeight()
```

フローティングボックスの高さを示す float 値を取得します。

**Returns:**
高さを示す値。

### getLeft {#getLeft--}
```
public double getLeft()
```

テーブルの左座標を取得します。

**Returns:**
テーブルの左側座標。

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

フローティングボックスの余白を示すオブジェクトを取得します。

**Returns:**
パディングを示すオブジェクト。

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

セル内のすべての段落を示すコレクションを取得します。

**Returns:**
すべての段落を示すコレクション。

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

ページ上の FloatingBox の位置を決定するバリアントを指定します。

**Returns:**
ParagraphPositioningMode 要素

### getTop {#getTop--}
```
public double getTop()
```

テーブルの上座標を取得します。

**Returns:**
テーブル上部の座標。

### getWidth {#getWidth--}
```
public double getWidth()
```

フローティングボックスの幅を示す float 値を取得します。

**Returns:**
double 値

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

段落が次のページに繰り返し必要かどうかを示す boolean 値を取得します。デフォルト値は true です。この属性は、段落自体と、その ReferenceParagraphID が参照するオブジェクトの両方が RepeatingRows に含まれている場合にのみ有効です。

**Returns:**
ブール値

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
フローティングボックスの背景色を示すオブジェクトを設定します。

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
ページの背景画像を取得または設定します（ジェネレータ用のみで、ドキュメントを読み取る際には設定されません）。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
フローティングボックスの枠情報を示すオブジェクトを設定します。

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
列情報を設定します。

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

フローティングボックスの高さを示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 高さを示す値。 |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

テーブルの左座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | テーブルの左側座標。 |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

段落が次のページに繰り返し必要かどうかを示す boolean 値を設定します。デフォルト値は true です。この属性は、段落自体と、その ReferenceParagraphID が参照するオブジェクトの両方が RepeatingRows に含まれている場合にのみ有効です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
フローティングボックスの余白を示すオブジェクトを設定します。

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
セル内のすべての段落を示すコレクションを設定します。

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
ページ上の FloatingBox の位置を決定するバリアントを指定します。

### setTop {#setTop-double-}
```
public void setTop(double value)
```

テーブルの上端座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | テーブル上部の座標。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

浮動ボックスの幅を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
