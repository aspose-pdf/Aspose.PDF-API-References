---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "より標準的な容量を含むことができる MemoryStream を定義します。"
type: docs
weight: 3220
url: /ja/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

より標準的な容量を含むことができる MemoryStream を定義します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | デフォルトのバッファサイズ（バイト単位）の値です。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | 新しい {@link OptimizedMemoryStream} クラスのインスタンスを初期化します。 |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | 指定されたバイト配列に基づいて、新しい {@link OptimizedMemoryStream} クラスのインスタンスを初期化します。 |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | 新しい {@link OptimizedMemoryStream} クラスのインスタンスを初期化します。 |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | 指定されたバイト配列に基づいて、新しい {@link OptimizedMemoryStream} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [canRead](#canRead--) | 派生クラスでオーバーライドされた場合、現在のストリームが読み取りをサポートしているかどうかを示す値を取得します。 |
| [canSeek](#canSeek--) | 派生クラスでオーバーライドされた場合、現在のストリームがシークをサポートしているかどうかを示す値を取得します。 |
| [canWrite](#canWrite--) | 派生クラスでオーバーライドされた場合、現在のストリームが書き込みをサポートしているかどうかを示す値を取得します。 |
| [flush](#flush--) | 関数がオーバーライドされました。 |
| [getBufferSize](#getBufferSize--) | 基底バッファのサイズを取得または設定します。値: バッファのサイズです。 |
| [getFreeOnDispose](#getFreeOnDispose--) | 破棄時に基底バッファを解放するかどうかを示す値を取得または設定します。 |
| [getLength](#getLength--) | 派生クラスでオーバーライドされた場合、ストリームの長さ（バイト単位）を取得します。 |
| [getPosition](#getPosition--) | 派生クラスでオーバーライドされた場合、現在のストリーム内の位置を取得または設定します。 |
| [read](#read-byte:A-int-int-) | 派生クラスでオーバーライドされた場合、現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| [readByte](#readByte--) | ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めます。ストリームの末尾に達した場合は -1 を返します。 |
| [seek](#seek-long-int-) | 派生クラスでオーバーライドされた場合、現在のストリーム内の位置を設定します。 |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | 派生クラスでオーバーライドされた場合、現在のストリーム内の位置を設定します。 |
| [setBufferSize](#setBufferSize-int-) | 基底バッファのサイズを取得または設定します。値: バッファのサイズです。 |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | 破棄時に基底バッファを解放するかどうかを示す値を取得または設定します。 |
| [setLength](#setLength-long-) | 派生クラスでオーバーライドされた場合、現在のストリームの長さを設定します。 |
| [setPosition](#setPosition-long-) | 派生クラスでオーバーライドされた場合、現在のストリーム内の位置を取得または設定します。ストリーム内の現在の位置です。値: |
| [toArray](#toArray--) | 現在のストリームをバイト配列に変換します。 |
| [write](#write-byte:A-int-int-) | 派生クラスでオーバーライドされた場合、現在のストリームにバイトのシーケンスを書き込み、書き込んだバイト数だけこのストリーム内の現在位置を進めます。 |
| [writeByte](#writeByte-byte-) | ストリームの現在位置に 1 バイトを書き込み、ストリーム内の位置を 1 バイト進めます。 |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | 指定されたストリームに書き込みます。 |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

デフォルトのバッファサイズ（バイト単位）の値です。

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

新しい {@link OptimizedMemoryStream} クラスのインスタンスを初期化します。

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

指定されたバイト配列に基づいて、新しい {@link OptimizedMemoryStream} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バッファ |  | 現在のストリームを作成するための符号なしバイトの配列です。 |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

新しい {@link OptimizedMemoryStream} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バッファサイズ |  | 基礎となるバッファのサイズです。 |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

指定されたバイト配列に基づいて、新しい {@link OptimizedMemoryStream} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バッファサイズ |  | 基礎となるバッファのサイズです。 |
| バッファ |  | 現在のストリームを作成するための符号なしバイトの配列です。 |

### canRead {#canRead--}
```
public boolean canRead()
```

派生クラスでオーバーライドされた場合、現在のストリームが読み取りをサポートしているかどうかを示す値を取得します。

**Returns:**
ストリームが読み取りをサポートしている場合は true、そうでない場合は false。値:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

派生クラスでオーバーライドされた場合、現在のストリームがシークをサポートしているかどうかを示す値を取得します。

**Returns:**
ストリームがシークをサポートしている場合は true、そうでない場合は false。値:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

派生クラスでオーバーライドされた場合、現在のストリームが書き込みをサポートしているかどうかを示す値を取得します。

**Returns:**
ストリームが書き込みをサポートしている場合は true、そうでない場合は false。値:

### flush {#flush--}
```
public void flush()
```

関数がオーバーライドされました。

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

基底バッファのサイズを取得または設定します。値: バッファのサイズです。

**Returns:**
int 値です。

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

破棄時に基底バッファを解放するかどうかを示す値を取得または設定します。

**Returns:**
ブール値

### getLength {#getLength--}
```
public long getLength()
```

派生クラスでオーバーライドされた場合、ストリームの長さ（バイト単位）を取得します。

**Returns:**
ストリームの長さ（バイト単位）を表す long 値です。値:

### getPosition {#getPosition--}
```
public long getPosition()
```

派生クラスでオーバーライドされた場合、現在のストリーム内の位置を取得または設定します。

**Returns:**
ストリーム内の現在位置です。値:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

派生クラスでオーバーライドされた場合、現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バッファ |  | バイト配列です。このメソッドが戻ると、バッファには指定されたバイト配列が値として含まれます |
| オフセット |  | 現在のストリームから読み取ったデータの格納を開始する、ゼロベースのバイトオフセットです。 |
| カウント |  | 現在のストリームから読み取る最大バイト数です。 |

**Returns:**
バッファに読み込まれたバイト総数です。要求されたバイト数より少ない場合があります（利用可能なバイトが不足している場合）、またはストリームの終端に達した場合はゼロ (0) になります。

### readByte {#readByte--}
```
public int readByte()
```

ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めます。ストリームの末尾に達した場合は -1 を返します。

**Returns:**
バイト、またはストリームの終端に達した場合は -1。

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

派生クラスでオーバーライドされた場合、現在のストリーム内の位置を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| オフセット |  |  {@code origin} パラメータに対するバイトオフセットです。 |
| origin |  | 新しい位置を取得するために使用される基準点を示す {@link SeekOrigin} 型の値です。 |

**Returns:**
現在のストリーム内の新しい位置です。

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
派生クラスでオーバーライドされた場合、現在のストリーム内の位置を設定します。

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

基底バッファのサイズを取得または設定します。値: バッファのサイズです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

破棄時に基底バッファを解放するかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

派生クラスでオーバーライドされた場合、現在のストリームの長さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 現在のストリームの希望する長さ（バイト単位）です。 |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

派生クラスでオーバーライドされた場合、現在のストリーム内の位置を取得または設定します。ストリーム内の現在の位置です。値:

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

現在のストリームをバイト配列に変換します。

**Returns:**
バイト配列

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

派生クラスでオーバーライドされた場合、現在のストリームにバイトのシーケンスを書き込み、書き込んだバイト数だけこのストリーム内の現在位置を進めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バッファ |  | バイト配列です。このメソッドは {@code count} バイトを {@code buffer} から現在のストリームへコピーします。 |
| オフセット |  | 現在のストリームへバイトをコピーし始める {@code buffer} 内のゼロベースのバイトオフセットです。 |
| カウント |  | 現在のストリームに書き込まれるバイト数です。 |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

ストリームの現在位置に 1 バイトを書き込み、ストリーム内の位置を 1 バイト進めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ストリームに書き込むバイト。 |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
指定されたストリームに書き込みます。
