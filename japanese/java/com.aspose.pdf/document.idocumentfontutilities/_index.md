---
title: "Document.IDocumentFontUtilities"
linktitle: "Document.IDocumentFontUtilities"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォントを調整する機能を保持します"
type: docs
weight: 1100
url: /ja/java/com.aspose.pdf/document.idocumentfontutilities/
---
```
public static interface Document.IDocumentFontUtilities
```

フォントを調整する機能を保持します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAllFonts](#getAllFonts--) | ドキュメントからすべてのフォントを返します。 |
| [subsetFonts](#subsetFonts-byte-) | ドキュメント内のすべてのフォントをサブセット化します。 |

### getAllFonts {#getAllFonts--}
```
Font [] getAllFonts()
```

ドキュメントからすべてのフォントを返します。

**Returns:**
フォント

### subsetFonts {#subsetFonts-byte-}
```
void subsetFonts(byte subsetStrategy)
```

ドキュメント内のすべてのフォントをサブセット化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subsetStrategy |  | FontSubsetStrategy 要素 |
