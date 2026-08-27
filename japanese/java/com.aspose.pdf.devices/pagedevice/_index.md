---
title: "PageDevice"
linktitle: "PageDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントの特定のページを処理するために使用されるすべてのデバイスの抽象クラスです。"
type: docs
weight: 150
url: /ja/java/com.aspose.pdf.devices/pagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice

```
public abstract class PageDevice extends Device
```

PDF ドキュメントの特定のページを処理するために使用されるすべてのデバイスの抽象クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageDevice](#PageDevice--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | ページをグラフィックス上にレンダリングします |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | 指定されたページに対して何らかの操作を実行します。例：ページをグラフィック画像に変換します。 |
| [process](#process-com.aspose.pdf.Page-java.lang.String-) | 指定されたページに対して何らかの操作を実行し、結果をファイルに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 指定されたページに対して何らかの操作を実行します（e.g.）。 |

### PageDevice {#PageDevice--}
```
public PageDevice()
```



### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
ページをグラフィックス上にレンダリングします

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
指定されたページに対して何らかの操作を実行します。例：ページをグラフィック画像に変換します。

### process {#process-com.aspose.pdf.Page-java.lang.String-}
指定されたページに対して何らかの操作を実行し、結果をファイルに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
指定されたページに対して何らかの操作を実行します（e.g.）。
