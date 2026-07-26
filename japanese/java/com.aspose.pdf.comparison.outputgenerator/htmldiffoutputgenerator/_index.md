---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト差分のHTML表現を生成するクラスを表します。削除された改行は - 段落記号で示されます。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

テキスト差分のHTML表現を生成するクラスを表します。削除された改行は - 段落記号で示されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | {@link HtmlDiffOutputGenerator} クラスのインスタンスを作成します。 |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | {@link HtmlDiffOutputGenerator} クラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | テキスト間の差分に基づいて出力を生成し、ファイルに保存します。 |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | テキスト間の差分に基づいて出力を生成し、ファイルに保存します。 |
| [generateOutput1](#generateOutput1-java.util.List-) | テキスト間の差分に基づいて出力を生成し、ファイルに保存します。 |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | テキスト間の差分に基づいて出力を生成し、ファイルに保存します。 |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | 内部メソッド |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Delete 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Equal 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Insert 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | 削除操作の text-decoration: line-through スタイルを取得または設定します。デフォルト値は {@code False} です。 |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Delete 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Equal 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Insert 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | 削除操作の text-decoration: line-through スタイルを取得または設定します。デフォルト値は {@code False} です。 |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

{@link HtmlDiffOutputGenerator} クラスのインスタンスを作成します。

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
{@link HtmlDiffOutputGenerator} クラスのインスタンスを作成します。

### generateOutput {#generateOutput-java.util.List-}
テキスト間の差分に基づいて出力を生成し、ファイルに保存します。

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
テキスト間の差分に基づいて出力を生成し、ファイルに保存します。

### generateOutput1 {#generateOutput1-java.util.List-}
テキスト間の差分に基づいて出力を生成し、ファイルに保存します。

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
テキスト間の差分に基づいて出力を生成し、ファイルに保存します。

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
内部メソッド

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Delete 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66;

**Returns:**
文字列値

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Equal 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66;

**Returns:**
文字列値

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Insert 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66;

**Returns:**
文字列値

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

削除操作の text-decoration: line-through スタイルを取得または設定します。デフォルト値は {@code False} です。

**Returns:**
ブール値

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Delete 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Equal 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Insert 操作の CSS スタイル文字列を取得および設定します。例: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

削除操作の text-decoration: line-through スタイルを取得または設定します。デフォルト値は {@code False} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
