---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "単一フォントファイルのソースを表します。"
type: docs
weight: 3040
url: /ja/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

単一フォントファイルのソースを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | {@code MemoryFontSource} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [close](#close--) | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [dispose](#dispose--) | 内部リソースを解放します。このメソッドは非推奨で、代わりに close() を使用してください。 |
| [equals](#equals-java.lang.Object-) | フォントファイルソースオブジェクトが等しいかどうかをチェックします。 |
| [getFontBytes](#getFontBytes--) | フォントファイルのバイト配列です。 |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。） |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

{@code MemoryFontSource} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontBytes |  | フォントファイルのバイト配列です。 |

### close {#close--}
```
public void close()
```

このドキュメントで使用されているすべてのリソースを閉じます。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

内部リソースを解放します。このメソッドは非推奨で、代わりに close() を使用してください。

### equals {#equals-java.lang.Object-}
フォントファイルソースオブジェクトが等しいかどうかをチェックします。

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

フォントファイルのバイト配列です。

**Returns:**
byte[] 配列

### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。）

**Returns:**
このオブジェクトのハッシュコード値。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
