---
title: PdfFileStamp.Close
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp メソッド。開いているファイルを閉じて変更を保存します。警告。入力または出力ストリームが指定されている場合、Close メソッドによってそれらは閉じられません。
type: docs
weight: 150
url: /ja/net/aspose.pdf.facades/pdffilestamp/close/
---
## PdfFileStamp.Close メソッド

開いているファイルを閉じて変更を保存します。警告。入力または出力ストリームが指定されている場合、Close() メソッドによってそれらは閉じられません。

```csharp
public override void Close()
```

## 例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
//do some work... 
stamp.Close();
```

### 参照

* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)