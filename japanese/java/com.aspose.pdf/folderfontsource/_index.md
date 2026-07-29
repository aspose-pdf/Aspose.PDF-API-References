---
title: "FolderFontSource"
linktitle: "FolderFontSource"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォントファイルを含むフォルダーを表します。"
type: docs
weight: 1640
url: /ja/java/com.aspose.pdf/folderfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FolderFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FolderFontSource

```
public final class FolderFontSource extends FontSource
```

フォントファイルを含むフォルダーを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FolderFontSource](#FolderFontSource-java.lang.String-) | 新しい {@code FolderFontSource} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | フォルダー フォント ソース オブジェクトが等しいかどうかを確認します。 |
| [getFolderPath](#getFolderPath--) | フォント ファイルを含むフォルダーへのパス。 |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。） |
| [setFolderPath](#setFolderPath-java.lang.String-) |  |

### FolderFontSource {#FolderFontSource-java.lang.String-}
新しい {@code FolderFontSource} クラスのインスタンスを初期化します。

### equals {#equals-java.lang.Object-}
フォルダー フォント ソース オブジェクトが等しいかどうかを確認します。

### getFolderPath {#getFolderPath--}
```
public String getFolderPath()
```

フォント ファイルを含むフォルダーへのパス。

**Returns:**
文字列値

### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。）

**Returns:**
このオブジェクトのハッシュコード値。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFolderPath {#setFolderPath-java.lang.String-}
