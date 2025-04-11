---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OptimizedMemoryStream クラス。標準容量を超える MemoryStream を定義します
type: docs
weight: 7990
url: /ja/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream クラス

標準容量を超える MemoryStream を定義します

```csharp
public class OptimizedMemoryStream : Stream
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | `OptimizedMemoryStream` クラスの新しいインスタンスを初期化します。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | 指定されたバイト配列に基づいて `OptimizedMemoryStream` クラスの新しいインスタンスを初期化します。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | `OptimizedMemoryStream` クラスの新しいインスタンスを初期化します。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | 指定されたバイト配列に基づいて `OptimizedMemoryStream` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | 基になるバッファのサイズを取得または設定します。 |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | 派生クラスでオーバーライドされた場合、現在のストリームが読み取りをサポートしているかどうかを示す値を取得します。 |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | 派生クラスでオーバーライドされた場合、現在のストリームがシークをサポートしているかどうかを示す値を取得します。 |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | 派生クラスでオーバーライドされた場合、現在のストリームが書き込みをサポートしているかどうかを示す値を取得します。 |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Dispose 時に基になるバッファを解放するかどうかを示す値を取得または設定します。 |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | 派生クラスでオーバーライドされた場合、ストリームのバイト数を取得します。 |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | 派生クラスでオーバーライドされた場合、現在のストリーム内の位置を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | オーバーライドされた関数です。 |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | 派生クラスでオーバーライドされた場合、現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | ストリームからバイトを読み取り、ストリーム内の位置を1バイト進めます。ストリームの終わりに達した場合は -1 を返します。 |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | 派生クラスでオーバーライドされた場合、現在のストリーム内の位置を設定します。 |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | 派生クラスでオーバーライドされた場合、現在のストリームの長さを設定します。 |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | 現在のストリームをバイト配列に変換します。 |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | 派生クラスでオーバーライドされた場合、現在のストリームにバイトのシーケンスを書き込み、書き込んだバイト数だけこのストリーム内の現在の位置を進めます。 |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | 現在のストリームの位置にバイトを書き込み、ストリーム内の位置を1バイト進めます。 |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | 指定されたストリームに書き込みます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | バイト単位のデフォルトバッファサイズの値。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)