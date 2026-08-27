---
title: "OptimizedMemoryStream.Read"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OptimizedMemoryStream メソッド。派生クラスでオーバーライドされた場合、現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます"
type: docs
weight: 100
url: /ja/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

派生クラスでオーバーライドされた場合、現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| バッファ | Byte[] | バイトの配列。このメソッドが戻ると、バッファには指定されたバイト配列が値として格納されています |
| オフセット | Int32 | バイトオフセット（0 ベース）で、現在のストリームから読み取ったデータの格納を開始する位置です |
| カウント | Int32 | 現在のストリームから読み取る最大バイト数。 |

### 戻り値

バッファに読み取られた総バイト数。要求されたバイト数より少ない場合があります（利用可能なバイトが不足している場合）、またはストリームの末尾に達した場合は 0（ゼロ）になります。

### 関連項目

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


