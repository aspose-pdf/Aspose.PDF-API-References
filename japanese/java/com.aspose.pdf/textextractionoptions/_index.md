---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト抽出オプションを表します"
type: docs
weight: 5060
url: /ja/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

テキスト抽出オプションを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | 指定されたテキスト書式モード用に {@code TextExtractionOptions} オブジェクトの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | 書式モードを取得します。 |
| [getScaleFactor](#getScaleFactor--) | 純粋モードで抽出中にフォントサイズをスケーリングする際に適用される係数を取得します。値を小さく設定すると抽出テキストにスペースが多くなります。デフォルト値は 1 でスケーリングなしです。値を 0 に設定するとアルゴリズムが自動的にスケーリングを選択します。 |
| [setFormattingMode](#setFormattingMode-int-) | 書式モードを設定します。 |
| [setScaleFactor](#setScaleFactor-double-) | 純粋モードで抽出中にフォントサイズをスケーリングする際に適用される係数を設定します。値を小さく設定すると抽出テキストにスペースが多くなります（1 から 10 の範囲）。デフォルト値は 1 でスケーリングなしです。値を 0 に設定するとアルゴリズムが自動的にスケーリングを選択します。 |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

指定されたテキスト書式モード用に {@code TextExtractionOptions} オブジェクトの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattingMode |  | テキスト書式モードの値。 @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

書式モードを取得します。

**Returns:**
TextFormattingMode の値 @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

純粋モードで抽出中にフォントサイズをスケーリングする際に適用される係数を取得します。値を小さく設定すると抽出テキストにスペースが多くなります。デフォルト値は 1 でスケーリングなしです。値を 0 に設定するとアルゴリズムが自動的にスケーリングを選択します。

**Returns:**
double 値

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

書式モードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | TextFormattingMode の値 @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

純粋モードで抽出中にフォントサイズをスケーリングする際に適用される係数を設定します。値を小さく設定すると抽出テキストにスペースが多くなります（1 から 10 の範囲）。デフォルト値は 1 でスケーリングなしです。値を 0 に設定するとアルゴリズムが自動的にスケーリングを選択します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
