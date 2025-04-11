---
title: TiffDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TiffDevice メソッド。特定のドキュメントページを tiff に変換し、出力ストリームに保存します。
type: docs
weight: 90
url: /ja/net/aspose.pdf.devices/tiffdevice/process/
---
## Process(Document, int, int, Stream) {#process}

特定のドキュメントページを tiff に変換し、出力ストリームに保存します。

```csharp
public override void Process(Document document, int fromPage, int toPage, Stream output)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | Document | 変換するドキュメント。 |
| fromPage | Int32 | 変換を開始するページ番号を定義します。 |
| toPage | Int32 | 変換を終了するページ番号を定義します。 |
| output | Stream | tiff 画像を含む出力ストリーム。 |

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Page, Stream) {#process_4}

```csharp
public override void Process(Page page, Stream output)
```

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)