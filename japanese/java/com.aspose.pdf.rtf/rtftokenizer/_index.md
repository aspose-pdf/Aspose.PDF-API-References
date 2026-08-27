---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ストリーミングされた RTF コンテンツをトークンのセットとして抽出するよう設計されたクラスです。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

ストリーミングされた RTF コンテンツをトークンのセットとして抽出するよう設計されたクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [readNextToken](#readNextToken--) | 入力ストリームを読み取り、次のトークンを返します。 |
| [skip](#skip-int-) | 入力ストリームから指定された文字数を消費し、破棄します。 |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

入力ストリームを読み取り、次のトークンを返します。

### skip {#skip-int-}
```
public final void skip(int count)
```

入力ストリームから指定された文字数を消費し、破棄します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| カウント |  | スキップする文字数。 |
