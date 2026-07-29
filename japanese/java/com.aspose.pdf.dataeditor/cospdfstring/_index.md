---
title: "CosPdfString"
linktitle: "CosPdfString"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは Pdf String オブジェクトを表します。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf.dataeditor/cospdfstring/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfString, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfString

**All Implemented Interfaces:**
ICosPdfPrimitive

```
public final class CosPdfString extends CosPdfPrimitive
```

このクラスは Pdf String オブジェクトを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CosPdfString](#CosPdfString-java.lang.String-) | 新しい {@link CosPdfString} クラスのインスタンスを初期化します。 |
| [CosPdfString](#CosPdfString-java.lang.String-boolean-) | 新しい {@link CosPdfString} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。 |
| [getValue](#getValue--) | 文字列（ANSII）を取得します。値: 文字列。 |
| [hashCode](#hashCode--) | 現在のオブジェクトのハッシュコードを取得します。 |
| [isHexadecimal](#isHexadecimal--) | このインスタンスが十六進数かどうかを示す値を取得します。値: このインスタンスが十六進数の場合は {@code true}、それ以外の場合は {@code false}。 |
| [toCosPdfString](#toCosPdfString--) | このインスタンスを {@link CosPdfString} にキャストしようとします。 |
| [toString](#toString--) | 現在の {@link CosPdfString} を表す {@link String} を返します。 |

### CosPdfString {#CosPdfString-java.lang.String-}
新しい {@link CosPdfString} クラスのインスタンスを初期化します。

### CosPdfString {#CosPdfString-java.lang.String-boolean-}
新しい {@link CosPdfString} クラスのインスタンスを初期化します。

### equals {#equals-java.lang.Object-}
指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。

### getValue {#getValue--}
```
public final String getValue()
```

文字列（ANSII）を取得します。値: 文字列。

**Returns:**
文字列値

### hashCode {#hashCode--}
```
public int hashCode()
```

現在のオブジェクトのハッシュコードを取得します。

**Returns:**
現在のオブジェクトのハッシュコード。

### isHexadecimal {#isHexadecimal--}
```
public final boolean isHexadecimal()
```

このインスタンスが十六進数かどうかを示す値を取得します。値: このインスタンスが十六進数の場合は {@code true}、それ以外の場合は {@code false}。

**Returns:**
ブール値

### toCosPdfString {#toCosPdfString--}
```
public CosPdfString toCosPdfString()
```

このインスタンスを {@link CosPdfString} にキャストしようとします。

**Returns:**
インスタンスが {@link CosPdfString} でない場合は null、そうであれば {@link CosPdfString}。

### toString {#toString--}
```
public String toString()
```

現在の {@link CosPdfString} を表す {@link String} を返します。

**Returns:**
現在の {@link CosPdfString} を表す {@link String}。
