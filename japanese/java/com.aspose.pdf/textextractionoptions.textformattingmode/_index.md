---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントをテキストに変換する際に使用できるさまざまなモードを定義します。 {@code TextDevice} クラスを参照してください。"
type: docs
weight: 5070
url: /ja/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

PDF ドキュメントをテキストに変換する際に使用できるさまざまなモードを定義します。 {@code TextDevice} クラスを参照してください。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Flatten](#Flatten) | 座標によって位置付けられたテキストフラグメントで PDF コンテンツを表現します。基本的に "Raw" モードと似ています。ただし "Raw" モードが文書内のテキストフラグメント（演算子）の構造を保持することに重点を置くのに対し、 "Flatten" モードはテキストを読み取られる順序で保持することに重点を置きます。 |
| [MemorySaving](#MemorySaving) | メモリ節約を伴う抽出です。'Raw' モードとほぼ同じですが、若干高速でメモリ使用量が少なくなります。 |
| [Pure](#Pure) | 少しの書式設定ルーチンで PDF コンテンツを表現します。 |
| [Raw](#Raw) | PDF コンテンツをそのまま表現します。つまり、書式設定なしです。 |

### Flatten {#Flatten}
```
public static final int Flatten
```

座標によって位置付けられたテキストフラグメントで PDF コンテンツを表現します。基本的に "Raw" モードと似ています。ただし "Raw" モードが文書内のテキストフラグメント（演算子）の構造を保持することに重点を置くのに対し、 "Flatten" モードはテキストを読み取られる順序で保持することに重点を置きます。

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

メモリ節約を伴う抽出です。'Raw' モードとほぼ同じですが、若干高速でメモリ使用量が少なくなります。

### Pure {#Pure}
```
public static final int Pure
```

少しの書式設定ルーチンで PDF コンテンツを表現します。

### Raw {#Raw}
```
public static final int Raw
```

PDF コンテンツをそのまま表現します。つまり、書式設定なしです。
