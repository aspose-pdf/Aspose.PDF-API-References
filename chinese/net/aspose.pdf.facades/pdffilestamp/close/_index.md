---
title: "PdfFileStamp.Close"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileStamp 方法。关闭已打开的文件并保存更改。警告：如果指定了输入或输出流，Close 方法不会关闭它们"
type: docs
weight: 150
url: /zh/net/aspose.pdf.facades/pdffilestamp/close/
---
## PdfFileStamp.Close method

关闭已打开的文件并保存更改。警告：如果指定了输入或输出流，Close() 方法不会关闭它们。

```csharp
public override void Close()
```

## 示例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
//执行一些操作... 
stamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


