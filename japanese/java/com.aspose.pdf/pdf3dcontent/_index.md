---
title: "PDF3DContent"
linktitle: "PDF3DContent"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF3DContent クラス。"
type: docs
weight: 3580
url: /ja/java/com.aspose.pdf/pdf3dcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DContent

```
public class PDF3DContent extends Object
```

PDF3DContent クラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PDF3DContent](#PDF3DContent--) | {@code PDF3DContent} クラスの新しいインスタンスを初期化します。 |
| [PDF3DContent](#PDF3DContent-java.lang.String-) | {@code PDF3DContent} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAsByteArray](#getAsByteArray--) | 3D コンテンツをバイト配列として取得します。 |
| [getAsStream](#getAsStream--) | 3D コンテンツをストリームとして取得します。 |
| [getExtension](#getExtension--) | 拡張子を取得します。 |
| [load](#load-java.lang.String-) | 指定されたファイル名で 3D コンテンツをロードします。 |
| [loadAsPRC](#loadAsPRC-byte:A-) | バイト配列から 3D コンテンツを PRC 形式でロードします。 |
| [loadAsPRC](#loadAsPRC-java.io.InputStream-) | ストリームから 3D コンテンツを PRC 形式でロードします。 |
| [loadAsPRC](#loadAsPRC-java.lang.String-) | 指定されたファイル名で 3D コンテンツを PRC 形式でロードします。 |
| [loadAsU3D](#loadAsU3D-byte:A-) | バイト配列から 3D コンテンツを U3D 形式でロードします。 |
| [loadAsU3D](#loadAsU3D-java.io.InputStream-) | ストリームから 3D コンテンツを U3D 形式でロードします。 |
| [loadAsU3D](#loadAsU3D-java.lang.String-) | 指定されたファイル名で 3D コンテンツを U3D 形式でロードします。 |
| [saveToFile](#saveToFile-java.lang.String-) | 3D コンテンツをファイルに保存します。 |

### PDF3DContent {#PDF3DContent--}
```
public PDF3DContent()
```

{@code PDF3DContent} クラスの新しいインスタンスを初期化します。

### PDF3DContent {#PDF3DContent-java.lang.String-}
{@code PDF3DContent} クラスの新しいインスタンスを初期化します。

### getAsByteArray {#getAsByteArray--}
```
public byte[] getAsByteArray()
```

3D コンテンツをバイト配列として取得します。

**Returns:**
System.Byte[].

### getAsStream {#getAsStream--}
```
public InputStream getAsStream()
```

3D コンテンツをストリームとして取得します。

**Returns:**
Stream.

### getExtension {#getExtension--}
```
public String getExtension()
```

拡張子を取得します。

**Returns:**
String object: 拡張子。

### load {#load-java.lang.String-}
指定されたファイル名で 3D コンテンツをロードします。

### loadAsPRC {#loadAsPRC-byte:A-}
```
public void loadAsPRC(byte[] stream)
```

バイト配列から 3D コンテンツを PRC 形式でロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream |  | ストリーム。 |

### loadAsPRC {#loadAsPRC-java.io.InputStream-}
ストリームから 3D コンテンツを PRC 形式でロードします。

### loadAsPRC {#loadAsPRC-java.lang.String-}
指定されたファイル名で 3D コンテンツを PRC 形式でロードします。

### loadAsU3D {#loadAsU3D-byte:A-}
```
public void loadAsU3D(byte[] stream)
```

バイト配列から 3D コンテンツを U3D 形式でロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream |  | ストリーム。 |

### loadAsU3D {#loadAsU3D-java.io.InputStream-}
ストリームから 3D コンテンツを U3D 形式でロードします。

### loadAsU3D {#loadAsU3D-java.lang.String-}
指定されたファイル名で 3D コンテンツを U3D 形式でロードします。

### saveToFile {#saveToFile-java.lang.String-}
3D コンテンツをファイルに保存します。
