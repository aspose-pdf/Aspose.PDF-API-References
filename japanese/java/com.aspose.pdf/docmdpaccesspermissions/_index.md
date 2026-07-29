---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このドキュメントに付与されたアクセス権限を取得します。有効な値は次のとおりです: 1 - ドキュメントへの変更は許可されません。変更があると署名が無効になります。 2 -."
type: docs
weight: 1010
url: /ja/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

この文書に付与されたアクセス許可です。有効な値は次のとおりです: 1 - 文書への変更は一切許可されず、変更があると署名が無効になります。 2 - 許可される変更はフォームへの入力、ページテンプレートのインスタンス化、署名であり、その他の変更は署名を無効にします。 3 - 許可される変更は 2 と同じに加えて、注釈の作成、削除、修正が可能で、その他の変更は署名を無効にします。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - 変更が許可されるのは 2 と同様に、アノテーションの作成、削除、変更も含まれます。その他の変更は署名を無効にします。 |
| [FillingInForms](#FillingInForms) | 2 - 変更が許可されるのは、フォームへの入力、ページテンプレートのインスタンス化、署名です。その他の変更は署名を無効にします。 |
| [NoChanges](#NoChanges) | 1 - ドキュメントへの変更は許可されません。変更があると署名が無効になります。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - 変更が許可されるのは 2 と同様に、アノテーションの作成、削除、変更も含まれます。その他の変更は署名を無効にします。

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - 変更が許可されるのは、フォームへの入力、ページテンプレートのインスタンス化、署名です。その他の変更は署名を無効にします。

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - ドキュメントへの変更は許可されません。変更があると署名が無効になります。

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列
