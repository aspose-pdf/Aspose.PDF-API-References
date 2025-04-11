---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfFileEditor. Получает последнее возникшее исключение. Может быть использовано для проверки причины сбоя
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## Свойство PdfFileEditor.LastException

Получает последнее возникшее исключение. Может быть использовано для проверки причины сбоя.

```csharp
public Exception LastException { get; }
```

## Примеры

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

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)