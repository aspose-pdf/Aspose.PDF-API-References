---
title: "NamedDestinationCollection"
linktitle: "NamedDestinationCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスはすべてのデスティネーションのコレクションを表します（名前文字列をデスティネーションにマッピングする名前ツリー（12.3.2.3、\"Named Destinations\" を参照）および（7.7.4、\"Name Dictionary\" を参照））です。"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.nameddestinations/nameddestinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.nameddestinations.NamedDestinationCollection

**All Implemented Interfaces:**
INamedDestinationCollection

```
public class NamedDestinationCollection extends Object implements INamedDestinationCollection
```

PDF ドキュメント内のすべてのデスティネーション（名前文字列をデスティネーションにマッピングする名前ツリー（12.3.2.3「Named Destinations」参照）および（7.7.4「Name Dictionary」参照））のコレクションを表すクラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-java.lang.String-com.aspose.pdf.IAppointment-) | 新しい名前付き宛先を追加します。 |
| [get_Item](#get_Item-java.lang.String-) | 名前で予約を取得または設定します。 |
| [getNames](#getNames--) | 宛先の名前の一覧。 |
| [isEmpty](#isEmpty--) |  |
| [remove](#remove-java.lang.String-) | 名前付き宛先を削除します。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.IAppointment-) | 名前で予約を取得または設定します。 |
| [size](#size--) | 名前付き宛先の数。 |

### add {#add-java.lang.String-com.aspose.pdf.IAppointment-}
新しい名前付き宛先を追加します。

### get_Item {#get_Item-java.lang.String-}
名前で予約を取得または設定します。

### getNames {#getNames--}
```
public String [] getNames()
```

宛先の名前の一覧。

**Returns:**
文字列値の配列

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```



**Returns:**
ブール値

### remove {#remove-java.lang.String-}
名前付き宛先を削除します。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.IAppointment-}
名前で予約を取得または設定します。

### size {#size--}
```
public int size()
```

名前付き宛先の数。

**Returns:**
int 値です。
