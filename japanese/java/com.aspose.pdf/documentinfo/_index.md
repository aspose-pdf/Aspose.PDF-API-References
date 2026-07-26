---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF 文書のメタ情報を表します。"
type: docs
weight: 1160
url: /ja/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

PDF 文書のメタ情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | DocumentInfo インスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | 指定されたキーと値を持つ要素をコレクションに追加します。 |
| [clear](#clear--) | ドキュメント情報をクリアします。 |
| [clearCustomData](#clearCustomData--) | カスタムデータのみをクリアし、他のすべての事前定義された値（Title、Author など）は残します。 |
| [get_Item](#get_Item-java.lang.String-) | 指定されたキーに関連付けられた値を取得します。 |
| [getAuthor](#getAuthor--) | ドキュメントの作者を取得します。 |
| [getCreationDate](#getCreationDate--) | ドキュメントの作成日を取得します。 |
| [getCreationTimeZone](#getCreationTimeZone--) | 作成日のタイムゾーン（ミリ秒単位）。 |
| [getCreator](#getCreator--) | ドキュメントの作成者を取得します。 |
| [getKeywords](#getKeywords--) | ドキュメントのキーワードを取得します。 |
| [getModDate](#getModDate--) | ドキュメントの更新日を取得します。 |
| [getModTimeZone](#getModTimeZone--) | 更新日のタイムゾーン。 |
| [getProducer](#getProducer--) | ドキュメントのプロデューサーを取得します。 |
| [getSubject](#getSubject--) | ドキュメントの件名を取得します。 |
| [getTitle](#getTitle--) | ドキュメントのタイトルを取得します。 |
| [getTrapped](#getTrapped--) | トラップフラグを取得します。 |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | キーがカスタムではなく、事前定義されたもの（Title、Author など）かどうかを判定します。 |
| [remove](#remove-java.lang.String-) | コレクションから指定されたキーを持つ要素を削除します。 |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | 指定されたキーに関連付けられた値を設定します。 |
| [setAuthor](#setAuthor-java.lang.String-) | ドキュメントの作者を設定します。 |
| [setCreationDate](#setCreationDate-java.util.Date-) | ドキュメントの作成日を設定します。 |
| [setCreationTimeZone](#setCreationTimeZone-double-) | 作成日のタイムゾーン（ミリ秒単位）。 |
| [setCreator](#setCreator-java.lang.String-) | ドキュメントの作成者を設定します。 |
| [setKeywords](#setKeywords-java.lang.String-) | ドキュメントのキーワードを設定します。 |
| [setModDate](#setModDate-java.util.Date-) | ドキュメントの更新日を設定します。 |
| [setModTimeZone](#setModTimeZone-double-) | 更新日のタイムゾーン。 |
| [setProducer](#setProducer-java.lang.String-) | ドキュメントのプロデューサーを設定します。 |
| [setSubject](#setSubject-java.lang.String-) | ドキュメントの件名を設定します。 |
| [setTitle](#setTitle-java.lang.String-) | ドキュメントのタイトルを設定します。 |
| [setTrapped](#setTrapped-java.lang.String-) | トラップフラグを設定します。 |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
DocumentInfo インスタンスを初期化します。

### addItem {#addItem-java.lang.String-java.lang.String-}
指定されたキーと値を持つ要素をコレクションに追加します。

### clear {#clear--}
```
public void clear()
```

ドキュメント情報をクリアします。

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

カスタムデータのみをクリアし、他のすべての事前定義された値（Title、Author など）は残します。

### get_Item {#get_Item-java.lang.String-}
指定されたキーに関連付けられた値を取得します。

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

ドキュメントの作者を取得します。

**Returns:**
文字列値

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

ドキュメントの作成日を取得します。

**Returns:**
Date オブジェクト

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

作成日のタイムゾーン（ミリ秒単位）。

**Returns:**
double 値

### getCreator {#getCreator--}
```
public String getCreator()
```

ドキュメントの作成者を取得します。

**Returns:**
文字列値

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

ドキュメントのキーワードを取得します。

**Returns:**
文字列値

### getModDate {#getModDate--}
```
public Date getModDate()
```

ドキュメントの更新日を取得します。

**Returns:**
Date オブジェクト

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

更新日のタイムゾーン。

**Returns:**
double 値

### getProducer {#getProducer--}
```
public String getProducer()
```

ドキュメントのプロデューサーを取得します。

**Returns:**
文字列値

### getSubject {#getSubject--}
```
public String getSubject()
```

ドキュメントの件名を取得します。

**Returns:**
文字列値

### getTitle {#getTitle--}
```
public String getTitle()
```

ドキュメントのタイトルを取得します。

**Returns:**
文字列値

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

トラップフラグを取得します。

**Returns:**
文字列値

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
キーがカスタムではなく、事前定義されたもの（Title、Author など）かどうかを判定します。

### remove {#remove-java.lang.String-}
コレクションから指定されたキーを持つ要素を削除します。

### set_Item {#set_Item-java.lang.String-java.lang.String-}
指定されたキーに関連付けられた値を設定します。

### setAuthor {#setAuthor-java.lang.String-}
ドキュメントの作者を設定します。

### setCreationDate {#setCreationDate-java.util.Date-}
ドキュメントの作成日を設定します。

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

作成日のタイムゾーン（ミリ秒単位）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ミリ秒で |

### setCreator {#setCreator-java.lang.String-}
ドキュメントの作成者を設定します。

### setKeywords {#setKeywords-java.lang.String-}
ドキュメントのキーワードを設定します。

### setModDate {#setModDate-java.util.Date-}
ドキュメントの更新日を設定します。

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

更新日のタイムゾーン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setProducer {#setProducer-java.lang.String-}
ドキュメントのプロデューサーを設定します。

### setSubject {#setSubject-java.lang.String-}
ドキュメントの件名を設定します。

### setTitle {#setTitle-java.lang.String-}
ドキュメントのタイトルを設定します。

### setTrapped {#setTrapped-java.lang.String-}
トラップフラグを設定します。
