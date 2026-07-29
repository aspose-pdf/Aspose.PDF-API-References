---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "用紙のサイズを指定します。"
type: docs
weight: 100
url: /ja/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

用紙のサイズを指定します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | PaperSize クラスの新しいインスタンスを初期化します。 |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | PaperSize クラスの新しいインスタンスを初期化します。 |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | PaperSize クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeight](#getHeight--) | 用紙の高さ（インチの百分の一単位）を取得または設定します。 |
| [getKind](#getKind--) | 用紙の種類を取得します。 |
| [getPaperName](#getPaperName--) | 用紙の種類名を取得または設定します。 |
| [getRawKind](#getRawKind--) | PaperSize のいずれかの値またはカスタム値を表す整数を取得または設定します。 |
| [getWidth](#getWidth--) | 用紙の幅（インチの百分の一単位）を取得または設定します。 |
| [setHeight](#setHeight-int-) | 用紙の高さ（インチの百分の一単位）を取得または設定します。 |
| [setPaperName](#setPaperName-java.lang.String-) | 用紙の種類名を取得します。 |
| [setWidth](#setWidth-int-) | 用紙の幅（インチの百分の一単位）を設定します。 |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | {@link PaperSize} を Windows 固有の System.Drawing.Printing.PaperSize に変換します。 |
| [toString](#toString--) | このインスタンスの名前を取得します。 |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

PaperSize クラスの新しいインスタンスを初期化します。

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
PaperSize クラスの新しいインスタンスを初期化します。

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
PaperSize クラスの新しいインスタンスを初期化します。

### getHeight {#getHeight--}
```
public int getHeight()
```

用紙の高さ（インチの百分の一単位）を取得または設定します。

**Returns:**
int 値です。

### getKind {#getKind--}
```
public int getKind()
```

用紙の種類を取得します。

**Returns:**
int 値 @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

用紙の種類名を取得または設定します。

**Returns:**
文字列値

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

PaperSize のいずれかの値またはカスタム値を表す整数を取得または設定します。

**Returns:**
int 値です。

### getWidth {#getWidth--}
```
public int getWidth()
```

用紙の幅（インチの百分の一単位）を取得または設定します。

**Returns:**
int 値です。

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

用紙の高さ（インチの百分の一単位）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPaperName {#setPaperName-java.lang.String-}
用紙の種類名を取得します。

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

用紙の幅（インチの百分の一単位）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
{@link PaperSize} を Windows 固有の System.Drawing.Printing.PaperSize に変換します。

### toString {#toString--}
```
public String toString()
```

このインスタンスの名前を取得します。

**Returns:**
文字列値
