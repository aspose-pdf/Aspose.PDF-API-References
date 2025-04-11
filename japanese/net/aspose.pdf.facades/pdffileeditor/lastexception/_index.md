---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor プロパティ。最後に発生した例外を取得します。失敗の理由を確認するために使用できます。
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException プロパティ

最後に発生した例外を取得します。失敗の理由を確認するために使用できます。

```csharp
public Exception LastException { get; }
```

## 例

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

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)