---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "コレクションアイテムクラスを表します。コレクションアイテムはコレクションスキーマで記述されたデータを含みます。"
type: docs
weight: 640
url: /ja/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

コレクションアイテムクラスを表します。コレクションアイテムはコレクションスキーマで記述されたデータを含みます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAllNames](#getAllNames--) | コレクション項目のすべての値の名前のコレクションを取得します。 |
| [hasName](#hasName-java.lang.String-) | 指定された名前がコレクション項目に存在するかどうかをチェックします。 |
| [isEmpty](#isEmpty--) | コレクション項目が空かどうかを示す値を取得します。 |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | 指定された名前でコレクション項目から DateTime 型の値を取得しようとします。 |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | 指定された名前でコレクション項目から double 値を取得しようとします。 |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | 指定された名前でコレクション項目から整数値を取得しようとします。 |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | コレクション項目から指定された名前のテキスト値を取得しようとします。 |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

コレクション項目のすべての値の名前のコレクションを取得します。

**Returns:**
String のリスト

### hasName {#hasName-java.lang.String-}
指定された名前がコレクション項目に存在するかどうかをチェックします。

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

コレクション項目が空かどうかを示す値を取得します。

**Returns:**
コレクション項目が空の場合は true、そうでない場合は false です。このプロパティは、文字列値、倍精度数値、整数値、日付値を含むいかなる値もコレクション項目に含まれていない場合に true を返します。これらの値タイプのいずれかがコレクション項目に存在する場合、このプロパティは false を返します。

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
指定された名前でコレクション項目から DateTime 型の値を取得しようとします。

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
指定された名前でコレクション項目から double 値を取得しようとします。

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
指定された名前でコレクション項目から整数値を取得しようとします。

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
コレクション項目から指定された名前のテキスト値を取得しようとします。
