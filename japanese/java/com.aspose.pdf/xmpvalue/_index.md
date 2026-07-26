---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XMP 値を表します"
type: docs
weight: 5750
url: /ja/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

XMP 値を表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | 日時値のコンストラクタです。 |
| [XmpValue](#XmpValue-double-) | 浮動小数点値のコンストラクタです。 |
| [XmpValue](#XmpValue-int-) | 整数値のコンストラクタです。 |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | 文字列値のコンストラクタです。 |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | 新しい文字列 XMP 値を初期化します。 |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | 配列値のコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [isArray](#isArray--) | XmpValue が配列の場合は true を返します。 |
| [isDateTime](#isDateTime--) | 値が DateTime の場合は true を返します。 |
| [isDouble](#isDouble--) | 値が浮動小数点値の場合は true を返します。 |
| [isField](#isField--) | XmpValue がフィールドの場合は true を返します。 |
| [isInteger](#isInteger--) | 値が整数の場合は true を返します。 |
| [isNamedValue](#isNamedValue--) | XmpValue が名前付き値の場合は true を返します。 |
| [isNamedValues](#isNamedValues--) | XmpValue が名前付き値を表す場合は true を返します。 |
| [isRaw](#isRaw--) | 値はサポートされていない/不明で、未加工の XML コードが提供されます。 |
| [isString](#isString--) | 値が文字列の場合は true を返します。 |
| [isStructure](#isStructure--) | XmpValue が構造体を表す場合は true を返します。 |
| [to_](#to_-com.aspose.pdf.XmpValue-) | XmpValue を配列に変換します。 |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | XmpValue を配列に変換します。 |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | KeyValuePair 配列を取得します |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | XmpValue を名前付き値に変換します。 |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | XmpValue を文字列に変換します。 |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | DateTime を XmpValue に変換します。 |
| [to_XmpValue](#to_XmpValue-double-) | double を XmpValue に変換します。 |
| [to_XmpValue](#to_XmpValue-int-) | integer を XmpValue に変換します。 |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | 配列を XmpValue に変換します。 |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | 文字列を XmpValue に変換します。 |
| [toArray](#toArray--) | 配列を返します。 |
| [toDateTime](#toDateTime--) | 日付時刻に変換します。 |
| [toDateTimeOffset](#toDateTimeOffset--) | 現在の XMP 値を {@link DateTimeOffset} 表現に変換します。 |
| [toDictionary](#toDictionary--) | 名前付き値を含む辞書を返します。 |
| [toDouble](#toDouble--) | double に変換します。 |
| [toField](#toField--) | XMP フィールドとして XMP 値を返します。 |
| [toInteger](#toInteger--) | 整数に変換します。 |
| [toNamedValue](#toNamedValue--) | 名前付き値として XMP 値を返します。 |
| [toNamedValueInternal](#toNamedValueInternal--) | 内部使用のみ |
| [toNamedValues](#toNamedValues--) | 名前付き値コレクションとして XMP 値を返します。 |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | 不明またはサポートされていない値の生 XML コードです。 |
| [toString](#toString--) | XmpValue の文字列表現を返します。 |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | XmpValue の文字列表現を返します。 |
| [toStringValue](#toStringValue--) | 文字列に変換します。 |
| [toStructure](#toStructure--) | 構造体（フィールドの集合）として XMP 値を返します。 |

### XmpValue {#XmpValue-java.util.Date-}
日時値のコンストラクタです。

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

浮動小数点値のコンストラクタです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | Double 値です。 |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

整数値のコンストラクタです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 整数値です。 |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
文字列値のコンストラクタです。

### XmpValue {#XmpValue-java.lang.String-boolean-}
新しい文字列 XMP 値を初期化します。

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
配列値のコンストラクタです。

### isArray {#isArray--}
```
public boolean isArray()
```

XmpValue が配列の場合は true を返します。

**Returns:**
ブール値

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

値が DateTime の場合は true を返します。

**Returns:**
ブール値

### isDouble {#isDouble--}
```
public boolean isDouble()
```

値が浮動小数点値の場合は true を返します。

**Returns:**
ブール値

### isField {#isField--}
```
public boolean isField()
```

XmpValue がフィールドの場合は true を返します。

**Returns:**
ブール値

### isInteger {#isInteger--}
```
public boolean isInteger()
```

値が整数の場合は true を返します。

**Returns:**
ブール値

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

XmpValue が名前付き値の場合は true を返します。

**Returns:**
ブール値

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

XmpValue が名前付き値を表す場合は true を返します。

**Returns:**
ブール値

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

値はサポートされていない/不明で、未加工の XML コードが提供されます。

**Returns:**
値が生データとして返された場合は true です。

### isString {#isString--}
```
public boolean isString()
```

値が文字列の場合は true を返します。

**Returns:**
ブール値

### isStructure {#isStructure--}
```
public boolean isStructure()
```

XmpValue が構造体を表す場合は true を返します。

**Returns:**
ブール値

### to_ {#to_-com.aspose.pdf.XmpValue-}
XmpValue を配列に変換します。

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
XmpValue を配列に変換します。

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
KeyValuePair 配列を取得します

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
XmpValue を名前付き値に変換します。

### to_String {#to_String-com.aspose.pdf.XmpValue-}
XmpValue を文字列に変換します。

### to_XmpValue {#to_XmpValue-java.util.Date-}
DateTime を XmpValue に変換します。

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

double を XmpValue に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値（変換する値） |

**Returns:**
XmpValue インスタンス

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

integer を XmpValue に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値（変換する値） |

**Returns:**
XmpValue インスタンス

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
配列を XmpValue に変換します。

### to_XmpValue {#to_XmpValue-java.lang.String-}
文字列を XmpValue に変換します。

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

配列を返します。

**Returns:**
XmpValue 配列

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

日付時刻に変換します。

**Returns:**
Date インスタンス

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

現在の XMP 値を {@link DateTimeOffset} 表現に変換します。

**Returns:**
現在の XMP 値を表す {@link DateTimeOffset}。

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

名前付き値を含む辞書を返します。

**Returns:**
辞書

### toDouble {#toDouble--}
```
public double toDouble()
```

double に変換します。

**Returns:**
double 値

### toField {#toField--}
```
public XmpField toField()
```

XMP フィールドとして XMP 値を返します。

**Returns:**
XmpField インスタンス

### toInteger {#toInteger--}
```
public int toInteger()
```

整数に変換します。

**Returns:**
int 値です。

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

名前付き値として XMP 値を返します。

**Returns:**
(名前付き値) String キーと XmpValue 値を持つ HashMap インスタンス

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

内部使用のみ

**Returns:**
内部使用のみ

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

名前付き値コレクションとして XMP 値を返します。

**Returns:**
(名前付きコレクション値) String キーと XmpValue 値を持つ HashMap インスタンス

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

不明またはサポートされていない値の生 XML コードです。

**Returns:**
この値の XML ノードです。

### toString {#toString--}
```
public String toString()
```

XmpValue の文字列表現を返します。

**Returns:**
文字列表現

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
XmpValue の文字列表現を返します。

**Returns:**
文字列表現

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

文字列に変換します。

**Returns:**
文字列値

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

構造体（フィールドの集合）として XMP 値を返します。

**Returns:**
XmpField 配列
