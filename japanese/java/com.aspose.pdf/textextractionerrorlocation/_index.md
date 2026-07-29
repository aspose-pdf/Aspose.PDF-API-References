---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト抽出エラーが発生した PDF ドキュメント内の位置を表します。"
type: docs
weight: 5050
url: /ja/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

テキスト抽出エラーが発生した PDF ドキュメント内の位置を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | テキスト抽出エラーを引き起こす演算子の表示に使用される PDF フォントオブジェクトのキー（名前）。 |
| [getFormKey](#getFormKey--) | コンテンツストリームのテキスト抽出エラーが位置する PDF フォーム XObject のキー（名前）。ObjectType が 'xForm' の場合は空ではありません。 |
| [getObjectType](#getObjectType--) | コンテンツストリームのテキスト抽出エラーが位置する PDF オブジェクト（ページまたは xForm）のタイプ。 |
| [getOperatorIndex](#getOperatorIndex--) | テキスト抽出エラーを引き起こすコンテンツストリーム（演算子コレクション）内のテキスト表示演算子のインデックス。 |
| [getOperatorString](#getOperatorString--) | テキスト抽出エラーを引き起こすテキスト表示演算子。 |
| [getPageNumber](#getPageNumber--) | テキスト抽出エラーが発生したドキュメントページの番号。 |
| [getPath](#getPath--) | テキスト抽出エラーが発生したPDFドキュメントの場所。 |
| [getTextStartPoint](#getTextStartPoint--) | テキスト抽出エラーを引き起こす演算子の表示に使用される PDF フォントオブジェクトのキー（名前）。 |
| [toString](#toString--) | 文字列表現を返します。 |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

テキスト抽出エラーを引き起こす演算子の表示に使用される PDF フォントオブジェクトのキー（名前）。

**Returns:**
文字列値

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

コンテンツストリームのテキスト抽出エラーが位置する PDF フォーム XObject のキー（名前）。ObjectType が 'xForm' の場合は空ではありません。

**Returns:**
文字列値

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

コンテンツストリームのテキスト抽出エラーが位置する PDF オブジェクト（ページまたは xForm）のタイプ。

**Returns:**
文字列値

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

テキスト抽出エラーを引き起こすコンテンツストリーム（演算子コレクション）内のテキスト表示演算子のインデックス。

**Returns:**
int 値です。

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

テキスト抽出エラーを引き起こすテキスト表示演算子。

**Returns:**
文字列値

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

テキスト抽出エラーが発生したドキュメントページの番号。

**Returns:**
int 値です。

### getPath {#getPath--}
```
public String getPath()
```

テキスト抽出エラーが発生したPDFドキュメントの場所。

**Returns:**
文字列値

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

テキスト抽出エラーを引き起こす演算子の表示に使用される PDF フォントオブジェクトのキー（名前）。

**Returns:**
Point インスタンス

### toString {#toString--}
```
public String toString()
```

文字列表現を返します。

**Returns:**
文字列表現です。
