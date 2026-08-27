---
title: "PdfPageEditor.GetPageRotation"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfPageEditor. Возвращает поворот указанного page"
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation method

Возвращает поворот указанной страницы.

```csharp
public int GetPageRotation(int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Int32 | Индекс страницы. Страницы документа нумеруются с 1. |

### Возвращаемое значение

Page rotation в градусах.

## Примеры

Следующий пример демонстрирует, как получить page rotation:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### См. также

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


