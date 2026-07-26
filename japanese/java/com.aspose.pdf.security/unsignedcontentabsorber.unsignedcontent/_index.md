---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF 文書から抽出された未署名コンテンツ要素をカプセル化します。このクラスは、未署名のページ、フォームフィールド、XForms、注釈へのアクセスを提供します。"
type: docs
weight: 50
url: /ja/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

PDF ドキュメントから抽出された未署名コンテンツ要素をカプセル化します。このクラスは、ドキュメント内の未署名コンテンツの一部であるページ、フォームフィールド、XForm、注釈へのアクセスを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAnnotations](#getAnnotations--) | 変更または追加された可能性のある修正済み注釈の辞書を取得します。 |
| [getForms](#getForms--) | 増分で変更または追加されたフォームフィールドを取得します。 |
| [getPages](#getPages--) | コンテンツが未署名または増分で変更されたページのリストを取得します。ページは変更済みとみなされ、XForms はチェックされず XForms リストには表示されません。 |
| [getXForms](#getXForms--) | ページ自体は変更されていない（Pages リストに含まれない）ものの、変更された可能性のある修正済み XForm オブジェクトの辞書を取得します。 |
| [setXForms](#setXForms-java.util.HashMap-) | ページ自体は変更されていない（Pages リストに含まれない）ものの、変更された可能性のある修正済み XForm オブジェクトの辞書です。 |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

変更または追加された可能性のある修正済み注釈の辞書を取得します。

**Returns:**
変更または追加された可能性のある修正済み注釈の辞書です。

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

増分で変更または追加されたフォームフィールドを取得します。

**Returns:**
増分で変更または追加されたフォームフィールドです。

### getPages {#getPages--}
```
public final List < Page > getPages()
```

コンテンツが未署名または増分で変更されたページのリストを取得します。ページは変更済みとみなされ、XForms はチェックされず XForms リストには表示されません。

**Returns:**
コンテンツが未署名または増分で変更されたページのリストです。

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

ページ自体は変更されていない（Pages リストに含まれない）ものの、変更された可能性のある修正済み XForm オブジェクトの辞書を取得します。

**Returns:**
ページ自体は変更されていない（Pages リストに含まれません）が、変更された可能性のある修正済み XForm オブジェクトの辞書です。

### setXForms {#setXForms-java.util.HashMap-}
ページ自体は変更されていない（Pages リストに含まれない）ものの、変更された可能性のある修正済み XForm オブジェクトの辞書です。
