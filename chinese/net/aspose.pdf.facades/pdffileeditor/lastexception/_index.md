---
title: "PdfFileEditor.LastException"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 属性。获取最近发生的异常。可用于检查失败原因。"
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException property

获取最近发生的异常。可用于检查失败原因。

```csharp
public Exception LastException { get; }
```

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
if (!pfe.TryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
{
   Console.WriteLine("Error occured:");
   if (pfe.LastException != null)
   {
       Console.WriteLine(pfe.LastException.Message);
       if (pfe.LastException.InnerException != null)
           Console.WriteLine(pfe.LastException.InnerException.Message);
   }
}
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


