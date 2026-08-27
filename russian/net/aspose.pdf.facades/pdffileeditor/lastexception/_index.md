---
title: "PdfFileEditor.LastException"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfFileEditor. Возвращает последнее возникшее исключение. Может использоваться для проверки причины сбоя."
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException property

Получает последнее возникшее исключение. Может использоваться для проверки причины сбоя.

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

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


