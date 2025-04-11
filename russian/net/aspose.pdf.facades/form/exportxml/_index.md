---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Метод Form. Экспортирует содержимое полей pdf в xml поток. Значение полей кнопок не будет экспортировано
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/form/exportxml/
---
## Метод Form.ExportXml

Экспортирует содержимое полей pdf в xml поток. Значение поля кнопки не будет экспортировано.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputXmlStream | Stream | Выходной Xml поток. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)