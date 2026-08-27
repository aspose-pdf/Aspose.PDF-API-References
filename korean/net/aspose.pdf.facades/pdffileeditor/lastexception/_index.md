---
title: "PdfFileEditor.LastException"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 속성. 마지막 발생한 예외를 가져옵니다. 실패 이유를 확인하는 데 사용할 수 있습니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException property

마지막 발생한 예외를 가져옵니다. 실패 원인을 확인하는 데 사용할 수 있습니다.

```csharp
public Exception LastException { get; }
```

## 예제

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

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


