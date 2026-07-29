---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストサブシステムのデフォルトのタイプを指定します"
type: docs
weight: 4960
url: /ja/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

テキストサブシステムのデフォルトのタイプを指定します

## フィールド

| フィールド | 説明 |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | 事前定義された Font インスタンスのリストからデフォルトフォントを使用します。setDefaultFonts(List of Font instances) を使用して設定できます。テキストに必要なすべての文字を含む最初に見つかったフォントが使用されます。該当するフォントが見つからない場合は、システムフォントが使用されます。 |
| [PredefinedFont](#PredefinedFont) | デフォルトフォントを使用します。set/get PredefinedFont(Font) を使用して設定できます。PredefinedFont が null の場合は、SystemFont が使用されます。 |
| [SystemFont](#SystemFont) | デフォルトのシステムフォント Helvetica を使用するか、置き換えられた類似フォントが使用されます。 |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | テキストに必要なすべての文字を含む最初に見つかったフォントが使用されます。見つかったすべてのフォントが対象となります。該当するフォントが見つからない場合は、システムフォントが使用されます。 |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

事前定義された Font インスタンスのリストからデフォルトフォントを使用します。setDefaultFonts(List of Font instances) を使用して設定できます。テキストに必要なすべての文字を含む最初に見つかったフォントが使用されます。該当するフォントが見つからない場合は、システムフォントが使用されます。

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

デフォルトフォントを使用します。set/get PredefinedFont(Font) を使用して設定できます。PredefinedFont が null の場合は、SystemFont が使用されます。

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

デフォルトのシステムフォント Helvetica を使用するか、置き換えられた類似フォントが使用されます。

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

テキストに必要なすべての文字を含む最初に見つかったフォントが使用されます。見つかったすべてのフォントが対象となります。該当するフォントが見つからない場合は、システムフォントが使用されます。
