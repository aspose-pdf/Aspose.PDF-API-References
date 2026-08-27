---
title: "TextEncodingInternal"
linktitle: "TextEncodingInternal"
second_title: "Java 用 Aspose.PDF API リファレンス"
description:
type: docs
weight: 5030
url: /ja/java/com.aspose.pdf/textencodinginternal/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextEncodingInternal

```
public final class TextEncodingInternal extends Object
```



## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextEncodingInternal](#TextEncodingInternal-com.aspose.ms.System.Text.Encoding-) | 内部コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getASCII](#getASCII--) | ASCII（7ビット）文字セットのエンコーディングを取得します。 |
| [getBigEndianUnicode](#getBigEndianUnicode--) | ビッグエンディアンバイト順を使用する UTF-16 形式のエンコーディングを取得します。 |
| [getDefault](#getDefault--) | オペレーティングシステムの現在の ANSI コードページのエンコーディングを取得します。 |
| [getEncoding](#getEncoding-java.lang.String-) | 指定されたコードページ名に関連付けられたエンコーディングを返します。 |
| [getInternalFormat](#getInternalFormat--) | 内部メソッド |
| [getNames](#getNames--) | エンコーディング名の配列を取得します。 |
| [getString](#getString-byte:A-) | 派生クラスでオーバーライドされた場合、指定されたバイト配列のすべてのバイトを文字列にデコードします。 |
| [getUnicode](#getUnicode--) | リトルエンディアンのバイト順を使用した UTF-16 形式のエンコーディングを取得します。 |
| [getUTF32](#getUTF32--) | リトルエンディアンのバイト順を使用した UTF-32 形式のエンコーディングを取得します。 |
| [getUTF32BE](#getUTF32BE--) | ビッグエンディアンバイト順を使用する UTF-16 形式のエンコーディングを取得します。 |
| [getUTF7](#getUTF7--) | UTF-7 形式のエンコーディングを取得します。 |
| [getUTF8](#getUTF8--) | UTF-8 形式のエンコーディングを取得します。 |
| [getUTF8Unmarked](#getUTF8Unmarked--) | UTF-8 Unmarked 形式のエンコーディングを取得します。 |
| [toString](#toString-com.aspose.pdf.TextEncodingInternal-) | 現在のオブジェクトを表す文字列を返します。 |

### TextEncodingInternal {#TextEncodingInternal-com.aspose.ms.System.Text.Encoding-}
内部コンストラクタ

### getASCII {#getASCII--}
```
public static TextEncodingInternal getASCII()
```

ASCII（7ビット）文字セットのエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### getBigEndianUnicode {#getBigEndianUnicode--}
```
public static TextEncodingInternal getBigEndianUnicode()
```

ビッグエンディアンバイト順を使用する UTF-16 形式のエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### getDefault {#getDefault--}
```
public static TextEncodingInternal getDefault()
```

オペレーティングシステムの現在の ANSI コードページのエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### getEncoding {#getEncoding-java.lang.String-}
指定されたコードページ名に関連付けられたエンコーディングを返します。

### getInternalFormat {#getInternalFormat--}
```
public com.aspose.ms.System.Text.Encoding getInternalFormat()
```

内部メソッド

**Returns:**
内部オブジェクト

### getNames {#getNames--}
```
public static String [] getNames()
```

エンコーディング名の配列を取得します。

**Returns:**
文字列配列

### getString {#getString-byte:A-}
```
public String getString(byte[] value)
```

派生クラスでオーバーライドされた場合、指定されたバイト配列のすべてのバイトを文字列にデコードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | デコードするバイト列を含むバイト配列です。 |

**Returns:**
指定されたバイト列のデコード結果を含む文字列です。

### getUnicode {#getUnicode--}
```
public static TextEncodingInternal getUnicode()
```

リトルエンディアンのバイト順を使用した UTF-16 形式のエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### getUTF32 {#getUTF32--}
```
public static TextEncodingInternal getUTF32()
```

リトルエンディアンのバイト順を使用した UTF-32 形式のエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### getUTF32BE {#getUTF32BE--}
```
public static TextEncodingInternal getUTF32BE()
```

ビッグエンディアンバイト順を使用する UTF-16 形式のエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### getUTF7 {#getUTF7--}
```
public static TextEncodingInternal getUTF7()
```

UTF-7 形式のエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### getUTF8 {#getUTF8--}
```
public static TextEncodingInternal getUTF8()
```

UTF-8 形式のエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### getUTF8Unmarked {#getUTF8Unmarked--}
```
public static TextEncodingInternal getUTF8Unmarked()
```

UTF-8 Unmarked 形式のエンコーディングを取得します。

**Returns:**
TextEncodingInternal インスタンス

### toString {#toString-com.aspose.pdf.TextEncodingInternal-}
現在のオブジェクトを表す文字列を返します。
