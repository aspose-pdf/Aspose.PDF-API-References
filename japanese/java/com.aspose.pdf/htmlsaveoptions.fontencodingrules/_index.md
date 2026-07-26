---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "この列挙体はエンコーディングロジックを調整する規則を定義します"
type: docs
weight: 2050
url: /ja/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

この列挙体はエンコーディングロジックを調整する規則を定義します

## フィールド

| フィールド | 説明 |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode は、入力コードを Unicode 記号にデコードするのに役立つ特別なメカニズムです。仕様によれば、特定の入力コードに対して Unicode 記号を取得するために、すべてのメカニズムの中で最初に使用しなければなりません。しかし、一部の文書は非標準フォントを使用しており、これらの文書を正しく変換するには ToUnicode の優先度を下げ、別のメカニズムで入力コードをデコードする必要がある場合があります。 |
| [Default](#Default) | エンコーディングロジックは "そのまま" にしておく - PDF 仕様に従って |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode は、入力コードを Unicode 記号にデコードするのに役立つ特別なメカニズムです。仕様によれば、特定の入力コードに対して Unicode 記号を取得するために、すべてのメカニズムの中で最初に使用しなければなりません。しかし、一部の文書は非標準フォントを使用しており、これらの文書を正しく変換するには ToUnicode の優先度を下げ、別のメカニズムで入力コードをデコードする必要がある場合があります。

### Default {#Default}
```
public static final byte Default
```

エンコーディングロジックは "そのまま" にしておく - PDF 仕様に従って
