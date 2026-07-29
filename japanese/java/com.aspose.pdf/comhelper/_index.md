---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> COM クライアントが Aspose.PDF にドキュメントをロードするためのメソッドを提供します。 </p> <hr> <p> ComHelper クラスを使用して、ファイルまたはストリームからドキュメントをロードし、Document オブジェクトに変換します。</p>"
type: docs
weight: 760
url: /ja/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> COM クライアントがドキュメントを Aspose.PDF にロードするためのメソッドを提供します。 </p> <hr> <p> COM アプリケーションでファイルまたはストリームからドキュメントを Document オブジェクトにロードするには ComHelper クラスを使用します。Document クラスは新しいドキュメントを作成するデフォルトコンストラクタを提供し、ファイルまたはストリームからロードするためのオーバーロードされたコンストラクタも提供します。.NET アプリケーションで Aspose.Words を使用している場合は、すべての Document コンストラクタを直接使用できますが、COM アプリケーションで Aspose.PDF を使用している場合は、デフォルトの Document コンストラクタのみが利用可能です。 </p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | {@code filename} を使用して Document を作成し返します。{@code Document(Stream)} と同等です。 |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | 必要な変換オプションを指定して、ファイルから既存のドキュメントを開き、PDF ドキュメントを取得します。 |
| [openFile](#openFile-java.lang.String-java.lang.String-) | 暗号化されたドキュメントを操作するために、{@code Document} クラスの新しいインスタンスを初期化して返します。 |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | 暗号化されたドキュメントを操作するために、{@code Document} クラスの新しいインスタンスを初期化します。 |
| [openStream](#openStream-java.io.InputStream-) | {@code input} ストリームから新しい Document インスタンスを初期化して返します。 |
| [openStream](#openStream-java.io.InputStream-boolean-) | {@code input} ストリームから新しい Document インスタンスを初期化して返します。 |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | 必要な変換を行いながら、ストリームから既存のドキュメントを開き、返します。 |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | {@code input} ストリームから新しい Document インスタンスを初期化して返します。 |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | {@code input} ストリームから新しい Document インスタンスを初期化して返します。 |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
{@code filename} を使用して Document を作成し返します。{@code Document(Stream)} と同等です。

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
必要な変換オプションを指定して、ファイルから既存のドキュメントを開き、PDF ドキュメントを取得します。

### openFile {#openFile-java.lang.String-java.lang.String-}
暗号化されたドキュメントを操作するために、{@code Document} クラスの新しいインスタンスを初期化して返します。

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
暗号化されたドキュメントを操作するために、{@code Document} クラスの新しいインスタンスを初期化します。

### openStream {#openStream-java.io.InputStream-}
{@code input} ストリームから新しい Document インスタンスを初期化して返します。

### openStream {#openStream-java.io.InputStream-boolean-}
{@code input} ストリームから新しい Document インスタンスを初期化して返します。

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
必要な変換を行いながら、ストリームから既存のドキュメントを開き、返します。

### openStream {#openStream-java.io.InputStream-java.lang.String-}
{@code input} ストリームから新しい Document インスタンスを初期化して返します。

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
{@code input} ストリームから新しい Document インスタンスを初期化して返します。
