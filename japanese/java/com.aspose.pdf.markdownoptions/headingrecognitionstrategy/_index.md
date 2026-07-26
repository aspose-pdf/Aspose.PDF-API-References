---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ヘッダー認識戦略のタイプを表します。"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

ヘッダー認識戦略のタイプを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Auto](#Auto) | 自動ヘッダー認識戦略の選択を提供します。これはデフォルトのオプションです。ドキュメントにブックマークが含まれている場合、{@link HeadingRecognitionStrategy#Outlines} 戦略が選択され、そうでない場合は {@link HeadingRecognitionStrategy#Heuristic} が選択されます。 |
| [Heuristic](#Heuristic) | ヒューリスティックルールとフォントサイズ統計に基づくヘッダー認識戦略を表します。 |
| [None](#None) | ヘッダーを認識しません。このオプションは、複雑にフォーマットされたドキュメントで役立つことがあります。 |
| [Outlines](#Outlines) | アウトラインに基づくヘッダー認識戦略を表します。 |

### Auto {#Auto}
```
public static final int Auto
```

自動ヘッダー認識戦略の選択を提供します。これはデフォルトのオプションです。ドキュメントにブックマークが含まれている場合、{@link HeadingRecognitionStrategy#Outlines} 戦略が選択され、そうでない場合は {@link HeadingRecognitionStrategy#Heuristic} が選択されます。

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

ヒューリスティックルールとフォントサイズ統計に基づくヘッダー認識戦略を表します。

### None {#None}
```
public static final int None
```

ヘッダーを認識しません。このオプションは、複雑にフォーマットされたドキュメントで役立つことがあります。

### Outlines {#Outlines}
```
public static final int Outlines
```

アウトラインに基づくヘッダー認識戦略を表します。
