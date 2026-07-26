---
title: "DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメント全体を処理するために使用されるすべてのデバイスの抽象クラスです。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

PDF ドキュメント全体を処理するために使用されるすべてのデバイスの抽象クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | 各デバイスはドキュメント上のある操作を表します。たとえば、PDF ドキュメントを別の形式に変換できます。 |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | ドキュメントの特定のページを処理し、結果をファイルに保存します。 |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | ドキュメント全体を処理し、結果をストリームに保存します。 |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | ドキュメント全体を処理し、結果をファイルに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | 各デバイスはドキュメント上のある操作を表します。たとえば、 |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | ドキュメント全体を処理し、結果をストリームに保存します。 |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
各デバイスはドキュメント上のある操作を表します。たとえば、PDF ドキュメントを別の形式に変換できます。

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
ドキュメントの特定のページを処理し、結果をファイルに保存します。

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
ドキュメント全体を処理し、結果をストリームに保存します。

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
ドキュメント全体を処理し、結果をファイルに保存します。

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
各デバイスはドキュメント上のある操作を表します。たとえば、

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
ドキュメント全体を処理し、結果をストリームに保存します。
