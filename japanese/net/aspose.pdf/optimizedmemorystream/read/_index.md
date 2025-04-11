---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: OptimizedMemoryStream メソッド。派生クラスでオーバーライドされた場合、現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。
type: docs
weight: 100
url: /ja/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read メソッド

派生クラスでオーバーライドされた場合、現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | Byte[] | バイトの配列。このメソッドが返されると、バッファには指定されたバイト配列の値が含まれます。 |
| offset | Int32 | 現在のストリームから読み取ったデータを格納し始めるゼロベースのバイトオフセット。 |
| count | Int32 | 現在のストリームから読み取る最大バイト数。 |

### 戻り値

バッファに読み込まれたバイトの合計数。これは、要求されたバイト数よりも少ない場合があり、その場合は現在利用可能なバイト数がそれほど多くないか、ストリームの終わりに達した場合はゼロ (0) になります。

### 参照

* クラス [OptimizedMemoryStream](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)