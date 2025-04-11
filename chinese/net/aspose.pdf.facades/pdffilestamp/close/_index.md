---
title: PdfFileStamp.Close
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 方法。关闭已打开的文件并保存更改。警告。如果指定了输入或输出流，则它们不会被 Close 方法关闭。
type: docs
weight: 150
url: /zh/net/aspose.pdf.facades/pdffilestamp/close/
---
## PdfFileStamp.Close 方法

关闭已打开的文件并保存更改。警告。如果指定了输入或输出流，则它们不会被 Close() 方法关闭。

```csharp
public override void Close()
```

## 示例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
//do some work... 
stamp.Close();
```

### 另请参阅

* 类 [PdfFileStamp](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)