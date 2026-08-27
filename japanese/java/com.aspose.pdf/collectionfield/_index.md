---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ドキュメントコレクションスキーマフィールドクラスを表します。"
type: docs
weight: 620
url: /ja/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

ドキュメントコレクションスキーマフィールドクラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getE](#getE--) | インタラクティブ PDF プロセッサがフィールド値の編集をサポートすべきかを示すフラグを取得します。デフォルト値: false |
| [getFiledType](#getFiledType--) | スキーマコレクション内のフィールド値の型を取得します。このフィールドは {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}) に対応する値の型を記述します。 |
| [getN](#getN--) | インタラクティブ PDF プロセッサがユーザーに提示すべきテキストフィールド名を取得します |
| [getO](#getO--) | ユーザーインターフェイスでのフィールド名の相対順序を取得します。フィールドはインタラクティブ PDF プロセッサによって昇順にソートされます。 |
| [getSubtype](#getSubtype--) | スキーマコレクション内のフィールド値のサブタイプを取得します。この辞書が記述するコレクションフィールドまたはファイル関連フィールドのサブタイプです。このエントリはフィールドに格納されるデータのタイプを識別します。 |
| [getV](#getV--) | ユーザーインターフェイスでのフィールドの初期表示状態を取得します。デフォルト値: true。 |

### getE {#getE--}
```
public final boolean getE()
```

インタラクティブ PDF プロセッサがフィールド値の編集をサポートすべきかを示すフラグを取得します。デフォルト値: false

**Returns:**
ブール値

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

スキーマコレクション内のフィールド値の型を取得します。このフィールドは {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}) に対応する値の型を記述します。

**Returns:**
FieldValueType 要素

### getN {#getN--}
```
public final String getN()
```

インタラクティブ PDF プロセッサがユーザーに提示すべきテキストフィールド名を取得します

**Returns:**
文字列値

### getO {#getO--}
```
public final Integer [] getO()
```

ユーザーインターフェイスでのフィールド名の相対順序を取得します。フィールドはインタラクティブ PDF プロセッサによって昇順にソートされます。

**Returns:**
Integer の配列

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

スキーマコレクション内のフィールド値のサブタイプを取得します。この辞書が記述するコレクションフィールドまたはファイル関連フィールドのサブタイプです。このエントリはフィールドに格納されるデータのタイプを識別します。

**Returns:**
CollectionFieldSubtype 要素

### getV {#getV--}
```
public final boolean getV()
```

ユーザーインターフェイスでのフィールドの初期表示状態を取得します。デフォルト値: true。

**Returns:**
ブール値
