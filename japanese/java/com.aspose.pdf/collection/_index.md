---
title: "コレクション"
linktitle: "コレクション"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Collection（12.3.5 Collections）用のクラスを表します。"
type: docs
weight: 610
url: /ja/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Collection（12.3.5 Collections）用のクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Collection](#Collection--) | 新しい Collection オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | デフォルトの埋め込みファイル名です。 |
| [getSchema](#getSchema--) | ドキュメントコレクションの\"Schema\"を取得します。 |
| [getSortedCollection](#getSortedCollection--) | 仕様に従ってソートされたファイルのコレクションを取得します。 |

### Collection {#Collection--}
```
public Collection()
```

新しい Collection オブジェクトを初期化します。

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

デフォルトの埋め込みファイル名です。

**Returns:**
String オブジェクト

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

ドキュメントコレクションの\"Schema\"を取得します。

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

仕様に従ってソートされたファイルのコレクションを取得します。

**Returns:**
ソートされたファイルの一覧です。
