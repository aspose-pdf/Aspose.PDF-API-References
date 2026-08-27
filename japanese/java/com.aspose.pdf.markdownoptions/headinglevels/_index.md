---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォントサイズに基づくヘッダーレベルを操作するクラスを表します。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

フォントサイズに基づくヘッダーレベルを操作するクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | HeadingLevels クラスの新しいインスタンスを作成します。 |
| [HeadingLevels](#HeadingLevels-double-) | HeadingLevels クラスの新しいインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | 見出しレベルを追加します。 |
| [estimateLevel](#estimateLevel-double-) | 可能なヘッダーレベルを推定します。fontSize がレベルのリストに見つからない場合、フォントサイズの値に最も近いレベルが返されます。fontSize が指定された最小および最大ヘッダーレベルの範囲外の場合、メソッドは false を返します。 |
| [findLevel](#findLevel-double-int:A-) | 対応するフォントサイズのレベルを検索します。完全一致を探しています。 |
| [getAllLevels](#getAllLevels--) | すべての見出しレベルを取得します。 |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

HeadingLevels クラスの新しいインスタンスを作成します。

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

HeadingLevels クラスの新しいインスタンスを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threshold |  | threshold 値はフォントサイズを比較するためのものです。threshold の範囲内では、ヘッダーレベルは同じになります。threshold のデフォルト値は 0.01 です。 |

### addLevels {#addLevels-java.lang.Iterable-}
見出しレベルを追加します。

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

可能なヘッダーレベルを推定します。fontSize がレベルのリストに見つからない場合、フォントサイズの値に最も近いレベルが返されます。fontSize が指定された最小および最大ヘッダーレベルの範囲外の場合、メソッドは false を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontSize |  | フォントサイズです。 |

**Returns:**
見出しレベルです。

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

対応するフォントサイズのレベルを検索します。完全一致を探しています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontSize |  | フォントサイズです。 |
| level |  | 指定されたフォントサイズに対応する見出しレベルです。 |

**Returns:**
指定された範囲内に fontSize がない場合は False。

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

すべての見出しレベルを取得します。

**Returns:**
IEnumerable of Double
