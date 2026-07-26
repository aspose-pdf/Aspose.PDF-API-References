---
title: "HtmlSaveOptions.HtmlMarkupGenerationModes"
linktitle: "HtmlSaveOptions.HtmlMarkupGenerationModes"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "HTML 作成時に特定の要件が存在することがあります。この列挙体は、PDF から HTML への変換時にそのような特定の要件に合わせて使用できる HTML 準備モードを定義します。"
type: docs
weight: 2090
url: /ja/java/com.aspose.pdf/htmlsaveoptions.htmlmarkupgenerationmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes

```
public static final class HtmlSaveOptions.HtmlMarkupGenerationModes extends com.aspose.ms.System.Enum
```

作成されたHTMLに特定の要件がある場合があります。この列挙体は、PDFからHTMLへの変換中にそのような特定の要件に合わせるために使用できるHTML準備モードを定義します

## フィールド

| フィールド | 説明 |
| --- | --- |
| [WriteAllHtml](#WriteAllHtml) | デフォルトモードは、特定の要件が存在しない場合です。特別な追加処理を行わず、HTML のすべての部分を含む出力が生成されます。 |
| [WriteOnlyBodyContent](#WriteOnlyBodyContent) | HTML の body 外部にあるすべての HTML コンテンツは除去され、{@code } タグ内のコンテンツのみが残ります。 |

### WriteAllHtml {#WriteAllHtml}
```
public static final int WriteAllHtml
```

デフォルトモードは、特定の要件が存在しない場合です。特別な追加処理を行わず、HTML のすべての部分を含む出力が生成されます。

### WriteOnlyBodyContent {#WriteOnlyBodyContent}
```
public static final int WriteOnlyBodyContent
```

HTML の body 外部にあるすべての HTML コンテンツは除去され、{@code } タグ内のコンテンツのみが残ります。
