---
title: "Form.ImportJson"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Импортирует все данные полей из JSON‑потока в поля документа, сопоставляя их по полным именам."
type: docs
weight: 290
url: /ru/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson method

Импортирует все данные полей из потока JSON в поля документа, сопоставляя поля по их полным именам.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputJsonStream | Stream | Входной JSON‑поток, содержащий данные полей для импорта в поля документа. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


