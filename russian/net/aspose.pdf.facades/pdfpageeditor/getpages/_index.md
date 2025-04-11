---
title: PdfPageEditor.GetPages
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfPageEditor. Возвращает общее количество страниц
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/pdfpageeditor/getpages/
---
## Метод PdfPageEditor.GetPages

Возвращает общее количество страниц.

```csharp
public int GetPages()
```

### Возвращаемое значение

Количество страниц.

## Примеры

Следующий пример демонстрирует использование метода GetPages():

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
Console.WriteLine("Document has: " + editor.GetPages());
```

### См. также

* класс [PdfPageEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)