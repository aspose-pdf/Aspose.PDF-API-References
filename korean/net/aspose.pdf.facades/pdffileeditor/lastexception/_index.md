---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 속성. 마지막으로 발생한 예외를 가져옵니다. 실패의 원인을 확인하는 데 사용할 수 있습니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException 속성

마지막으로 발생한 예외를 가져옵니다. 실패의 원인을 확인하는 데 사용할 수 있습니다.

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

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)