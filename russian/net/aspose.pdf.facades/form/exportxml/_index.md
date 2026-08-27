---
title: "Form.ExportXml"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Экспортирует содержимое полей pdf в xml‑поток. Значения полей кнопок не будут экспортированы"
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml method

Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputXmlStream | Stream | Выводной Xml‑поток. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


