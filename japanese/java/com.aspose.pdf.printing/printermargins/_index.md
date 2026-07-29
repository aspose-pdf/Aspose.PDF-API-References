---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "印刷されたページの余白の寸法を指定します。"
type: docs
weight: 70
url: /ja/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

印刷されたページの余白の寸法を指定します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | 1インチ幅の余白で Margins クラスの新しいインスタンスを初期化します。 |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | 指定された左、右、上、下の余白で Margins クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | このオブジェクトの複製をメンバーごとに取得します。 |
| [equals](#equals-java.lang.Object-) | この Margins を指定された Object と比較し、同じ寸法かどうかを判断します。(Object.Equals(Object) をオーバーライドします。) |
| [getBottom](#getBottom--) | インチの百分の一単位で下余白を取得または設定します。 |
| [getLeft](#getLeft--) | インチの百分の一単位で左余白幅を取得または設定します。 |
| [getRight](#getRight--) | インチの百分の一単位で右余白幅を取得または設定します。 |
| [getTop](#getTop--) | インチの百分の一単位で上余白幅を取得または設定します。 |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。） |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | 2つの Margins を比較し、同じ寸法かどうかを判断します。 |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | 2つの Margins を比較し、幅が異なるかどうかを判断します。 |
| [setBottom](#setBottom-int-) | インチの百分の一単位で下余白を取得または設定します。 |
| [setLeft](#setLeft-int-) | インチの百分の一単位で左余白幅を取得または設定します。 |
| [setRight](#setRight-int-) | インチの百分の一単位で右余白幅を取得または設定します。 |
| [setTop](#setTop-int-) | インチの百分の一単位で上余白幅を取得または設定します。 |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

1インチ幅の余白で Margins クラスの新しいインスタンスを初期化します。

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

指定された左、右、上、下の余白で Margins クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left |  | int 値です。 |
| 右 |  | int 値です。 |
| 上部 |  | int 値です。 |
| bottom |  | int 値です。 |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

このオブジェクトの複製をメンバーごとに取得します。

**Returns:**
PrinterMargins オブジェクト

### equals {#equals-java.lang.Object-}
この Margins を指定された Object と比較し、同じ寸法かどうかを判断します。(Object.Equals(Object) をオーバーライドします。)

### getBottom {#getBottom--}
```
public int getBottom()
```

インチの百分の一単位で下余白を取得または設定します。

**Returns:**
int 値です。

### getLeft {#getLeft--}
```
public int getLeft()
```

インチの百分の一単位で左余白幅を取得または設定します。

**Returns:**
int 値です。

### getRight {#getRight--}
```
public int getRight()
```

インチの百分の一単位で右余白幅を取得または設定します。

**Returns:**
int 値です。

### getTop {#getTop--}
```
public int getTop()
```

インチの百分の一単位で上余白幅を取得または設定します。

**Returns:**
int 値です。

### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。）

**Returns:**
このオブジェクトのハッシュコード値。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
2つの Margins を比較し、同じ寸法かどうかを判断します。

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
2つの Margins を比較し、幅が異なるかどうかを判断します。

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

インチの百分の一単位で下余白を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

インチの百分の一単位で左余白幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

インチの百分の一単位で右余白幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

インチの百分の一単位で上余白幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
