---
title: PdfFileStamp.Close
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileStamp. Закрывает открытые файлы и сохраняет изменения. Внимание. Если указаны входные или выходные потоки, они не закрываются методом Close
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/pdffilestamp/close/
---
## Метод PdfFileStamp.Close

Закрывает открытые файлы и сохраняет изменения. Внимание. Если указаны входные или выходные потоки, они не закрываются методом Close().

```csharp
public override void Close()
```

## Примеры

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
//do some work... 
stamp.Close();
```

### См. также

* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)