---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントから未署名コンテンツを抽出しようとする操作の結果をカプセル化します。このクラスは、操作の成功に関する情報や詳細を提供します。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

PDF ドキュメントから未署名コンテンツを抽出しようとする操作の結果をカプセル化します。このクラスは、操作の成功状態、未署名コンテンツの詳細、結果を説明するメッセージ、およびドキュメントの署名のカバレッジ状態に関する情報を提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCoverage](#getCoverage--) | ドキュメントが有効なデジタル署名でカバーされている程度を示す値を取得します。 |
| [getMessage](#getMessage--) | 操作の結果を説明するメッセージを取得します。 |
| [getSuccess](#getSuccess--) | ドキュメントから未署名コンテンツを取得する操作が成功したかどうかを示す値を取得します。 |
| [getUnsignedContent](#getUnsignedContent--) | 未署名コンテンツを取得します。 |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

ドキュメントが有効なデジタル署名でカバーされている程度を示す値を取得します。

**Returns:**
ドキュメントが有効なデジタル署名でカバーされている程度を示す値。

### getMessage {#getMessage--}
```
public final String getMessage()
```

操作の結果を説明するメッセージを取得します。

**Returns:**
操作の結果を説明するメッセージ。

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

ドキュメントから未署名コンテンツを取得する操作が成功したかどうかを示す値を取得します。

**Returns:**
ドキュメントから未署名コンテンツを取得する操作が成功したかどうかを示す値。

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

未署名コンテンツを取得します。

**Returns:**
未署名コンテンツ。
