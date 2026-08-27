---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "文書を並列出力で比較するためのオプションクラスを表します。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

文書を並列出力で比較するためのオプションクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) |  {@link SideBySideComparisonOptions} クラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | 追加の変更マーカーを表示するかどうかを決定するプロパティを取得および設定します。設定すると、現在のページにはないが別のページに存在する変更マークが表示されます。変更が単語間にある場合、マークは空白文字に対して正確に位置付けられないことがあります。デフォルト値は {@code false} です。 |
| [getComparisonArea1](#getComparisonArea1--) | 比較領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)})、{@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])})、および {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。 |
| [getComparisonArea2](#getComparisonArea2--) | 比較領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)})、{@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])})、および {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。 |
| [getComparisonMode](#getComparisonMode--) | 比較モードを取得および設定します。デフォルト値は {@link ComparisonMode#IgnoreSpaces} です。 |
| [getDeleteColor](#getDeleteColor--) | サイドバイサイド比較中に削除されたコンテンツをマークするために使用される色を取得します。このプロパティは比較結果における削除の視覚的表現を定義します。 |
| [getExcludeAreas1](#getExcludeAreas1--) | 除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できますが、 {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) オプションと同時には設定できません。 |
| [getExcludeAreas2](#getExcludeAreas2--) | 除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できますが、 {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) オプションと同時には設定できません。 |
| [getExcludeTables](#getExcludeTables--) | 比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) および {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) と同時に設定できません。デフォルト値は {@code false} です。 |
| [getInsertColor](#getInsertColor--) | サイドバイサイド比較中に挿入されたコンテンツをマークするために使用される色を取得します。このプロパティは比較結果における挿入の視覚的表現を定義します。 |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | 追加の変更マーカーを表示するかどうかを決定するプロパティを取得および設定します。設定すると、現在のページにはないが別のページに存在する変更マークが表示されます。変更が単語間にある場合、マークは空白文字に対して正確に位置付けられないことがあります。デフォルト値は {@code false} です。 |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | 比較領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)})、{@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])})、および {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。 |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | 比較領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)})、{@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])})、および {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。 |
| [setComparisonMode](#setComparisonMode-int-) | 比較モードを取得および設定します。デフォルト値は {@link ComparisonMode#IgnoreSpaces} です。 |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | サイドバイサイド比較中に削除されたコンテンツをマークするために使用される色を設定します。このプロパティは比較結果における削除の視覚的表現を定義します。 |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | 除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できますが、 {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) オプションと同時には設定できません。 |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | 除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できますが、 {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) オプションと同時には設定できません。 |
| [setExcludeTables](#setExcludeTables-boolean-) | 比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) および {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) と同時に設定できません。デフォルト値は {@code false} です。 |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | サイドバイサイド比較中に挿入されたコンテンツをマークするために使用される色を設定します。このプロパティは比較結果における挿入の視覚的表現を定義します。 |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

 {@link SideBySideComparisonOptions} クラスのインスタンスを作成します。

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

追加の変更マーカーを表示するかどうかを決定するプロパティを取得および設定します。設定すると、現在のページにはないが別のページに存在する変更マークが表示されます。変更が単語間にある場合、マークは空白文字に対して正確に位置付けられないことがあります。デフォルト値は {@code false} です。

**Returns:**
ブール値

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

比較領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)})、{@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])})、および {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。

**Returns:**
矩形インスタンス

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

比較領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)})、{@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])})、および {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。

**Returns:**
矩形インスタンス

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

比較モードを取得および設定します。デフォルト値は {@link ComparisonMode#IgnoreSpaces} です。

**Returns:**
ComparisonMode 要素

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

サイドバイサイド比較中に削除されたコンテンツをマークするために使用される色を取得します。このプロパティは比較結果における削除の視覚的表現を定義します。

**Returns:**
サイドバイサイド比較中に削除されたコンテンツをマークするために使用される色。

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できますが、 {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) オプションと同時には設定できません。

**Returns:**
Rectangle インスタンスの配列

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できますが、 {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) オプションと同時には設定できません。

**Returns:**
Rectangle インスタンスの配列

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) および {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) と同時に設定できません。デフォルト値は {@code false} です。

**Returns:**
ブール値

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

サイドバイサイド比較中に挿入されたコンテンツをマークするために使用される色を取得します。このプロパティは比較結果における挿入の視覚的表現を定義します。

**Returns:**
サイドバイサイド比較中に挿入されたコンテンツをマークするために使用される色。

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

追加の変更マーカーを表示するかどうかを決定するプロパティを取得および設定します。設定すると、現在のページにはないが別のページに存在する変更マークが表示されます。変更が単語間にある場合、マークは空白文字に対して正確に位置付けられないことがあります。デフォルト値は {@code false} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
比較領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)})、{@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])})、および {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
比較領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)})、{@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])})、および {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

比較モードを取得および設定します。デフォルト値は {@link ComparisonMode#IgnoreSpaces} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ComparisonMode 要素 |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
サイドバイサイド比較中に削除されたコンテンツをマークするために使用される色を設定します。このプロパティは比較結果における削除の視覚的表現を定義します。

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できますが、 {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) オプションと同時には設定できません。

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できますが、 {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) オプションと同時には設定できません。

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) および {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) と同時に設定できません。デフォルト値は {@code false} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
サイドバイサイド比較中に挿入されたコンテンツをマークするために使用される色を設定します。このプロパティは比較結果における挿入の視覚的表現を定義します。

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
