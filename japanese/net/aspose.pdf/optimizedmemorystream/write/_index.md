---
title: "OptimizedMemoryStream.Write"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OptimizedMemoryStream メソッド。派生クラスでオーバーライドされた場合、バイトのシーケンスを書き込み、現在のストリーム内の位置を書き込まれたバイト数だけ進めます"
type: docs
weight: 150
url: /ja/net/aspose.pdf/optimizedmemorystream/write/
---
## OptimizedMemoryStream.Write method

派生クラスでオーバーライドされた場合、現在のストリームにバイトのシーケンスを書き込み、書き込んだバイト数だけこのストリーム内の現在位置を進めます。

```csharp
public override void Write(byte[] buffer, int offset, int count)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| バッファ | Byte[] | バイトの配列。このメソッドは *count* バイトを *buffer* から現在のストリームへコピーします |
| オフセット | Int32 | バイトオフセット（0 ベース）*buffer* 内で、現在のストリームへバイトのコピーを開始する位置です |
| カウント | Int32 | 現在のストリームに書き込むバイト数。 |

### 関連項目

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


