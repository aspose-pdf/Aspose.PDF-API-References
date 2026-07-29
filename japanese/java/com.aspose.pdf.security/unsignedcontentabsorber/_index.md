---
title: "UnsignedContentAbsorber"
linktitle: "UnsignedContentAbsorber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "デジタル署名で管理されている PDF ファイルから未署名コンテンツを抽出するクラスを表します。"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

デジタル署名で管理されている PDF ファイルから未署名コンテンツを抽出するクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | 未署名コンテンツを処理するために使用されるクラスを表します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [tryGetContent](#tryGetContent--) | 関連文書から未署名コンテンツを取得しようとします。 |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
未署名コンテンツを処理するために使用されるクラスを表します。

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

関連文書から未署名コンテンツを取得しようとします。

**Returns:**
未署名コンテンツ、デジタル署名のカバレッジ、操作の成功ステータス、および情報メッセージの詳細を含む {@link UnsignedContentAbsorber.Result} オブジェクトです。
