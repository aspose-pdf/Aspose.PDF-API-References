---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DocumentDevice クラス。全てのデバイスのための抽象クラスで、PDF ドキュメント全体を処理するために使用されます。
type: docs
weight: 3570
url: /ja/net/aspose.pdf.devices/documentdevice/
---
## DocumentDevice クラス

PDF ドキュメント全体を処理するための全てのデバイスのための抽象クラスです。

```csharp
public abstract class DocumentDevice : PageDevice
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | ドキュメント全体を処理し、結果をストリームに保存します。 |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | ドキュメント全体を処理し、結果をファイルに保存します。 |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | 指定されたページに対して何らかの操作を実行します。例えば、ページをグラフィック画像に変換します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページに対して何らかの操作を実行し、結果をファイルに保存します。 |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | 各デバイスはドキュメントに対する何らかの操作を表します。例えば、PDF ドキュメントを別の形式に変換できます。 |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | ドキュメントの特定のページを処理し、結果をファイルに保存します。 |

### 参照

* クラス [PageDevice](../pagedevice/)
* 名前空間 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../)