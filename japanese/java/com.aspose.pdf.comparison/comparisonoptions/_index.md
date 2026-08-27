---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDFドキュメント比較オプションクラスを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

PDFドキュメント比較オプションクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | {@link ComparisonOptions} クラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | 編集操作の順序を取得および設定します。 |
| [getExcludeAreas1](#getExcludeAreas1--) | 除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できます。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。 |
| [getExcludeAreas2](#getExcludeAreas2--) | 除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できます。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。 |
| [getExtractionArea](#getExtractionArea--) | ページのテキストが比較される矩形領域を取得および設定します。このオプションは {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)})、{@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])})、および { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。 |
| [isExcludeTables](#isExcludeTables--) | 比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。デフォルト値は {@code false} です。 |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | 編集操作の順序を取得および設定します。 |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | 除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できます。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。 |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | 除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できます。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。 |
| [setExcludeTables](#setExcludeTables-boolean-) | 比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。デフォルト値は {@code false} です。 |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | ページのテキストが比較される矩形領域を取得および設定します。このオプションは {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)})、{@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])})、および { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。 |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

{@link ComparisonOptions} クラスのインスタンスを作成します。

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

編集操作の順序を取得および設定します。

**Returns:**
EditOperationsOrder 要素

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できます。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。

**Returns:**
Rectangle インスタンスの配列

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できます。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。

**Returns:**
Rectangle インスタンスの配列

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

ページのテキストが比較される矩形領域を取得および設定します。このオプションは {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)})、{@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])})、および { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。

**Returns:**
矩形インスタンス

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。デフォルト値は {@code false} です。

**Returns:**
ブール値

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
編集操作の順序を取得および設定します。

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できます。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) と共に設定できます。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) オプションと同時に設定できません。デフォルト値は {@code false} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
ページのテキストが比較される矩形領域を取得および設定します。このオプションは {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)})、{@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])})、および { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) オプションと同時に設定できません。
