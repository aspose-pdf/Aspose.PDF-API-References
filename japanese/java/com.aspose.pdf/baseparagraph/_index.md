---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページに追加できる抽象基底オブジェクト（doc.Paragraphs.Add()）を表します。"
type: docs
weight: 280
url: /ja/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

ページに追加できる抽象基底オブジェクト（doc.Paragraphs.Add()）を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | このインスタンスをクローンします。仮想メソッド。常に null を返します。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 段落の水平配置を取得します |
| [getHyperlink](#getHyperlink--) | / * / * 段落が脚注かどうかを取得または設定します。デフォルトは false です。(PDF 生成用) / * / * |
| [getMargin](#getMargin--) | 段落の外側余白を取得します (PDF 生成用) |
| [getVerticalAlignment](#getVerticalAlignment--) | 段落の垂直配置を取得します |
| [getZIndex](#getZIndex--) | グラフの Z 順序を示す int 値を取得します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。(PDF 生成用) |
| [isInLineParagraph](#isInLineParagraph--) | 段落がインラインかどうかを取得します。デフォルトは false です。(PDF 生成用) |
| [isInNewPage](#isInNewPage--) | この段落が新しいページで生成されるよう強制するかどうかを示す bool 値を取得します。デフォルトは false です。(PDF 生成用) |
| [isKeptWithNext](#isKeptWithNext--) | 現在の段落が次の段落と同じページに残るかどうかを示す boolean 値を取得します。デフォルトは false です。(PDF 生成用) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。(PDF 生成用) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 段落の水平配置を設定します |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | ハイパーリンクを設定します (PDF ジェネレータ用)。 |
| [setInLineParagraph](#setInLineParagraph-boolean-) | 段落をインラインに設定します。デフォルトは false です。(PDF 生成用) |
| [setInNewPage](#setInNewPage-boolean-) | この段落が新しいページで生成されるよう強制する boolean 値を設定します。デフォルトは false です。(PDF 生成用) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | 現在の段落が次の段落と同じページに残るかどうかを示す boolean 値を設定します。デフォルトは false です。(PDF 生成用) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 段落の外側余白を設定します (PDF 生成用) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 段落の垂直配置を設定します |
| [setZIndex](#setZIndex-int-) | グラフの Z 順序を示す int 値を設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

このインスタンスをクローンします。仮想メソッド。常に null を返します。

**Returns:**
Null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

段落の水平配置を取得します

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * 段落が脚注かどうかを取得または設定します。デフォルトは false です。(PDF 生成用) / * / *

**Returns:**
boolean 値 /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

段落の外側余白を取得します (PDF 生成用)

**Returns:**
MarginInfo 値

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

段落の垂直配置を取得します

**Returns:**
VerticalAlignment 要素 @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

グラフの Z 順序を示す int 値を取得します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。

**Returns:**
int 値です。

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。(PDF 生成用)

**Returns:**
ブール値

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

段落がインラインかどうかを取得します。デフォルトは false です。(PDF 生成用)

**Returns:**
ブール値

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

この段落が新しいページで生成されるよう強制するかどうかを示す bool 値を取得します。デフォルトは false です。(PDF 生成用)

**Returns:**
ブール値

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

現在の段落が次の段落と同じページに残るかどうかを示す boolean 値を取得します。デフォルトは false です。(PDF 生成用)

**Returns:**
ブール値

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。(PDF 生成用)

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
段落の水平配置を設定します

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
ハイパーリンクを設定します (PDF ジェネレータ用)。

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

段落をインラインに設定します。デフォルトは false です。(PDF 生成用)

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

この段落が新しいページで生成されるよう強制する boolean 値を設定します。デフォルトは false です。(PDF 生成用)

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

現在の段落が次の段落と同じページに残るかどうかを示す boolean 値を設定します。デフォルトは false です。(PDF 生成用)

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
段落の外側余白を設定します (PDF 生成用)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
段落の垂直配置を設定します

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

グラフの Z 順序を示す int 値を設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
