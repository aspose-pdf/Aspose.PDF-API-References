---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "署名名のクラスを表します。より正確な署名名を表します。文字列名の代わりに使用されます。同じ文字列名で署名を提示することができます。"
type: docs
weight: 690
url: /ja/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

署名名のクラスを表します。より正確な署名名を表します。文字列名の代わりに使用されます。同じ文字列名で署名を提示することができます。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [FullName](#FullName) | 署名のフルネームを取得し、署名フィールドに対して一意で正確な識別子を提供します。 |
| [Name](#Name) | 署名の名前を取得します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | このインスタンスと指定されたオブジェクトが等しいかどうかを判断します。 |
| [getSignatureDictionary](#getSignatureDictionary--) | 署名辞書を取得します。 |
| [hashCode](#hashCode--) | FullName プロパティに基づいてこのインスタンスのハッシュコードを返します。 |
| [hasSignature](#hasSignature--) | 署名が存在するかどうかを示します。 |
| [toString](#toString--) | {@link SignatureName} インスタンスの文字列表現を返します。主にその名前を使用します。 |

### FullName {#FullName}
```
public final String FullName
```

署名のフルネームを取得し、署名フィールドに対して一意で正確な識別子を提供します。

### Name {#Name}
```
public final String Name
```

署名の名前を取得します。

### equals {#equals-java.lang.Object-}
このインスタンスと指定されたオブジェクトが等しいかどうかを判断します。

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

署名辞書を取得します。

**Returns:**
署名辞書、見つからない場合は null。

### hashCode {#hashCode--}
```
public int hashCode()
```

FullName プロパティに基づいてこのインスタンスのハッシュコードを返します。

**Returns:**
FullName プロパティのハッシュコードを表す整数。

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

署名が存在するかどうかを示します。

**Returns:**
ブール値

### toString {#toString--}
```
public String toString()
```

{@link SignatureName} インスタンスの文字列表現を返します。主にその名前を使用します。

**Returns:**
署名の名前を表す文字列です。
