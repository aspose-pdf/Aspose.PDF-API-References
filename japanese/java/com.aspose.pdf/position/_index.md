---
title: "Position"
linktitle: "Position"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "位置オブジェクトを表します。"
type: docs
weight: 3940
url: /ja/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

位置オブジェクトを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Position](#Position-double-double-) | 新しい {@code Position} クラスのインスタンスを初期化します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | 指定されたオブジェクトが現在の {@code Position} オブジェクトと等しいかどうかを判断します。 |
| [getXIndent](#getXIndent--) | オブジェクトの X 座標を取得します |
| [getYIndent](#getYIndent--) | オブジェクトの Y 座標を取得します |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。） |
| [setXIndent](#setXIndent-double-) | オブジェクトの X 座標を設定します |
| [setYIndent](#setYIndent-double-) | オブジェクトの Y 座標を設定します |
| [toString](#toString--) | 現在の {@code Position} オブジェクトの文字列表現を取得します。 |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

新しい {@code Position} クラスのインスタンスを初期化します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xIndent |  | X 座標の値。 |
| yIndent |  | Y 座標の値。 |

### equals {#equals-java.lang.Object-}
指定されたオブジェクトが現在の {@code Position} オブジェクトと等しいかどうかを判断します。

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

オブジェクトの X 座標を取得します

**Returns:**
double 値

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

オブジェクトの Y 座標を取得します

**Returns:**
double 値

### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。）

**Returns:**
このオブジェクトのハッシュコード値。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

オブジェクトの X 座標を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

オブジェクトの Y 座標を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### toString {#toString--}
```
public String toString()
```

現在の {@code Position} オブジェクトの文字列表現を取得します。

**Returns:**
Position オブジェクトの文字列表現。
