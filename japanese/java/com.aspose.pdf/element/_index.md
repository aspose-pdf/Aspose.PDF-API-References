---
title: "Element"
linktitle: "Element"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造の基本要素を表すクラス。"
type: docs
weight: 1180
url: /ja/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

論理構造の基本要素を表すクラス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getActualText](#getActualText--) | (Optional; PDF 1.4) テキストは構造要素とその子要素の正確な置き換えです。この置き換えテキストは（可能な限り小さなコンテンツ単位に適用すべき）で、障害を持つユーザーへのアクセシビリティ支援やその他の目的で文書内容を抽出する際に有用です。 |
| [getAlt](#getAlt--) | (Optional) 人が読める形式での構造要素とその子要素の代替説明で、障害を持つユーザーへのアクセシビリティ支援やその他の目的で文書内容を抽出する際に有用です。 |
| [getChildren](#getChildren--) | 子要素コレクションを取得します。 |
| [getE](#getE--) | (Optional; PDF 1.5) 略語の展開形です。 |
| [getLang](#getLang--) | (Optional; PDF 1.4) 構造要素内のすべてのテキストの自然言語を指定する言語で、入れ子の構造要素やマーク付きコンテンツの言語指定で上書きされる場合を除きます。 |
| [remove](#remove--) | 要素を削除します。 |
| [setActualText](#setActualText-java.lang.String-) | (Optional; PDF 1.4) テキストは構造要素とその子要素の正確な置き換えです。この置き換えテキストは（可能な限り小さなコンテンツ単位に適用すべき）で、障害を持つユーザーへのアクセシビリティ支援やその他の目的で文書内容を抽出する際に有用です。 |
| [setAlt](#setAlt-java.lang.String-) | (Optional) 人が読める形式での構造要素とその子要素の代替説明で、障害を持つユーザーへのアクセシビリティ支援やその他の目的で文書内容を抽出する際に有用です。 |
| [setE](#setE-java.lang.String-) | (Optional; PDF 1.5) 略語の展開形です。 |
| [setLang](#setLang-java.lang.String-) | (Optional; PDF 1.4) 構造要素内のすべてのテキストの自然言語を指定する言語で、入れ子の構造要素やマーク付きコンテンツの言語指定で上書きされる場合を除きます。 |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Optional; PDF 1.4) テキストは構造要素とその子要素の正確な置き換えです。この置き換えテキストは（可能な限り小さなコンテンツ単位に適用すべき）で、障害を持つユーザーへのアクセシビリティ支援やその他の目的で文書内容を抽出する際に有用です。

**Returns:**
String オブジェクト

### getAlt {#getAlt--}
```
public String getAlt()
```

(Optional) 人が読める形式での構造要素とその子要素の代替説明で、障害を持つユーザーへのアクセシビリティ支援やその他の目的で文書内容を抽出する際に有用です。

**Returns:**
String オブジェクト

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

子要素コレクションを取得します。

**Returns:**
ElementCollection インスタンス

### getE {#getE--}
```
public String getE()
```

(Optional; PDF 1.5) 略語の展開形です。

**Returns:**
String オブジェクト

### getLang {#getLang--}
```
public String getLang()
```

(Optional; PDF 1.4) 構造要素内のすべてのテキストの自然言語を指定する言語で、入れ子の構造要素やマーク付きコンテンツの言語指定で上書きされる場合を除きます。

**Returns:**
String オブジェクト

### remove {#remove--}
```
public final void remove()
```

要素を削除します。

### setActualText {#setActualText-java.lang.String-}
(Optional; PDF 1.4) テキストは構造要素とその子要素の正確な置き換えです。この置き換えテキストは（可能な限り小さなコンテンツ単位に適用すべき）で、障害を持つユーザーへのアクセシビリティ支援やその他の目的で文書内容を抽出する際に有用です。

### setAlt {#setAlt-java.lang.String-}
(Optional) 人が読める形式での構造要素とその子要素の代替説明で、障害を持つユーザーへのアクセシビリティ支援やその他の目的で文書内容を抽出する際に有用です。

### setE {#setE-java.lang.String-}
(Optional; PDF 1.5) 略語の展開形です。

### setLang {#setLang-java.lang.String-}
(Optional; PDF 1.4) 構造要素内のすべてのテキストの自然言語を指定する言語で、入れ子の構造要素やマーク付きコンテンツの言語指定で上書きされる場合を除きます。
