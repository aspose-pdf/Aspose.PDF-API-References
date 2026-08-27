---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "単一フォントファイルのソースを表します。"
type: docs
weight: 1450
url: /ja/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

単一フォントファイルのソースを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | 新しい {@code FileFontSource} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | フォントファイルソースオブジェクトが等しいかどうかをチェックします。 |
| [getFilePath](#getFilePath--) | フォントファイルへのパスです。 |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。 <p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へと一貫している必要はありません。 <li>2 つのオブジェクトが {@code equals(Object)} メソッドにより等しいと判断される場合、両方のオブジェクトで {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li> {@link java.lang.Object#equals(java.lang.Object)} メソッドにより等しくないと判断された 2 つのオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} で定義された hashCode メソッドは異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java <span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語で必須ではありません。） |
| [setFilePath](#setFilePath-java.lang.String-) | フォントファイルへのパスです。 |

### FileFontSource {#FileFontSource-java.lang.String-}
新しい {@code FileFontSource} クラスのインスタンスを初期化します。

### equals {#equals-java.lang.Object-}
フォントファイルソースオブジェクトが等しいかどうかをチェックします。

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

フォントファイルへのパスです。

**Returns:**
文字列値

### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。 <p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へと一貫している必要はありません。 <li>2 つのオブジェクトが {@code equals(Object)} メソッドにより等しいと判断される場合、両方のオブジェクトで {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li> {@link java.lang.Object#equals(java.lang.Object)} メソッドにより等しくないと判断された 2 つのオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} で定義された hashCode メソッドは異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java <span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語で必須ではありません。）

**Returns:**
このオブジェクトのハッシュコード値。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
フォントファイルへのパスです。
