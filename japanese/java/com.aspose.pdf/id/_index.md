---
title: "Id"
linktitle: "Id"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> ファイル識別子構造体を表します。 </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /ja/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> ファイル識別子構造を表します。 </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getModified](#getModified--) | 最後に更新された時点でのドキュメントの内容に基づいて識別子を変更します。 |
| [getOriginal](#getOriginal--) | 元々作成された時点でのドキュメントの内容に基づく永続的な識別子です。 |

### getModified {#getModified--}
```
public String getModified()
```

最後に更新された時点でのドキュメントの内容に基づいて識別子を変更します。

**Returns:**
文字列値

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

元々作成された時点でのドキュメントの内容に基づく永続的な識別子です。

**Returns:**
文字列値
