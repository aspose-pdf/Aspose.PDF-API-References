---
title: "Form.ImportXfdf"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Импортирует содержимое полей из файла xfdfxml и помещает их в новый PDF."
type: docs
weight: 300
url: /ru/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXfdfStream | Stream | Входной поток xfdf(xml). |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


